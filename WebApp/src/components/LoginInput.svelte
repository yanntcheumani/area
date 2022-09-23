<script lang="ts" >
    export let PlaceHolder: string = "";
    export const test: string = "";

    let handleInput:string = "";
</script>

<input class="input-login" placeholder={PlaceHolder} bind:value={handleInput}>

<style>
    :global(body) {
        background-color: pink;
    }
    .input-login {
        width: 300px;
        height: 60px;
        background: rgba(255, 255, 255, 0.22);
        border: 1px solid #FFFFFF;
        border-radius: 4px;
    }
</style>
