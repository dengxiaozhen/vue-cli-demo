<template>
    <div>
        <ul class="nav">
            <router-link :to="{name:'About'}" exact tag="li">
                <a>study</a>
            </router-link>
            <router-link :to="{name:'Work'}" tag="li">
                <a>work</a>
            </router-link>
            <router-link :to="{name:'Hobby'}" tag="li">
                <a>hobby</a>
            </router-link>
        </ul>

        <router-view></router-view>
    </div>
</template>

<script>
export default {}
</script>

<style></style>