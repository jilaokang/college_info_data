<template>
    <Submenu name="1">
        <template slot="title">
            <Icon type="home"></Icon>
            整体概况
        </template>
        <MenuItem name="校园概况">
            <router-link to="/surveysituation">
                校园概况
            </router-link>
        </MenuItem>
        <MenuItem name="院系情况">
            <router-link to="/surveyfaculty">
                院系情况
            </router-link>
        </MenuItem>
        <MenuItem name="班级情况">
            <router-link to="/surveyclassblock">
                班级情况
            </router-link>
        </MenuItem>
        <MenuItem name="教学情况">
            <router-link to="/surveyteach">
                教学情况
            </router-link>
        </MenuItem>
        <MenuItem name="学生情况">
            <router-link to="/surveystudent">
                学生情况
            </router-link>
        </MenuItem>
    </Submenu>
</template>

<script>
    export default {
        methods:{
            
        }
    }
</script>

<style scoped>

</style>