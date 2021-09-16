<template>
    <c-flex as="nav">
        <c-flex justify="center"> 
            <c-box>
                <c-text font-size="lg" font-weight="bold">EFFECT FREE</c-text>
            </c-box>
        </c-flex>
    </c-flex>
</template>

<script lang="ts">
import Vue from 'vue';
import { CFlex, CText, CBox } from '@chakra-ui/vue';

export default Vue.extend({
    name: 'Navbar',
    components: {
        CFlex,
        CBox,
        CText,
    },
});
</script>