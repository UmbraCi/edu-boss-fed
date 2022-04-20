<template>
    <div id="app">
        <h1>App</h1>
        <el-button type="primary">主要按钮</el-button>
        <p class="text">hello world</p>
        <!-- 根级路由出⼝ -->
        <router-view />
    </div>
</template>

<style lang="scss" scoped>
.text {
    color: $success-color;
}
</style>
