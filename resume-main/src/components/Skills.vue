<template>
    <ul>
        <li>
            <strong>PMP证书：</strong>项目管理认证
        </li>
        <li>
            <strong>后端：</strong>{{skills.libraries.join(', ')}}
        </li>
        <li>
            <strong>前端：</strong>{{skills.tools.join(', ')}}
        </li>
        <li>
            <strong>设计：</strong>{{skills.tests.join(', ')}}
        </li>
    </ul>
</template>

<script>
    export default {
        name: "Skills",
        props: {
            skills: {
                type: Object,
                required: true
            }
        }
    }
</script>

<style scoped lang="scss">

</style>