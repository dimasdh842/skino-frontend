<template>
  <div class="content">
    <img src="../assets/logo-bg-green.png" alt="logo green">
        <div class="card-container"  id="1">

            <img src="../assets/img-1.jpeg" alt="img1" class="img">
            <h2 class="title">1. Apakah Anak anda memiliki gejala Gelembung air sperti diatas ? </h2>
            <button class="ya" @click=next($event)>Ya</button>
            <button class="tidak" @click=next($event)>Tidak</button>

           
            <!-- <button class="header-cta center-right"><img src="./panah.png" alt="panah" width="25px"></button> -->
            
        </div>
        <div class="card-container hide" id="2">

            <img src="../assets/img-2.jpeg" alt="img1" class="img">
            <h2 class="title">2. Apakah Anak anda memiliki demam ? </h2>
            <button class="ya" @click=next($event)>Ya</button>
            <button class="tidak" @click=next($event)>Tidak</button>
            <!-- <button class="header-cta center-right"><img src="./panah.png" alt="panah" width="25px"></button> -->
        </div>
        <div class="card-container hide" id="3">
            
            <img src="../assets/img-3.jpeg" alt="img1" class="img">
            <h2 class="title">3. Apakah Anak anda mengalami nyeri kepala ? </h2>
            <button class="ya" @click=next($event)>Ya</button>
            <button class="tidak" @click=next($event)>Tidak</button>
            <!-- <button class="header-cta center-right"><img src="./panah.png" alt="panah" width="25px"></button> -->
            
        </div>
        <div class="card-container hide" id="4">

            <img src="../assets/img-4.jpeg" alt="img1" class="img">
            <h2 class="title">3. Apakah Anak anda mengalami gatal-gatal pada kulit ? </h2>
            <button class="ya" @click=next($event)>Ya</button>
            <button class="tidak" @click=next($event)>Tidak</button>
            <!-- <button class="header-cta center-right"><img src="./panah.png" alt="panah" width="25px"></button> -->
        </div>
        <div class="card-container hide" id="5">

            <img src="../assets/img-5.jpeg" alt="img1" class="img">
            <h2 class="title">4.Apakah Anak anda memiliki gejala Lesi seluruh tubuh seperti diatas ? </h2>
            <button class="ya" @click=next($event)>Ya</button>
            <button class="tidak" @click=next($event)>Tidak</button>
            <!-- <button class="header-cta center-right"><img src="./panah.png" alt="panah" width="25px"></button> -->
        </div>
        <div class="card-container hide" id="6">

            <img src="../assets/img-6.jpeg" alt="img1" class="img">
            <h2 class="title">5.Apakah Anak anda memiliki gejala mata merah seperti diatas ? </h2>
            <button class="ya" @click=next($event)>Ya</button>
            <button class="tidak" @click=next($event)>Tidak</button>
            <!-- <button class="header-cta center-right"><img src="./panah.png" alt="panah" width="25px"></button> -->
        </div>
        <div class="card-container hide" id="7">

            <img src="../assets/img-7.jpeg" alt="img1" class="img">
            <h2 class="title">6.Apakah Anak anda memiliki gejala batuk ? </h2>
            <button class="ya" @click=next($event)>Ya</button>
            <button class="tidak" @click=next($event)>Tidak</button>
            <!-- <button class="header-cta center-right"><img src="./panah.png" alt="panah" width="25px"></button> -->
        </div>
        <div class="card-container hide" id="8">

            <img src="../assets/img-8.jpeg" alt="img1" class="img">
            <h2 class="title">7.Apakah Anak anda memiliki gejala pilek ? </h2>
            <button class="ya" @click=next($event)>Ya</button>
            <button class="tidak" @click=next($event)>Tidak</button>
            <!-- <button class="header-cta center-right"><img src="./panah.png" alt="panah" width="25px"></button> -->
        </div>
        <div class="card-container hide" id="9">

            <img src="../assets/img-9.jpeg" alt="img1" class="img">
            <h2 class="title">8.Apakah Anak anda memiliki gejala kulit meradang seperti diatas ? </h2>
            <button class="ya" @click=next($event)>Ya</button>
            <button class="tidak" @click=next($event)>Tidak</button>
            <!-- <button class="header-cta center-right"><img src="./panah.png" alt="panah" width="25px"></button> -->
        </div>
        <div class="card-container hide" id="10">

            <img src="../assets/img-10.jpeg" alt="img1" class="img">
            <h2 class="title">9.Apakah Anak anda memiliki gejala nyeri tekan pada bagian tertentu ? </h2>
            <button class="ya" @click=next($event)>Ya</button>
            <button class="tidak" @click=next($event)>Tidak</button>
            <!-- <button class="header-cta center-right"><img src="./panah.png" alt="panah" width="25px"></button> -->
        </div>
        <div class="card-container hide" id="11">

            <img src="../assets/img-11.jpeg" alt="img1" class="img">
            <h2 class="title">10.Apakah Anak anda memiliki gejala kulit perih? </h2>
            <button class="ya" @click=next($event)>Ya</button>
            <button class="tidak" @click=next($event)>Tidak</button>
            <!-- <button class="header-cta center-right"><img src="./panah.png" alt="panah" width="25px"></button> -->
        </div>
        <div class="card-container hide" id="12">

            <img src="../assets/img-12.jpeg" alt="img1" class="img">
            <h2 class="title">11.Apakah Anak anda memiliki gejala kulit bersisik seperti diatas ? </h2>
            <button class="ya" @click=next($event)>Ya</button>
            <button class="tidak" @click=next($event)>Tidak</button>
            <!-- <button class="header-cta center-right"><img src="./panah.png" alt="panah" width="25px"></button> -->
        </div>
        <div class="card-container hide" id="13">

            <img src="../assets/img-13.jpeg" alt="img1" class="img">
            <h2 class="title" >12.Apakah Anak anda memiliki gejala kulit melepuh? </h2>
            <button class="ya" @click=next($event)>Ya</button>
            <button class="tidak" @click=next($event)>Tidak</button>
            <!-- <button class="header-cta center-right"><img src="./panah.png" alt="panah" width="25px"></button> -->
        </div>
        <div class="card-container hide" id="14">

            <img src="../assets/img-14.jpeg" alt="img1" class="img">
            <h2 class="title" >13.Apakah Anak anda memiliki gejala bengkak ? </h2>
            <button class="ya" @click=next($event)>Ya</button>
            <button class="tidak" @click=next($event)>Tidak</button>
            <!-- <button class="header-cta center-right"><img src="./panah.png" alt="panah" width="25px"></button> -->
        </div>
        <div class="card-container hide" id="15">

            <img src="../assets/img-15.jpeg" alt="img1" class="img">
            <h2 class="title">14.Apakah Anak anda memiliki gejala neradabg air seperti diatas ? </h2>
            <button class="ya" @click=next($event)>Ya</button>
            <button class="tidak" @click=next($event)>Tidak</button>
            <!-- <button class="header-cta center-right"><img src="./panah.png" alt="panah" width="25px"></button> -->
        </div>
        <div class="card-container hide" id="16">

            <img src="../assets/img-16.jpeg" alt="img1" class="img">
            <h2 class="title">15.Apakah Anak anda memiliki gejala Lesi pada bagian tertentu seperti diatas ? </h2>
            <button class="ya" @click=next($event)>Ya</button>
            <button class="tidak" @click=next($event)>Tidak</button>
            <!-- <button class="header-cta center-right"><img src="./panah.png" alt="panah" width="25px"></button> -->
        </div>
        <div class="card-container hide" id="17">

            <img src="../assets/img-17.jpeg" alt="img1" class="img">
            <h2 class="title">16.Apakah Anak anda memiliki gejala Gelembung air di area tertentu seperti diatas ? </h2>
            <button class="ya" @click=next($event)>Ya</button>
            <button class="tidak" @click=next($event)>Tidak</button>
            <!-- <button class="header-cta center-right"><img src="./panah.png" alt="panah" width="25px"></button> -->
        </div>
        <div class="card-container hide" id="18">

            <img src="../assets/img-18.jpeg" alt="img1" class="img">
            <h2 class="title">17.Apakah Anak anda memiliki gejala Gelembung air sperti diatas ? </h2>
            <button class="ya" @click=next($event)>Ya</button>
            <button class="tidak" @click=next($event)>Tidak</button>
            <!-- <button class="header-cta center-right"><img src="./panah.png" alt="panah" width="25px"></button> -->
        </div>
        <div class="card-container hide" id="19">

            <img src="../assets/img-19.jpeg" alt="img1" class="img">
            <h2 class="title">18.Apakah Anak anda memiliki gejala Benjolan berisi nanah seperti diatas ? </h2>
            <button class="ya" @click=next($event)>Ya</button>
            <button class="tidak" @click=next($event)>Tidak</button>
            <!-- <button class="header-cta"><img src="./panah.png" alt="panah" width="25px"></button> -->
            <!-- <button class="header-cta-finish">
                <h2>Finish</h2>
            </button> -->
        </div>
        
        <div class="card-container hide" id="99">

            <h2 class="title m-s" id="hasil"></h2>
            <button class="header-cta-3" @click=postData()>Finish</button>
        </div>
        <nav>
            <ul>
                <li>
                    <a href="#" class="kiri" @click="kiri()">
                        <img src="../assets/kiri.png" alt="home"/>
                    </a>
                    <router-link to="/">
                        <img src="../assets/home.png" alt="home"/>
                    </router-link>
                    <a href="#" class="kanan" @click="kanan()">
                        <img src="../assets/kanan.png" alt="home"/>
                    </a>
                </li>
            </ul>
        </nav>
  </div>
