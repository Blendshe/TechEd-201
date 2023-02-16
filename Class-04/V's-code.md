
**Day 6 14.02.23**

**Get and Set functions**

```
<!DOCTYPE html>
<html>
  <head>
    
  </head>

  <body>

    <div>

      <button onclick="getTheCity()">GET THE CITY</button>

      <button onclick="setTheCity()">SET THE CITY</button>
     
    </div>


    <script>

      var city = "Norwich";

      function getTheCity(){
         console.log(city);
      }

      function setTheCity(){
        city = prompt('Enter the city');
        //console.log(city);
      }
           
    </script>
    
  </body>
  
</html>

```


**Day 7 15.02.23**

**Setter and Getter functions continued**

```

<!DOCTYPE html>
<html>
  <head>
    
  </head>

  <body>

    <button onclick="getSecretNumber()">Get Secret Number</button>

    <button onclick="setSeretNumber()">Set Secret Number</button>

    <script>

      var secretNumber = 20;
      
      function getSecretNumber(){// gets the secret number
        console.log(secretNumber)
      }

      function setSeretNumber(){// you are setting the secret number
        secretNumber = prompt("set the secret number");
      }
      
    </script>
    
  </body>
</html>

```
