<template>
    <Submenu name="2">
        <template slot="title">
            <Icon type="pie-graph"></Icon>
            综合评估
        </template>
        <MenuItem name="管理评估">
            <router-link to="/evaluatmanage">管理评估</router-link>
        </MenuItem>
        <MenuItem name="师资评估">
            <router-link to="/evaluatteachers">师资评估</router-link>
        </MenuItem>
        <MenuItem name="教学评估">
            <router-link to="/evaluatteach">教学评估</router-link>
        </MenuItem>
    </Submenu>
</template>

<script>
    export default {}
</script>

<style scoped>

</style>