function calcola(operazione, out1,out2){
    
      switch(operazione)
          case'somma':
          return out1 + out2;
          break;
          
          case'sottrazione':
          return out1 - out2;
          break;
          
          case'moltiplicazione':
          return out1 * out2;
          break;
          
          case'divisione':
          return out1 / out2;
          break;
          
       }
       
   }
   console.log(calcola('somma',2,4));
   console.log(calcola('sottrazione',2,4));
   console.log(calcola('moltiplicazione',2,4));
   console.log(calcola('divisione',2,4));
