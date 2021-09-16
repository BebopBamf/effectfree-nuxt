<template>
    <c-theme-provider>
        <c-reset />
        <Nuxt />
    </c-theme-provider>
</template>

<script lang="ts">
import Vue from 'vue';
import { CThemeProvider, CReset } from '@chakra-ui/vue';

export default Vue.extend({
    name: 'App',
    components: {
        CThemeProvider,
        CReset,
    },
});
</script>
