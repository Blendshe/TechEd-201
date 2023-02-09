**Useful Termnal Commands**

1.  |  pwd = print working directory
2.  | tree = shows the file tree of your directory
3.  | ls = list all the files and folders located in your current directory
4.  | ls -a = list all the files and folders located in your current directory including hidden files in short form
5.  | ls -la = list all the files and folders located in your current directory including hidden files in a more detailed form
6.  | cd = change directory
7.  | mkdir = make directory
8.  | touch = create a new file
9.  | code <filename> = open up this file in VSCode
10. | code . = open the current directory in VSCode

Other important ones:

11. mv = move a file
12. rm <filename> = remove a file permanently. Warning: there is no recovery!
13. cp <source> <destination> = copy a file

  **Task**
  
1.  | Paste your yesterdays code into your replit or vscode
2️.  | Create a click event handler and listener
3️.  | Now, when the click event happens we need to get four prompts --> education, favorite programming language, future dream role , holiday destination
4️.  | Now, when someone enters the favorite language of their own choice they needs to get an alert saying hey you have selected the favorite language....
5️.  | After all the prompts are done render that to the frontend.
  
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
