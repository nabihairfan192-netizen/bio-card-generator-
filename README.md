# bio-card-generator-
its a auto bio card generator 
<!doctype html>
<html lang="en">
    <head>
       <meta charset="UTF-8">
       <meta name="viewport" content="width=device-width, initial-scale=1.0">
       <title>My first website</title>
   </head>
   <body>
        <h1>Auto Bio Card Generator</h1>

<div class="form">
  <input type="text" id="name" placeholder="Name">
  <input type="text" id="about" placeholder="1 Line About You">
  <select id="mood">
    <option value="chill">Chill 😎</option>
    <option value="motivated">Motivated 💪</option>
    <option value="creative">Creative 🎨</option>
    <option value="funny">Funny 😂</option>
  </select>
  <button onclick="generateCard()">Generate My Card</button>
</div>

<div class="card" id="card">
  <h2 id="cardName">Your Name</h2>
  <p id="cardAbout">Your about line</p>
  <p id="cardMood">Mood: Chill</p>
</div>

<script src="script.js"></script>
</body>
</html>
