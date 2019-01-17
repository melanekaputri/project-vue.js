<template>
    <div>

    </div>
</template>

<script>
    import Input from './Input.vue'
    export  default {
        data() {
          return {
            message: 'This is A great Message!'
          }
      },
      components: {
          'app-input': Input
      }
    }
</script>
