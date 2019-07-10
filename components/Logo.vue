<template>
  <div class="nav-two">
    <div class="toggle-color">
      <ul class="flex justify-center items-center">
        <li class="mx-4">
          <a href="/">
            <svg class="" width="30"  viewBox="0 0 576 512"><title>home</title><g fill="#111"><path d="M280.37 148.26L96 300.11V464a16 16 0 0 0 16 16l112.06-.29a16 16 0 0 0 15.92-16V368a16 16 0 0 1 16-16h64a16 16 0 0 1 16 16v95.64a16 16 0 0 0 16 16.05L464 480a16 16 0 0 0 16-16V300L295.67 148.26a12.19 12.19 0 0 0-15.3 0zM571.6 251.47L488 182.56V44.05a12 12 0 0 0-12-12h-56a12 12 0 0 0-12 12v72.61L318.47 43a48 48 0 0 0-61 0L4.34 251.47a12 12 0 0 0-1.6 16.9l25.5 31A12 12 0 0 0 45.15 301l235.22-193.74a12.19 12.19 0 0 1 15.3 0L530.9 301a12 12 0 0 0 16.9-1.6l25.5-31a12 12 0 0 0-1.7-16.93z"></path></g></svg>
          </a>
        </li>

        <li class="mx-4">
          <button @click="$emit('toggle')">
              <svg v-if="toggle_dark"  width="30" viewBox="0 0 512 512"><title>moon</title><g fill="#111111"><path d="M283.211 512c78.962 0 151.079-35.925 198.857-94.792 7.068-8.708-.639-21.43-11.562-19.35-124.203 23.654-238.262-71.576-238.262-196.954 0-72.222 38.662-138.635 101.498-174.394 9.686-5.512 7.25-20.197-3.756-22.23A258.156 258.156 0 0 0 283.211 0c-141.309 0-256 114.511-256 256 0 141.309 114.511 256 256 256z"></path></g></svg>
            
            <svg v-else  width="30" viewBox="0 0 48 48"><title>ic_wb_sunny_48px</title>
                <g fill="#111111">
                    <path d="M13.51 9.69L9.93 6.1 7.1 8.93l3.59 3.59 2.82-2.83zM8 21H2v4h6v-4zM26 1.1h-4V7h4V1.1zm14.9 7.83L38.07 6.1l-3.59 3.59 2.83 2.83 3.59-3.59zm-6.41 27.38l3.59 3.59 2.83-2.83-3.59-3.59-2.83 2.83zM40 21v4h6v-4h-6zM24 11c-6.63 0-12 5.37-12 12s5.37 12 12 12 12-5.37 12-12-5.37-12-12-12zm-2 33.9h4V39h-4v5.9zM7.1 37.07l2.83 2.83 3.59-3.59-2.83-2.83-3.59 3.59z"></path>
                </g>
            </svg>
          </button>
        </li>
      </ul>
    </div>
    <!-- <div class="img w-16 absolute right-0 top-0 mr-10 mt-2">
        <img src="../static/img/logo.png" alt />
    </div> -->
  </div>
</template>

<script>
export default {
  data() {
    return {
      toggle_dark: true,
    }
  },
  methods: {
   
  },
}
</script>

<style>
.toggle-color{
  position: absolute;
  top: 0;
  right: 0;
  margin: 1.5em;
}

</style>
