<template>
    <c-stack></c-stack>
</template>

<script lang="ts">
import Vue from 'vue';
import { CStack } from '@chakra-ui/vue';

export default Vue.extend({
    name: 'Navbar',
    components: {
        CStack,
    },
});
</script>