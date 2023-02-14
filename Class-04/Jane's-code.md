



**Class 4 14.02.23**

```

<!DOCTYPE html>
<html>

<! TASK 
1️⃣  | Create  a setter function to set a score in rugby
2️⃣  | Create a setter function to set a score in football.
3️⃣  | Create a getter function to get the score of rugby
4️⃣  | Create a getter function to get the score of football
  
  <head>


<h1>The Getter and Setter function</h1>
    
  </head>

  <body>

    <div>
      <button onclick="setTheRugbyScore()">SET THE RUGBY SCORE</button>
      
      <button onclick="getTheRugbyScore()">GET THE RUGBY SCORE</button>

      <button onclick="setTheFootballScore()">SET THE FOOTBALL SCORE</button>
      
      <button onclick="getTheFootballScore()">GET THE FOOTBALL SCORE</button>   
     
    </div>

    <script>

      var score = "1-0";
      
      function setTheRugbyScore(){
        
        score = prompt('Enter the score');
          //console.log(score);
        
      }
      
      function getTheRugbyScore(){
         console.log(score);
        
      }

      function setTheFootballScore(){
        
        score = prompt('Enter the score');
          //console.log(score);

      }

     function getTheFootballScore(){
         console.log(score);
      
     }  
      
    </script>
    
  </body>
  
</html>

```
