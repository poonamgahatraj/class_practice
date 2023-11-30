<template>

</template>

<script>
class RailwayForm{
    submit(){
            alert(this.name+" "+"your form is submitted")
    }
    cancel(){
            alert(this.name+" "+"your form is  cancelled")
    }
    fill(givenname){
            this.name=givenname
    }
}

let x=new RailwayForm()
x.fill("poonam")
let y=new RailwayForm()
y.fill("vishu")

x.submit()
y.cancel()
</script>