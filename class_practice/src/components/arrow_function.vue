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

//only one argument then no need of ()

let apple = user => console.log("hello" + " " + user)
apple("sam");

let q = {
name : "kdjfkl",
class:2,
address: function (){
    setTimeout(() =>{
        console.log(this)
        console.log("class is" + " "+ this.class)
        
    })
}
}

q.address();
</script>