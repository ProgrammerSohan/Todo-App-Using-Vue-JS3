<template>
    <div class="wrapper">
       <h1> Todo By Sohan!!</h1>
       <h2 class="header">Todo List</h2>
       <div class="inputDiv">
            <input ref="myInput" type="text" class="todoInput" v-model="model" placeholder="Enter a new todo!" />
       <button class="addTodoBtn">Add Todo </button>

       </div>
    </div>
</template>
<script>
export default{
    name:"Todo",

}

</script>
<style scoped>
.wrapper {
    width: 100%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;

}
.header {
    color: orange;
}
.inputDiv{
    width: 90%;
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 0.5rem;
}
.todoInput{
    width: 70%;
    padding: 5px;
    border: none;
    border-radius: 10px;

}
.addTodoBtn{
    border: none;
    padding: 5px;
    border-radius: 5px;
    background-color: green;
    color: white;
    cursor: pointer;

}
.addTodoBtn:hover{
    background-color: navy;
    color:rgb(11, 204, 140);

}

</style>