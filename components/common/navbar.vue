<template>
    <c-box>
        <c-flex p="2">
            <c-box>
                <c-text font-size="lg" font-weight="bold">EFFECT FREE</c-text>
            </c-box>
        </c-flex>
    </c-box>
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