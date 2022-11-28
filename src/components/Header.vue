<template>
  <div id="head">
    <img src="../assets/dc-logo.png" alt="errore">
    <nav>
        <ul>
            <li><a href="#">CHARACTERS</a></li>
            <li><a href="#">COMICS</a></li>
            <li><a href="#">MOVIES</a></li>
            <li><a href="#">TV</a></li>
            <li><a href="#">GAMES</a></li>
            <li><a href="#">COLLECTIBLES</a></li>
            <li><a href="#">VIDEOS</a></li>
            <li><a href="#">FANS</a></li>
            <li><a href="#">NEWS</a></li>
            <li><a href="#">SHOP</a></li>

        </ul>
    </nav>
  </div>
</template>

<!-- Script -->
<script>
export default {
  name: 'HeaderNav'
}
</script>

<!-- CSS -->
<style scoped lang="scss">
#head {
  padding: 25px 250px 10px 250px;
  display: flex;
  justify-content: space-between;
}

nav{
  display: inline-block;
}

ul{
  display: inline-flex;
  list-style-type: none;
  gap: 30px;
  margin-top: 30px;
}

li:hover{
  a{
    color: #0282f9;
  }
}

a{
    color: #4a4d52;
    font-weight: bold;
    text-decoration: none;
}
</style>