
Example 

    class Parents { 
        #need
    
        constructor(food,need){
            this.food = food;
            this.#need = need;
        }
    
        getFood(){
            console.log(`this ${this.food} really important `)
        }
    
        getNeed(){
            console.log(`this ${this.#need} really important`)
        }
    }
    
    class child extends Parents {
        constructor(food,age){
            super(food,age);
        }
    
        getFood(){
            console.log(`this ${this.food} really bad `)
        }
    
    }
    
    
    const value = new child("Vegetable",23)
    
    // value.getFood()
    value.getNeed()
