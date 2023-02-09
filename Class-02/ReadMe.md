
**Lab**

1.  | create four prompts
2️.  | each prompt should ask your name, age, country and fav color respectively
3️.  | Create a LIST in your html
4️.  | This list should contain four list items with name, age, country and fav color
5️.  | the values you enter in your prompt should be rendered in the frontend and the text color should be the fav color you entered
  
 ```
  <!DOCTYPE html>

<html>

<head>

</head>

<body>

  <h1 id="example">Class-02 Example Array</h1>

  <button onclick="clickHandler()">Click</button>


  <script>

    var campervan = [];//[] --> arrays


    function clickHandler() {

      var newCampervan = prompt("Enter newCampervan");

      campervan.push(newCampervan);
      
      console.log(campervan);
    }


  </script>
</body>

</html>
  
  
  //next task
  
  <!DOCTYPE html>
<html>

<head>
  <style>
    body {
      font-family: Arial, Helvetica, sans-serif;
      font-size: 20px;
      background-color: teal;
    }
  </style>
  
</head>

<body>

  <p id="someText">Questions</p>

  <button id="setquestionButton" onclick="setquestion()">click to answer questions</button>

 

  <ul>
    
    <li>Jane</li>
    <li>Don't be nosey</li>
    <li>UK</li>
    <li>Teal</li>
 
  </ul>

 <button id="morequestionButton" onclick="morequestion()">more questions</button>

    <ul>
     
    <li>Masters</li>
    <li>web developer</li>
    <li>Portugal</li>
    <li>Javascript</li>
 
  </ul>
  
  <script>

     function setquestion() {

      var name = prompt("Enter your name:");
      console.log("name will be:" + name);

      var age = prompt("Enter your age:");
      console.log("Age will be:" + age);

      var country = prompt("Enter your country:");
      console.log("Country will be:" + country);
      
      var favoritecolor = prompt("Enter your favourite color:");
       
      console.log("favorite color will be:" + favoritecolor);

     }
    
 function morequestion() {

      var education = prompt("Enter your education:");
   
      console.log("education will be:" + education);

      var futuredreamrole = prompt("Enter your future dream role:");
   
      console.log("Future dream role will be:" + futuredreamrole);
      
      var holidaydestination = prompt("Enter your favourite holiday destination:");
   
      console.log("holiday destination will be:" + holidaydestination);   

    //*this needs if and else for the alert to come up only for the right answer*
    
     var programminglang = prompt("Enter your favorite programming language:");
     
   console.log("programming language will be:" + programminglang);

   alert("hey you have selected the favorite language...")

    }
    
  </script>

</body>

</html>
  
 ```
 
 **Push - code from V**
 ```
 <!DOCTYPE html>
<html>

<head>

</head>

<body>

  <h1 id="example">Class-02 Example</h1>

  <button onclick="clickHandler()">Click</button>


  <script>

    var studentsInTheClass = [];//[] --> arrays


    function clickHandler() {

      var newStudent = prompt("Enter new student name");

      studentsInTheClass.push(newStudent);
      
      console.log(studentsInTheClass);
    }


  </script>
</body>

</html>

```

**Array**

Code by V as example 

```
<!DOCTYPE html>
<html>

<head>
</head>

<body>

  <h1 id="example">Class-02 Example</h1>
  <p id="here">Jez details here</p>
  <button onclick="clickHandler()">Click</button>

  <script>

    var studentsInTheClass = [];//[] --> arrays

    function clickHandler() {

      var newStudent = prompt("Enter new student name");

      studentsInTheClass.push(newStudent);



      console.log(studentsInTheClass);

      if (newStudent == 'Jez' || newStudent == "jez" || newStudent == "j") {

        document.getElementById('here').innerHTML = "jex welcome to the evening class from the morning class";

      }else{
        document.getElementById('here').innerHTML = "jez  is not welcome to the evening class from the morning class";
      }


    }

  </script>
</body>

</html>

```

**Task**

1️. | Create a button and name it as guess
2️.  | Add an event listener and event handler to it
3️.  | Create a new variable and and a number to it/assign a value.
4️.  | when someone clicks on the button they should get a popup
5️.  | this popup should ask us a number
6️.  | the number should be guessed in six attempts


My code 
 
 ```
 <!DOCTYPE html>
<html>

<head>
  <style>
    body {
      font-family: Arial, Helvetica, sans-serif;
      font-size: 20px;
      background-color: lightblue;
    }
  </style>
  
</head>

<body>

  <p id="someText">Guess the number</p>

  <button id="setquestionButton" onclick="setquestion()">click to guess the number</button>

 

  
  <script>

     function setquestion("what do you think the number is?") 
    
      {

       //condition
       //Use if to specify a block of code to be executed, if a     specified condition is true
      //Use else to specify a block of code to be executed, if the same condition is false
      //Use else if to specify a new condition to test, if the first condition is false
       
      var guess = prompt("Guess a number:");
      console.log("name will be:" + guess);

      if(numberis42) 
      
              
   //  block of code to be executed if the condition is true
        
      alert ("hey you have selected the number 42 well done!!!!");
      
      //else()

        
}
 
  </script>

</body>

</html>

V code for the task

```
<!DOCTYPE html>
<html>
  <head>
    
  </head>

  <body>


  <button onclick="clickHandler()">Guess my lucky number</button>


    <script>
      var numberToBeGuessed = 16;
      var attempts = 0;
      
      function clickHandler(){
        var guessedNumber = prompt('Enter a number');
        console.log('its working');

        attempts++;// this actually increments the value by +1  
        // logic
        if(attempts == 6){
          alert("hey you actually used all the attempts")
        }else{

          if(guessedNumber == numberToBeGuessed){
          alert("Heyyyy you guessed it right");
          }else if(guessedNumber > numberToBeGuessed){
            alert("Its high");
          }else if(guessedNumber < numberToBeGuessed){
            alert("its low");
          }
          
        }
        
        
      }
    </script>
  </body>
</html>
  
 ```
  
