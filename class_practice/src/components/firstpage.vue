<template>

</template>

<script>
class RailwayForm{
    constructor(givenname){
        console.log("constructor is called")
        this.name=givenname
    }    
    submit(){
            alert(this.name+" "+"your form is submitted")
    }
    cancel(){
            alert(this.name+" "+"your form is  cancelled")
    }
   
}

let x=new RailwayForm("Poonam")

let y=new RailwayForm("Vishu")


x.submit()
y.cancel()
</script>