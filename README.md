<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dee Dee Bakery</title>
  <link rel="stylesheet" href="styles.css">
<body>
        <input type="checkbox" name="breakfast" value="bacon">Bacon 🥓
        <input type="number" name="balance" placeholder="Select Quantity">
        <select name="rental-option">
            <option value="small">Ripe</option>
            <option value="family">Unripe</option>
            <option value="lux">Medium Rare</option>
        </select><br>
    <input type="checkbox" name="breakfast" value="eggs">Eggs 🍳
    <input type="number" name="balance" placeholder="Select Quantity">
    <select name="rental-option">
        <option value="small">Ripe</option>
        <option value="family">Unripe</option>
        <option value="lux">Medium Rare</option>
    </select><br>
    <input type="checkbox" name="breakfast" value="pancakes">Pancakes 🥞
    <input type="number" name="balance" placeholder="Select Quantity">
    <select name="rental-option">
        <option value="Ripe">Ripe</option>
        <option value="Unripe">Unripe</option>
        <option value="Medium Rare">Medium Rare</option>
    </select><br>


    <br><textarea rows="10" cols="30" name="comment" placeholder="Note here such as 'No spicy'"></textarea>


    <form method="post" action="http://server1">
        Enter your name:
        <input type="text" name="fname">
        <br>
        Enter your address:
        <input type="text" name="address">
        <br>

    <label for="nname">Nickname:</label>
    <input type="text" name="nname" id="nname"><br>

    <input type="checkbox" name="vehicle" value="Bike"> I agree
    <br>
    <input type="submit" value="Submit">
    </form>


</body>
</html>
