<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8"/>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>E-Cell Feedback Form</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <h1>E-Cell Feedback Form</h1>
  <form>
    <label for="name">Full Name</label>
    <input type="text" id="name" name="name" placeholder="Enter your name" required/>

    <label for="rating">How would you rate the event?</label> 
      <select id="rating" name="rating" required>
        <option value="">Select rating</option>
        <option value="5">&#9733; &#9733; &#9733; &#9733; &#9733;-Amazing</option>
        <option value="5">&#9733; &#9733; &#9733; &#9733;-Very Good</option>
        <option value="5">&#9733; &#9733; &#9733;-Good</option>
        <option value="5">&#9733; &#9733;-Okay</option>
        <option value="5">&#9733;-Poor</option>
      </select>

        <label for="fav">What did you like the most?</label>
        <textarea id="fav" name="fav" placeholder="Your favourite part..."
        required></textarea>

        <label for="suggestion">Suggestion to improve more</label>
        <textarea id="suggestion" name="Suggestion" placeholder="What can we do bettet?" required></textarea>
        <label for="future">Would you attend future event?</label>
        <select is="future" name="future" required>
          <option value="">Select></option>
          <option value="yes">Yes</option>
          <option value="no">No</option>
        </select>

        <button type="submit">Submit Feedback</button>

      </form>

  
</body>
</html>