</template>
<script>
export default {
  name:"contentView",
  data(){
    return{
      activeID:1,
      hasil:"default",
      array:[]
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
            next(e) {
              console.log(e.target.textContent)
              if(e.target.textContent == "Ya") {
                this.array.push(1)
                console.log(this.array)
              } else if(e.target.textContent == "Tidak") {
                this.array.push(0)
                console.log(this.array)
              }
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
            },
            getData() {
              fetch('http://localhost:5001/api')
                .then(response => response.json())
                .then(data => {
                  let arr = data.result.result.split('"')
                  console.log(parseFloat(arr[1]))
                  let nilai = parseFloat(arr[1])
                  if (nilai > 0.56 ) {
                    document.getElementById("hasil").textContent =  "Anak Anda memiliki penyakit kulit" 
                  } else {
                    document.getElementById("hasil").textContent =  "Anak anda tidak memiliki penyakit kulit" 
                  }
                });
            },
            postData(){
              
              // let formData = new FormData();
              // formData.append('data', [...this.array]);
              // console.log(formData)  
              let data = {"data":this.array}
              
              fetch('http://localhost:5001/api',{
                method: "POST",
                mode:"cors",
                headers:{
                  'Content-Type': 'application/json',
                  'Accept': 'application/json'
                },
                body:JSON.stringify(data),

              })
                .then(response => response.json())
                .then(data => {
                  console.log(data)
                  this.getData()

                  });

            }
  }

  
}
</script>
