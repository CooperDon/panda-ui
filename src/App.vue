<template>
<div>导航栏 | <router-link to="/">Frank</router-link>
    | <router-link to="/xxx">Frank2</router-link>
</div>
<hr />
<router-view></router-view>
</template>

<script>
import Frank from './components/Frank.vue'

export default {
    name: 'App',
}
</script>
