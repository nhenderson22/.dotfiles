<script>
import { messages } from "../Stores/MessageStore";
</script>

<div class="message-container">
    {#each $messages as message}
    <div class="message-{message.position}">{message.content}</div>
    {/each}
</div>


<style>
.message-right{
 background-color: black;
 color: white;
}
</style>