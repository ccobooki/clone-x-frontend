<template>
  <div class = "container">
    <LoginPage/>
  </div>
</template>

<script>
import LoginPage from "./views/LoginPage.vue" ;
export default {
  name: 'App',
  components: {LoginPage},
};
</script>


<style>
body {
  background-color: black;
  color: white;

}

.container {
  height: 100vh;
  display: flex;
  flex-direction: column; /* 수직 정렬 */
  justify-content: center; /* 수직 중앙 정렬 */
  align-items: center; /* 수평 중앙 정렬 */
}
</style>

