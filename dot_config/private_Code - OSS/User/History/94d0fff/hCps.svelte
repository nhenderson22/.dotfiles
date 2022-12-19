<script lang='ts'>
let hover = false;
</script>

<div class="InsertContainer">
 <input type="text">
 {#if hover}
 <button class='Send' on:mouseover={hover=true}>Send</button>
 {/if}
 
</div>

<style>
.InsertContainer{
    width: 300px;
}
</style>