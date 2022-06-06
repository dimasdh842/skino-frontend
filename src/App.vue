/* eslint-disable */
<template>
<div  class="container">
       <router-view>
         </router-view>
    </div>
</template>
<script>

export default {
  data(){
    return{
      activeID:1,
      hasil:0
    }
  },
  methods:{
    render() {

      document.querySelectorAll(".card-container").forEach(e => {
            if (e.getAttribute("id") == this.activeID) {
                        e.classList.remove("hide");
                        e.classList.add("show");
                    }
                    (e.getAttribute("id") != this.activeID) ? e.classList.add("hide") : "";
            });
            },
            kanan(){
              if (this.activeID < 20) {
                     this.activeID++
                 }
                   if (this.activeID == 20) {

                     // merubah menjadi finish
                     if (this.hasil == 0) {
                         this.activeID = 100
                         console.log(this.hasil);
                     } else {
                         this.activeID = 99
                     }
                 }
                  this.render()
            },
            kiri() {
              if (this.activeID != 1 && !(this.activeID > 20)) {
                     this.activeID--
                  }
                  this.render()
            },
            next() {
                        this.activeID++
                        this.hasil = 1
                        if (this.activeID == 20) {

                            // merubah menjadi finish
                            if (this.hasil == 0) {
                                this.activeID = 100
                                console.log(this.hasil);
                            } else {
                                this.activeID = 99
                            }
                        }

                        this.render()
            }
  }

  }

  // 



            
  // 
</script>

<style>

@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800&display=swap');

body {
       font-family: 'Poppins', sans-serif;
        padding: 0;
        margin: 0;
        background: lightgrey;
        width: 100vw;
        height: 100vh;
        overflow: hidden;
        background: url('./assets/bg.png');
        }

        .img{
            margin:41px 0;
        }

        .container{
            width: 320px;
            height: 100vh;
            margin: 0 auto;
            background: white;
            overflow-y:scroll;
            overflow-x:hidden ;
            text-align: center;
            position: relative;
        }

        /* .container::-webkit-scrollbar {
            display: none;
        }

            /* Hide scrollbar for IE, Edge and Firefox */
        /* .container { */
            /* -ms-overflow-style: none;
            scrollbar-width: none;  
            }  */

        .title{
            font-size: 20px;
            margin-bottom:36px;
        }

        .img{
            width: 200px;
            height: 200px;
        }

        .ya,.tidak{
            width: 171px;
            height: 47px;
            border: 0;
            font-weight: 700;
            background: #F8DC37;
            display: block;
            margin: 10px auto;
            }
        
        .tidak{
            background: #EB5353;

        }

        .card-container{
            width: 100%;
            text-align: center;
        }

        .header-cta{
            padding:15px;
            border-radius: 50%;
            background: #EB5353;
            border-radius: 46px;
            border: 0;
            text-align: center;
            display: block;
            margin: 100px auto 0;
        }
                .header-cta-finish{
            padding:0px 20px;
            background: #EB5353;
            border: 0;
            text-align: center;
            display: block;
            margin: 10px auto 20px;
            color: white;
        }
                .header-cta-2{
            padding:15px;
            border-radius: 50%;
            background: #EB5353;
            border-radius: 46px;
            border: 0;
            display: inline-block;
            text-align: center;
            margin: 100px auto 0;
        }
                .header-cta-3{
            padding: 15px;
            border-radius: 50%;
            background: #EB5353;
            border-radius: 46px;
            border: 0;
            display: inline-block;
            text-align: center;
            margin: 100px auto 171px;
            font-size: 20px;
            padding: 10px 15px;
            color: white;
            font-weight: 700;
        }

        .title{
            font-size: 16px;
        }   

        .show {
                display: block;
        }
            
        .hide {
                display: none;
        }

        nav{
          position: absolute;
            bottom: 0;
            left: 0;
            right: 0;
        }

        ul{
            padding: 0;
            background: #6FC4A1;
            margin: 0;
        }

        li{
            list-style: none;
            padding:10px;
        }

        a{
            text-decoration: none;
            margin: 0 30px;
        }
        .m-s{
            margin-bottom: 10px;
            margin-top: 100px;
            margin-right: 30px;
            margin-left: 30px;
        }

        @media only screen and (max-height:553px) {
          nav{
            position: relative;
          }
        }

</style>
