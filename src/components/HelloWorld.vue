<template>
  <div class="hello">
        <Navbar></Navbar><hr/>
        <div class="container h-10">
          <div class="row h-100 justify-content-center align-items-center">
            <div class="col-md-5">
              <div class="hero-content">
                <h1 class="hero-title">
                  Share Your Blog To Others
                </h1>
                <p>
                  Lorem ipsum dolor sit amet consectetur adipisicing elit. Quos numquam tempora, iure delectus totam minus quam aperiam ratione dolores magni voluptates ut necessitatibus odio ipsum fuga, voluptas ab praesentium nihil?
                </p>
                <div class="hero-btn mt-5">
                    <button class="btn custom-btn btn-info mr-4">Search</button>
                    <a data-toggle='modal' data-target='#login' class="btn custom-btn btn-outline-secondary">Your Blogs</a>
                </div>
              </div>
            </div>
            <div class="col-md-7">
                <div class="graphic">
                    <img src="/img/svg/graphic.svg" alt="">
                </div>
            </div>
          </div>
        </div> 
    <!-- under ------------------------------ -->
    <!-- <h1>{{ msg }}</h1>
    <p>
      For a guide and recipes on how to configure / customize this project,<br>
      check out the
      <a href="https://cli.vuejs.org" target="_blank" rel="noopener">vue-cli documentation</a>.
    </p>
    <h3>Home page</h3>
    <ul>
      <li><router-link to="/login">Login</router-link></li>
      <li><router-link to="/blog">Blog</router-link></li>
    </ul> -->
    
  </div>
</template>

<script>
import Navbar from './Navbar.vue'
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  components:{
    Navbar
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.hello{ 
    width: 100%;
    height: 50px;
    text-align: left;
  }

</style>
