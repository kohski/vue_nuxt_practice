<template>
  <div id="app">
    <HelloWorld title="JSX?">
    </HelloWorld>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'


export default {
  name: 'app',
  components: {
    HelloWorld
  },
  data: function(){
    return {
      slotobjs: [
        {name:'Taro', mail:'taro@yamada'},
        {name:'Hanako', mail:'hanako@flower'},
        {name:'Sachiko', mail:'sachiko@happy'},
      ],
    };
  }
}
</script>