<template>
  <div id="app">
    <Amega/>
    <Header/>
    <Home/>
    <Map/>
    <Statistics/>
    <Review/>
    <Traffic/>
    <search/>
    <Notification/>
    <Burha/>
    <Special/>
    <Real/>
    <Lecture/>
    <Source/>
    <Behaviour/>
    <Conversation/>
    <Recommendation/>
    <Blank/>
    <Dash/>

    
  
  </div>
</template>

<script>
import Amega from './components/Amega.vue'
import Header from './components/Header.vue'
import Home from './components/Home.vue'
import Map from './components/Map.vue'
import Statistics from './components/Statistics.vue'
import Review from './components/Review.vue'
import Traffic from './components/Traffic.vue'
import Search from './components/Search.vue'
import Notification from './components/Notification.vue'
import Burha from './components/Burha.vue'
import Special from './components/Special.vue'
import Real from './components/Real.vue'
import Lecture from './components/Lecture.vue'
import Source from './components/Source.vue'
import Behaviour from './components/Behaviour.vue'
import Conversation from './components/Conversation.vue'
import Recommendation from './components/Recommendation.vue'
import Blank from './components/Blank.vue'
import Dash from './components/Dash.vue'

export default {
  name: 'app',
  components: {
     Amega,
     Header,
     Home,
     Map,
     Statistics,
     Review,
     Traffic,
     Search,
     Notification,
     Burha,
     Special,
     Real,
     Lecture,
     Source,
     Behaviour,
     Conversation,
     Recommendation,
     Blank,
     Dash,

  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  background:#3c3a53;
  height:103vh;
  width:100wv;
}

</style>
