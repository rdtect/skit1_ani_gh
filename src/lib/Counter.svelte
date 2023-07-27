<script>
    let count = 0;
</script>

<h1>Counter Example</h1>
<button on:click={()=>count ++}>+</button>
<button on:click={()=>count --}>-</button>
<h1>{count}</h1>

<style>

    /* h1{
        color: red;
    } */
/* 
    button{
        background-color: blue;
        color: white;
        border: none;
        padding: 10px;
        margin: 10px;
        border-radius: 5px;
        cursor: pointer;
        font-size: 20px;
        width: 100px;

    } */

    /* button:hover{
        background-color: green;
    } */
</style>