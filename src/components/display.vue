<template>
  <div class='display'>
      {{ value }}
  </div>
</template>

<script>
export default {
  props: ['value']
}
</script>

<style>
  .display{
    grid-column: span 4;
    background-color: #0005;
    
    display: flex;
    align-items: center;
    justify-content: flex-end;
    padding: 20px;
    font-size: 2.2em;
    overflow: hidden;
  }
</style>