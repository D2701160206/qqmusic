<template>
  <div>
    <Header></Header>
    <Tab></Tab>
    <router-view></router-view>
    <player></player>
  </div>
</template>

<script>
import Header from "./components/m-header/header";
import Tab from "./components/tab/tab";
import Player from "./components/player/player";

export default {
  components: {
    Header,
    Tab,
    Player
  }
}
</script>