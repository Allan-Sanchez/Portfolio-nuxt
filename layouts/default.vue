<template>
 <div class="content-wrapper bg-background-secondary" :class="theme">
   <Logo  @toggle="toggle" :toogleTheme="theme"></Logo>    
    <nav class="side-menu hidden md:block">
        <ul class="bg-background-secondary content-wrapper">
          <li class="nav-home hover:bg-background-ternary">
            <nuxt-link to="/" class="nav-link">
              <span class="block text-xl">Home</span>
            <svg class="" width="30"  viewBox="0 0 576 512"><title>home</title><g fill="#3182ce"><path d="M280.37 148.26L96 300.11V464a16 16 0 0 0 16 16l112.06-.29a16 16 0 0 0 15.92-16V368a16 16 0 0 1 16-16h64a16 16 0 0 1 16 16v95.64a16 16 0 0 0 16 16.05L464 480a16 16 0 0 0 16-16V300L295.67 148.26a12.19 12.19 0 0 0-15.3 0zM571.6 251.47L488 182.56V44.05a12 12 0 0 0-12-12h-56a12 12 0 0 0-12 12v72.61L318.47 43a48 48 0 0 0-61 0L4.34 251.47a12 12 0 0 0-1.6 16.9l25.5 31A12 12 0 0 0 45.15 301l235.22-193.74a12.19 12.19 0 0 1 15.3 0L530.9 301a12 12 0 0 0 16.9-1.6l25.5-31a12 12 0 0 0-1.7-16.93z"></path></g></svg>
            </nuxt-link>
          </li>
          <li class="nav-about hover:bg-background-ternary">
            <nuxt-link to="about" class="nav-link">
              <span class="text-xl block">About</span>
              <svg  width="25" viewBox="0 0 448 512"><title>user</title><g fill="#3182ce"><path d="M224 256c70.7 0 128-57.3 128-128S294.7 0 224 0 96 57.3 96 128s57.3 128 128 128zm89.6 32h-16.7c-22.2 10.2-46.9 16-72.9 16s-50.6-5.8-72.9-16h-16.7C60.2 288 0 348.2 0 422.4V464c0 26.5 21.5 48 48 48h352c26.5 0 48-21.5 48-48v-41.6c0-74.2-60.2-134.4-134.4-134.4z"></path></g></svg>
            </nuxt-link>
          </li>
          <li class="nav-skill hover:bg-background-ternary">
            <nuxt-link to="skill" class="nav-link">
              <span class="text-xl block">Skill</span>
              <svg width="30"  viewBox="0 0 480.105 480.105"><title>solucion</title><g fill="#3182ce"><path d="M448.055 304.105v16c0 17.673-14.327 32-32 32-17.673 0-32-14.327-32-32v-16h-24v24a8 8 0 0 1-8 8h-24c-8.837 0-16 7.163-16 16s7.163 16 16 16h24a8 8 0 0 1 8 8v40h96c8.837 0 16-7.163 16-16v-96h-24z"></path><path d="M328.055 320.105h16v-16h-112v96c0 8.837 7.163 16 16 16h96v-32h-16c-17.673 0-32-14.327-32-32 0-17.673 14.327-32 32-32z"></path><path d="M456.055 176.105h-96v16h16c17.673 0 32 14.327 32 32s-14.327 32-32 32h-16v32h32a8 8 0 0 1 8 8v24c0 8.837 7.163 16 16 16s16-7.163 16-16v-24a8 8 0 0 1 8-8h32v-96c0-8.837-7.163-16-16-16z"></path><path d="M330.399 210.449l-26.344 26.344v-44.688h-16v60.688l-8 8-8-8v-28.688h-16v12.688l-26.344-26.344-11.312 11.312 56 56a8 8 0 0 0 11.312 0l56-56-11.312-11.312z"></path><path d="M256.055 192.105h16v16h-16z"></path><path d="M256.055 160.105h16v16h-16z"></path><path d="M288.055 160.105h16v16h-16z"></path><path d="M360.055 48.105h-24a8 8 0 0 1-8-8v-24h-96c-8.837 0-16 7.163-16 16v82.096c-.76.272-1.528.512-2.28.84l-46.816 22.608a65.195 65.195 0 0 0-18.208-16.416c31.601-15.834 44.383-54.288 28.549-85.889C161.466 3.743 123.012-9.039 91.411 6.795 59.81 22.629 47.028 61.083 62.862 92.684a64.006 64.006 0 0 0 24.377 26.261 64.15 64.15 0 0 0-33.888 41.216L21.479 260.577a120 120 0 0 0 5.144 86.104 103.783 103.783 0 0 1-1.664 89.728l-16.064 32.12a8 8 0 0 0 7.16 11.576h88a8 8 0 0 0 8-8 39.776 39.776 0 0 0-21.392-35.336l3.824-7.632a120.92 120.92 0 0 0 10.744-75.264l-5.936-32.64a7.753 7.753 0 0 1 7.616-9.128 7.751 7.751 0 0 1 7.632 6.352l10.864 59.776a164.877 164.877 0 0 1 2.648 29.424v64.448a8 8 0 0 0 8 8h88a8 8 0 0 0 8-8 40.02 40.02 0 0 0-.272-4.656 35.425 35.425 0 0 0-19.712-27.84 38.77 38.77 0 0 0-28.848-2.56l5.328-26.624a180.982 180.982 0 0 0 3.504-35.4v-71.608l-9.344-107.128 55.512-26.488c15.148-6.724 21.977-24.454 15.253-39.602a30.067 30.067 0 0 0-1.029-2.094h75.608v-40a8 8 0 0 1 8-8h24c8.837 0 16-7.163 16-16s-7.163-16-16-16z"></path></g></svg>
            </nuxt-link>
          </li>
          <li class="nav-blog hover:bg-background-ternary">
            <nuxt-link to="blog" class="nav-link">
              <span class="text-xl block">Blog</span>
              <svg  width="30" viewBox="0 0 95.938 95.938"><title>blogger-logotipo</title><g fill="#3182ce"><path d="M95.329 59.861c-.031-7.134-.053-12.289-3.562-16.824-3.975-5.134-10.106-6.004-15.076-6.152.837-3.587 1.079-7.564.692-11.863C77.277 10.705 66.624.414 51.839.006L51.626 0 29.012.018l-.243-.001c-8.795 0-15.747 2.626-20.664 7.804C5.062 11.024 1.02 16.619.592 25.666l-.018 36.48c-.044.689.025 1.385.016 2.1 0 10.379 1.661 17.85 6.848 23.371 5.183 5.521 12.847 8.32 22.776 8.32.215 0 .432-.001.649-.004h34.629c8.858-.074 16.343-2.998 21.646-8.455 5.293-5.447 8.143-13.208 8.24-22.441-.001 0-.043-3.717-.049-5.176zM30.846 19.457l19.322-.023c4.554.072 8.188 4.151 8.114 8.705-.072 4.509-3.749 7.799-8.242 7.799l-19.455.008a8.245 8.245 0 0 1-8.113-8.375c.072-4.554 3.814-8.158 8.374-8.114zm36.318 54.275H28.521a8.246 8.246 0 0 1 0-16.492h38.644a8.246 8.246 0 0 1 8.246 8.246 8.246 8.246 0 0 1-8.247 8.246z"></path></g></svg>
            </nuxt-link>
          </li>
          <li class="nav-Contact hover:bg-background-ternary">
            <nuxt-link to="contact" class="nav-link">
              <span class="text-xl block">Contact</span>
              <svg  width="30" viewBox="0 0 512 512"><title>envelope-open-text</title><g fill="#3182ce"><path d="M176 216h160c8.84 0 16-7.16 16-16v-16c0-8.84-7.16-16-16-16H176c-8.84 0-16 7.16-16 16v16c0 8.84 7.16 16 16 16zm-16 80c0 8.84 7.16 16 16 16h160c8.84 0 16-7.16 16-16v-16c0-8.84-7.16-16-16-16H176c-8.84 0-16 7.16-16 16v16zm96 121.13c-16.42 0-32.84-5.06-46.86-15.19L0 250.86V464c0 26.51 21.49 48 48 48h416c26.51 0 48-21.49 48-48V250.86L302.86 401.94c-14.02 10.12-30.44 15.19-46.86 15.19zm237.61-254.18c-8.85-6.94-17.24-13.47-29.61-22.81V96c0-26.51-21.49-48-48-48h-77.55c-3.04-2.2-5.87-4.26-9.04-6.56C312.6 29.17 279.2-.35 256 0c-23.2-.35-56.59 29.17-73.41 41.44-3.17 2.3-6 4.36-9.04 6.56H96c-26.51 0-48 21.49-48 48v44.14c-12.37 9.33-20.76 15.87-29.61 22.81A47.995 47.995 0 0 0 0 200.72v10.65l96 69.35V96h320v184.72l96-69.35v-10.65c0-14.74-6.78-28.67-18.39-37.77z"></path></g></svg>
            </nuxt-link>
          </li>
          
        </ul>
    </nav>
    <nuxt />
  </div>
