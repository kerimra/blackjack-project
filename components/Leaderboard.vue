<template>
     
      <v-data-table 
        :headers="headers"
        :items="players"
        :items-per-page="10"
        item-class="secondary"
        sort-by="bank"
        :sort-desc="true"
        dense
        key="name"
        mobile-breakpoint="200px"
        class="elevation-1"
      /> 
      
      
</template>

<script>
export default {

  props: {
    headers: [],
    players: []
  },
    methods:{  
  
  }
}
</script>