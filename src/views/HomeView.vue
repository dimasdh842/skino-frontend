<template>
  <div class="home">

      <img src="../assets/logo-gede.png" alt="logo-big" class="logo-big">
    <input type="text" name="name" id="name" class="input-text" placeholder="Nama Anak Anda">
    <router-link to="content" class="link-start">Mulai</router-link>

    <div class="mt-max">
       <p class="text-footer">Mohammad Firmansyah 20081010022 <br> <b>  &copy; copyright 2022 </b> </p>
    </div> 
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'HomeView',
  components: {
  }
}
</script>

<style scoped>
  .home{
    width: 100%;
    min-height:100vh;
    padding-bottom: 10px;
    background: url("../assets/bg-phone.png");
  }

  .input-text{
    width: 233px;
    height: 45px;
    margin-bottom:50px ;
    background: #FFFFFF;
    border-radius: 8px;
    border: 0;
    text-align: center;
  }

  .input-text::placeholder{
    font-family: 'Poppins';
    font-style: normal;
    font-weight: 400;
    font-size: 15px;
    line-height: 22px;
    color: rgba(0, 0, 0, 0.54);
  }

  .link-start{
    width: 106px;
    height: 41px;
    padding: 10px 15px;
    color: white;
    background: #EB5353;
    border-radius: 8px;
    font-family: Poppins;
    font-size: 22px;
    font-weight: 700;
    line-height: 33px;
    letter-spacing: 0em;

  }

  .logo-big{
    margin: 190px 0 36px;
  }

  .mt-max{
         margin-top: 150px;
        font-size: 13px;
        color: white;
        line-height: 22px;
        margin-bottom:10px;
  }
</style>
