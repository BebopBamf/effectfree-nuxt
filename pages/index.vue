<template>
  <c-stack>
    <CommonNavbar />
    <c-box>
        <c-heading text-align="center">EFFECT FREE</c-heading>
        <c-text text-align="center">About everything under the sun, except for the side effects</c-text>
    </c-box>
  </c-stack>
</template>

<script lang="ts">
import Vue from 'vue';
import { CStack, CBox, CHeading, CText } from '@chakra-ui/vue';

export default Vue.extend({
    name: 'HomePage',
    components: {
        CStack,
        CBox,
        CHeading,
        CText,
    },
});
</script>
