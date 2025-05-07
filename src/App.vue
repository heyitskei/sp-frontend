<template>
  <div
    :style="{
      display: 'flex',
      justifyContent: 'center',
      alignItems: 'flex-start',
      height: '100vh',
    }"
  >
    <button
      @click="onClick"
      class="bg-slate-500 hover:bg-slate-700 text-white font-bold py-2 px-4 rounded m-10"
    >
      <img src="/vehikl.svg" width="40" height="40" />Vehikl + Growth
    </button>
  </div>
</template>
<script setup lang="ts">
const onClick = () => {
  alert("Let's Learn!");
};
</script>
