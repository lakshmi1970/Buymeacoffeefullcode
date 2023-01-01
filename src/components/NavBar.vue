<template>
  <div>
    <div>
      <nav
        class="
          container-fluid
          px-4
          xl:px-14
          py-8
          mx-auto
          md:flex md:justify-between md:items-center
        "
      >
        <div class="flex items-center justify-between">
          <router-link
            to="/"
            class="
              text-xl
              font-bold
              text-gray-800
              md:text-2xl
              hover:text-blue-400
            "
            ><img src="../assets/images/Logo.svg" alt="Logo" class="logo" />
          </router-link>
          <div @click="showMenu = !showMenu" class="flex md:hidden">
            <button
              type="button"
              class="
                text-gray-800
                hover:text-gray-400
                focus:outline-none focus:text-gray-400
              "
            >
              <svg viewBox="0 0 24 24" class="w-6 h-6 fill-current">
                <path
                  fill-rule="evenodd"
                  d="M4 5h16a1 1 0 0 1 0 2H4a1 1 0 1 1 0-2zm0 6h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2zm0 6h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2z"
                ></path>
              </svg>
            </button>
          </div>
        </div>

        <ul
          :class="showMenu ? 'flex' : 'hidden'"
          class="
            flex-col
            mt-8
            space-y-4
            md:flex
            md:space-y-0
            md:flex-row
            md:items-center
            md:space-x-10
            md:mt-0
            text-center"
        >
          <li class="text-sm text-gray-800 hover:text-blue-400">
           <a href="#">Why Open Enterprise</a>
          </li>
          <li class="text-sm text-gray-800 hover:text-blue-400">
            <a href="#">Features</a>
          </li>
          <li class="text-sm text-gray-800 hover:text-blue-400">
            <a href="#">Contribute</a>
          </li>
          <li class="text-sm text-gray-800 hover:text-blue-400">
            <a href="#" class="early-btn font-bold">Request early access</a>
          </li>
        </ul>
      </nav>
    </div>
  </div>
</template>
<script>
export default {
  data() {
    return {
      showMenu: false,
    };
  },
};
</script>
<style scoped>
 ul li{
    font-weight: 500;
    font-size: 20px;
    line-height: 24px;
    letter-spacing: -0.02em;
 }
 .early-btn {
    color: #71A894;
 }
@media (max-width:1199px){
    ul li {
        font-size:14px;
    }
    .logo {
        width: 200px;
    }        
}
</style>