</template>

<script>
import Logo from "~/components/Logo.vue";

export default {
  components: {
    Logo
  },
  data() {
    return {
      theme: 'theme-dark',
    }
  },
  methods: {
    toggle(){
      // console.log(`${this.theme} este es el resultado`);
      if(this.theme === 'theme-dark'){
        // console.log('soy igual a theme-dark');
        this.theme = 'theme-light';
      }
      else{
          // console.log('soy igual a theme-light');
         this.theme = 'theme-dark';
      } 
    }
  },
}
</script>

<style>
.side-menu{
  width: 14em;
  height: auto;
  margin: 4em auto 0;
  font-size: 1em;
  color: white;
  line-height: 2em;
  font-weight: 700;
  text-transform: uppercase;
  position: absolute;
  top: 0;
  bottom: 0;
  left: -10em;
}
.side-menu ul{
  list-style: none;
  margin: 0;
  padding: 0;
}
.side-menu ul li{
  display: block;
  /* background: #4a5568; */
  height: 6em;
  padding: 1em 1.5em;
  position: relative;
  transition: transform .5s,background-color .5s,color .5s;
}

.side-menu ul li:hover{
  /* background-color: #a0aec0; */
  transform: translateX(10rem);
}
.side-menu ul li .nav-link{
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 176px;
  height: 64px;
  color: #3182ce;
  text-decoration: none;
}
</style>
