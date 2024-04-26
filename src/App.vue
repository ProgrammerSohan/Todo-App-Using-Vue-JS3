<template>
   <Todo />
</template>
 <script>
import Todo from "./components/Todo.vue";

 export default {
     name: "App",
      components: { Todo },
       
     };
 
 </script>
 <style>
 @import url('https://fonts.googleapis.com/css2?family=Jersey+25&display=swap');

 *{
   margin: 0;
   padding: 0;
   box-sizing: border-box;
   list-style-type: none;
 }

body {
  font-family: "Jersey 25", sans-serif;
  font-weight: 400;
  font-style: normal;
  width: 100%;
  height: 100vh;
  overflow: hidden;
  background-color: #2c3e50;
  color:white;
}


 #app{
  text-align: center;
  margin-top: 60px;

 }

 
 </style>