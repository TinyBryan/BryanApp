<template>
    <div class = "container">
        <h1>Bryan's App</h1>
        <button id = "knopje">Add Task</button>
    </div>
</template>

<script>
export default {
    name: "App"
}

</script>

<style>
#app{
    text-align: center;
    color: gold;
    margin-top: 60px;
}
.container{
    max-width: 500px;
    border: 1px solid steelblue;
    padding: 30px;
    margin: auto;
}

#knopje{
    padding: 10px 20px;
    font-size: 15px;
    background: seagreen;
    color: white;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}
</style>