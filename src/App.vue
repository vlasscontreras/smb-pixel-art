<template>
  <div class="overworld">
    <Brick />
    <Question />
    <Floor />
  </div>
</template>

<script lang="ts">
import Vue from 'vue';

import Brick from '@/components/blocks/Brick.vue';
import Floor from '@/components/blocks/Floor.vue';
import Question from '@/components/blocks/Question.vue';

export default Vue.extend({
  name: 'App',
  components: {
    Brick,
    Floor,
    Question,
  },
});
</script>
