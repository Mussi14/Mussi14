<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Footprint</title>
    <script src="data.js" defer></script>
<style>
    input {
        cursor: pointer;
    }
</style>
</head>
<body>


    <h1>Carbon Footprint</h1>
    <form>
        <label for="myName">What is your name?</label>
        <input type="text" id="myName" placeholder="Your name here!">
        <br>
        <br>
        <label for="birthdate">Put your birthdate here</label>
        <input type="date" id="my Birthdate" placeholder="dd/m/yyyy">
    </form>

    <form>
        <p>Select your eating habits:</p>
        <input type="radio" id="heavyeater" name="habit" value="Heavy">
        <label for="Heavy">Heavy meat eater (+100g)</label><br>
        <input type="radio" id="mediumeater" name="habit" value="medium">
        <label for="medium">Medium meat (50-99g))</label><br>
        <input type="radio" id="loweater" name="habit" value="low">
        <label for="low">Low meat (-50g)</label>
      <br>
        <input type="radio" id="fisheater" name="habit" value="fish">
        <label for="fish">Pescaterian</label>
      <br>
        <input type="radio" id="vegan" name="habit" value="vegan">
        <label for="vegan">Vegan</label>
      <br>
        <input type="radio" id="vegetarian" name="habit" value="vegetarian">
        <label for="vegetarian">Vegetarian</label>
      <br>
      <br>
     <button type="submit">Submit data</button>
<form>
 <br />
 <br />
 <p>Your carbon footprint: <input type="text" id="result" /></p>
        
</body>
</html> 
