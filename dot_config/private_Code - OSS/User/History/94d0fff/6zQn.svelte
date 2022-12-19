<script lang='ts'>
import {messages} from '../Stores/MessageStore'
let content;

function updateMessages(){
    const newMessage={
        position: 'right',
        content: content
    }
    messages.update(messages => [...messages, newMessage])
}
</script>

<div class="InsertContainer">
 <input type="text" bind:value={content}>
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