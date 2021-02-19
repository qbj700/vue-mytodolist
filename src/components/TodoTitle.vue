<template>
  <div class="title text-left pl-4">
    <p class="title__message">{{ message }}</p>
    <p class="title__task font-bold flex flex-col">
      <span class="py-4">You've got</span>
      <span class="title__task-total text-5xl">{{ taskTotal }}</span> 
      <span class="py-4">tasks today.</span>
    </p>
  </div>
</template>
 
<script>
export default {
  data() {
    return {
      message: "Good Morning",
      taskTotal: 5
    };
  }
};
</script>