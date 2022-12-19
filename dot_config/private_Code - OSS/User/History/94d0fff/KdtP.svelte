<script lang='ts'>
let hover = false;
function toggleHover(){
    hover = !hover
}
</script>

<div class="InsertContainer">
 <input type="text">
 <button class="send-button">Send</button>
</div>

<style>
.InsertContainer{
    width: 300px;
}
.send-button {
    height: 30px;
}
.send-button:hover{
    opacity: .8;
}
</style>