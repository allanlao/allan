<template>
  <div class="flex justify-center items-center h-screen">
    <div  class="flex flex-col w-1/3">
      <div class="flex flex-wrap bg-gray-300 p-8 justify-start">
        <label for="department" class="w-full text-left">Department</label>
        <input type="text" id="department" class="border-gray-900 w-full" />
      </div>

      <div class="flex justify-end p-2 bg-gray-200 ">
        <button class="bg-indigo-900 text-white rounded-md p-2">
          Create Department
        </button>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
</style>