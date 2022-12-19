<script lang='ts'>
let hover = false;
</script>

<div class="InsertContainer">
 <input type="text">
 {#if hover}
 <button class='Send-Active' on:mouseover={hover=true}>Send</button>
 {#else}
 {/else}
</div>

<style>
.InsertContainer{
    width: 300px;
}
</style>