    class EncapsulationManager {
        #myName
    
      constructor(name, age) {
        this.#myName= name;
        this.age = age;
      }
    
      #fullDetails() {
        console.log(`${this.#myName} my name : ${this.age}`);
      }
    
      hiddenDetails() {
        this.#fullDetails();
      }
    }
    
    
    const person =new EncapsulationManager("Nayeem",23)
    
    // console.log(person.#myName)  error
