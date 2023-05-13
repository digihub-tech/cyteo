<template>
  <div>
    <p>{{ chineseDateTime }}</p>
  </div>
</template>

<script lang="ts">

import { defineComponent, ref, onMounted, onBeforeUnmount } from 'vue';
import { DateTime } from 'luxon'

export default defineComponent({
  setup() {
    const chineseDateTime = ref('');

    const updateChineseDateTime = () => {
      const dt = DateTime.local().setLocale('zh');
      const chineseWeekday = dt.toFormat('EEEE');
      const chineseDate = dt.toFormat('yyyy 年 MM 月 dd 日');
      const chineseTime = dt.toFormat('HH:mm:ss');

      chineseDateTime.value = `${chineseWeekday}，${chineseDate} ${chineseTime}`;
    };

    let timerId: number;

    onMounted(() => {
      updateChineseDateTime();
      timerId = setInterval(updateChineseDateTime, 1000);
    });

    onBeforeUnmount(() => {
      clearInterval(timerId);
    });

    return {
      chineseDateTime,
    };
  },
});
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=ZCOOL+KuaiLe&display=swap');
p{
  font-family: 'ZCOOL KuaiLe', sans-serif;
  color:#D5CEA3;
  font-size: 1.3rem;
}
</style>