<template>
    <BasicLayout>
        <template #header>
            <HeaderComp />
        </template>
        <template #footer>
            <FooterComp />
        </template>
    </BasicLayout>
</template>
<script>
import HeaderComp from "./components/header/comp.vue";
import FooterComp from "./components/footer/comp.vue";
import BasicLayout from "../components/Layouts/basic.vue";

export default {
    name: "user-layout",
    components: {
        BasicLayout,
        HeaderComp,
        FooterComp,
    },
};
</script>
