<template>
    <div class="container-fluid">
        <div class="row">
            <div class="col-12 ">
                <h1>Vue Router Demo App</h1>
            </div>
        </div>
        <div class="row">
            <div class="col-3">
                <left-menu></left-menu>
            </div>
            <div class="col-9">
                <router-view></router-view>
            </div>
        </div>
    </div>
</template>
<script>
    import LeftMenu from './LeftMenu';

    export default {
        components: { LeftMenu },
    }
</script>