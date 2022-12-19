<script lang='ts'>
let hover = false;
function toggleHover(){
    hover = !hover
}
</script>

<div class="InsertContainer">
 <input type="text">
 <button class="{hover ? hover:hover-false}">Send</button>
</div>

<style>
.InsertContainer{
    width: 300px;
}
</style>