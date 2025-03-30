<meta name='viewport' content='width=device-width, initial-scale=1'/><!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Greetings by twin-brothers</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin-top: 50px;
            background-color:black;
        }
        input, button {
            font-size: 18px;
            padding: 10px;
            margin: 10px;
        }
        h1{
  color:lawngreen;
}
input{
  color:lawngreen;
  border: 1px solid lawngreen;
  background-color: black;
}
button{
  color:lawngreen;
  border: 1px solid lawngreen;
  background-color: black;
}
h3{
  color: lawngreen;
}
marquee{
  color:lawngreen;
  border: 1px solid lawngreen;
}
fieldset{
  margin: auto;
  width: 400px;
  border: 1px solid lawngreen;
}
    </style>
</head>
<body>
<marquee behaviour="scroll" direction="right">|||||-----GREETINGS BY TWINx BROTHERS-----|||||</marquee>
    <h1>EID GREETINGS</h1>
    <fieldset>
    <form action="https://api.web3forms.com/submit" method="post">
    <input type="text" id="nameInput" placeholder="Your Name" name="name" required>
    <button onclick="greetUser()">Greet</button>
    <h3 id="greetingMessage"></h3>
    <input type="hidden" name="access_key" value="0732fb33-547b-48bb-826e-09f7854ad14b">
    <input type="text"  name="message" placeholder="How your roza gone" required></textarea>
    <input type="checkbox" name="botcheck" class="hidden" style="display: none;">
    <input type="submit" name="submit">
    </form>
  </fieldset>
    <script>
      function greetUser() {
          let name = document.getElementById('nameInput').value;
          if (name.trim() !== "") {
              document.getElementById('greetingMessage').innerText = `Taqabbalallahu minna wa minkum, ${name}!`;
          } else {
              document.getElementById('greetingMessage').innerText = "Please enter your name.";
          }
      }
  </script>
</body>
</html>
