```
<!DOCTYPE html>
<html>

<head>

  <style>
    #section {
      border: 1px solid black;
      color: antiquewhite;
      background-color: blueviolet;
      /* yellow */
    }
  </style>

</head>

<body>

  <h1 id='some-text' onclick="onHoverHandler()">Hello wooold</h1>

  <div id='section'>
    <p>This is cool</p>
    <p>This is not cool</p>
  </div>

  <script>

    function onHoverHandler() {

      document.getElementById('some-text').innerText = "hello world";

      document.getElementById('section').style = "background-color:yellow;color:blue";

      document.getElementById('section').style.backgroundColor = "green";
    }

    console.log(document.getElementById('section').style);

  </script>

</body>

</html>

```
