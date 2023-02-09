
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
