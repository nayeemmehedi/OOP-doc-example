    class Car { 
        constructor(name){
            this.name = name;
        }
    
        driving(){
            console.log("this car is driving and name is " + this.name);
        }
    }
    
    
    const value = new Car("toyota")
    
    value.driving()
