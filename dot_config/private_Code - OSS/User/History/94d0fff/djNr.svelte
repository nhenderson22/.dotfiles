<script lang='ts'>
let hover = false;
</script>

<div class="InsertContainer">
 <input type="text">
 {#if hover}
    
 {/if}
 <button class='Send' on:mouseover={}>Send</button>
</div>

<style>
.InsertContainer{
    width: 300px;
}
</style>