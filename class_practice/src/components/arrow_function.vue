<template>

</template>

<script>
let greet = function(){
  
  console.log("hello")
  return 1;
}

console.log(greet());

//arrow function

let x = () => {
  console.log("hello Poonam")
}

x();

//arrow function with arguments

let y = (user) =>{
  console.log("hello" + " " +user)
}

y("vishu");

//arrow funtion with only one argument

let a= (user) => console.log("hello"+" "+user)
a("luxmi");
</script>