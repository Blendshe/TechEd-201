1️⃣ | Create 10 elements with different ids   
2️⃣ | Create a button with event handler and event listener  
3️⃣ | When someone clicks the button all the innerHTML and also all the styles should change  
  
Paisleys code for reference  

```
<!DOCTYPE html>

<html>
    <head>
        <title>Class 06 Task</title>

        <style>
            ol {
                font-size: 30px;
            }
        </style>
    </head>

    <body>
        <h1>Class 06 Task</h1>

        <h2>Top 10 Biggest Animals!</h2>

        <ol>
            <li id="no1">Blue Whale</li>
            <li id="no2">North Pacific Right Whale</li>
            <li id="no3">Giant Squid</li>
            <li id="no4">Whale Shark</li>
            <li id="no5">White SHark</li>
            <li id="no6">Elephant</li>
            <li id="no7">Giraffe</li>
            <li id="no8">Anaconda</li>
            <li id="no9">Crocodile</li>
            <li id="no10">Polar Bear</li>
        </ol>

        <button onclick="clickHandler()">
            Click Here to See the Smallest Animals
        </button>

        <script>
            function clickHandler() {
                document.getElementById('no1').innerText =
                    'Paedophryne amauensis (a frog)';
                document.getElementById('no1').style.color = 'green';

                document.getElementById('no2').innerText = "Kitti's Hog Nosed Bat";
                document.getElementById('no2').style.color = 'grey';

                document.getElementById('no3').innerText = 'Bee Hummingbird';
                document.getElementById('no3').style.color = 'blue';

                document.getElementById('no4').innerText = 'Northern Pygmy Owl';
                document.getElementById('no4').style.colour = 'purple';

                document.getElementById('no5').innerText = 'Baluchistan Pygmy Jerboa';
                document.getElementById('no5').style.color = 'brown';

                document.getElementById('no6').innerText = 'Slender Blind Snake';
                document.getElementById('no6').style.color = 'mauve';

                document.getElementById('no7').innerText = 'Etruscan Shrew';
                document.getElementById('no7').style.color = 'pink';

                document.getElementById('no8').innerText = 'Speckled Padloper Tortoise';
                document.getElementById('no8').style.color = 'cyan';

                document.getElementById('no9').innerText = "Madame Berth's Mouse Lemur";
                document.getElementById('no9').style.color = 'green';

                document.getElementById('no10').innerText = 'Pygmy Rabbit';
                document.getElementById('no10').style.color = 'brown';

                document.getElementsByTagName('ol').style.fontSize = 'smaller';
                //document.getElementsByName('li').style.fontSize = 'smaller';
            }
        </script>
    </body>
</html>
```
