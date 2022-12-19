<script lang='ts'>
let hover = false;
function toggleHover(){
    hover = !hover
}
</script>

<div class="InsertContainer">
 <input type="text">
 {#if hover}
 <button class='Send-Active'>Send</button>
 {:else}
 <button class='Send-InActive' on:mouseover{toggleHover()}>Send</button> 
 {/if}
</div>

<style>
.InsertContainer{
    width: 300px;
}
</style>