<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Hello myapp"/>
    <Table title="人员信息表"/>
  </div>
</template>

<script lang="ts">
import { Options, Vue } from 'vue-class-component';
import HelloWorld from '@/components/HelloWorld.vue'; // @ is an alias to /src
import Table from '@/components/Table.vue';
@Options({
  components: {
    HelloWorld,
    Table
  },
})
export default class Home extends Vue {}
</script>
