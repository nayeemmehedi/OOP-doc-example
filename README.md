    class Parents {
      
      constructor(pant) {
        this.pant = pant;
      }
    }
    
    class child extends Parents {
      constructor(pant) {
        super(pant);
      }
    
      childValue() {
        console.log(this.pant);
      }
    }
    
    const value = new child("underware");
    value.childValue();
