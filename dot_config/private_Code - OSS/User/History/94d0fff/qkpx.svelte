<script lang='ts'>
let hover = false;
function toggleHover(){
    hover = !hover
}
</script>

<div class="InsertContainer">
 <input type="text">
 <button class="{hover ? "hover":"normal"}" on:mouseover={() => !hover}>Send</button>
</div>

<style>
.InsertContainer{
    width: 300px;
}
</style>