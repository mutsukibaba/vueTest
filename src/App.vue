<template>
  <div id="app">
    <div id="nav">
        <!-- `router.js` で定義したルーティングルールとの紐付けを行っている -->
      <router-link to="/">Home    </router-link>
      <router-link to="/routing">Rounting Test</router-link>
    </div>
    <router-view />
  </div>
</template>

// ▼ ここから削除 ( ルーティングによって不要となるため )
//<script>

<style lang="scss">

</style>