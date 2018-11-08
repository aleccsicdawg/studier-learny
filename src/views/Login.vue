

<template>


  <b-container>
    <b-row>
      <b-col sm="12">
        <button variant="primary" v-on:click="toogle" v-model ="registerOrLogin">LogIn / Register</button>
        <b-card title="Email" v-if="registerOrLogin" key="username">
          <b-input-group>
            <b-input class="mb-2 mr-sm-2 mb-sm-0"  placeholder="Pass" />
            <b-input class="mb-2 mr-sm-2 mb-sm-0" placeholder="Email" />
          </b-input-group>
        </b-card>
        <b-card title="Email" v-else key="email">
          <b-input-group>
            <b-input class="mb-2 mr-sm-2 mb-sm-0" placeholder="Login" />
            <b-input class="mb-2 mr-sm-2 mb-sm-0" placeholder="Email" />
          </b-input-group>
        </b-card>
      </b-col>
    </b-row>
  </b-container>
</template>




<script>
  export default {
    data() {
      return {
        registerOrLogin: "",
      }
    },
    methods: {
      toogle: function () {
        this.registerOrLogin = !this.registerOrLogin;
      }
    }
  
  }

</script>

<style scoped>


</style>

