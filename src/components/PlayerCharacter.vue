<template>
    <div class="panel panel-default">
        
        <div class="panel-heading">
            <PlayerCharacterName/>
        </div>
        <div class="panel-body">
          
            <PlayerCharacterHealthbar/>
        </div>
    </div>
</template>
  
<script>
  import PlayerCharacterName from './PlayerCharacterName.vue'
  import PlayerCharacterHealthbar from './PlayerCharacterHealthbar.vue'
 export default {
   compoents: {
     PlayerCharacterName,
     PlayerCharacterHealthbar
   }
 }
</script>

<style>
  
</style>