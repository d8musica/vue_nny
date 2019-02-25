 <template>
  <div>
    <MyHeader />
    <Login />
    <nuxt />
  </div>
</template>

<script>
  import MyHeader from '~/components/MyHeader.vue'
  import Login from '~/components/Login.vue'
  export default {
    components: {
      MyHeader,Login
    }
  };



</script>
