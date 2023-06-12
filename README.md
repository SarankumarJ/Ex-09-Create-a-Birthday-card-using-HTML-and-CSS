# Ex-09-Create-a-Birthday-card-using-HTML-and-CSS
## AIM:
To write html & css code to create birthday card.

## PROCEDURE:
### STEP 1:
Create a html code for the birthday card.

### STEP 2:
Make style for the birthday card using css.

### STEP 3:
Link the css with html by link tag

### STEP 4:
Verify the output by running the birthday card in any web browser.
## Program:-
```html
<!DOCTYPE html>
<html>
<head>
  <title>Birthday Card</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f4f4;
      text-align: center;
    }
    
    .card {
      width: 400px;
      margin: 50px auto;
      padding: 20px;
      background-color: #ffffff;
      border: 1px solid #dddddd;
      border-radius: 5px;
    }
    
    h1 {
      color: #ff4081;
    }
    
    p {
      color: #333333;
    }
    
    .message {
      font-size: 20px;
      font-weight: bold;
      margin-top: 30px;
    }
    
    .sender {
      font-style: italic;
      margin-top: 10px;
    }
  </style>
</head>
<body>
  <div class="card">
    <h1>Happy Birthday!</h1>
    <p>Wishing you a day filled with joy and happiness.</p>
    <img src="https://funkylife.in/wp-content/uploads/2021/11/happy-birthday-images-60.jpg" alt="Birthday Image" width="300">
    <p class="message">Best wishes,</p>
    <p class="sender">Sarankumar J</p>
  </div>
</body>
</html>

```
## Output:-
![git](./birthday%20card.png)
## Result:-
html & css code to create birthday card has been created and output has been verified.