<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>class-01</title>
    
</head>


<body>
    

    <main>
        <header>class-01</header>
    <h1 style="color: indigo; background-color: lavenderblush;"> Class 1 Lab</h1>
   
    
   
       

        <p style="font-size: large;">Estimation nutritional adequacy</p>
        <p style="color: rgb(68, 8, 53); background-color: rgb(128, 105, 255);" >How much fruit serving do you eat per day?</p>
       
        <script>
             var serving = prompt("How much fruit serving do you eat per day?" , "3");
            
        
            console.log(serving);
        

        </script>

        <p style="background-color: indigo; color: lemonchiffon;">How much water do you drink per day?</p>

        <script>
           
                let waterCups = prompt("How much water do you drink per day", int nextInt());
              

                console.log(waterCups);
           
            

        </script>

        <p style="color: yellow; background-color: violet; font-family: verdana">Do you take any kind of supplement?</p>
        <script>
       
            let supplement = prompt("Do you take any kind of supplement?" , "No");
           
            console.log(supplement); 

        
    </script>
    <p style="color: rgb(131, 27, 8); background-color: olive; border: 2px solid powderblue; padding: 30px;">What kind of food do you prefer?</p>




        <script>
    


           
            
                
        
               
        
                let food = prompt("What kind of food do you prefer?", "healthy food");
               
                console.log(food);
            
                alert("Your fruit serving size are:  " + serving +
                  " your consumption of water per day:" + waterCups +
                  " If you take any supplement :  "+ supplement +
                  " the kind of food  you prefer :  " + food);
            
        
           
        

        
          
            </script>
    </main>
<footer>

</footer>



    
</body>
</html>