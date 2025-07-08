<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Haircut Appointment Booking</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      padding: 40px;
      background: #f7f7f7;
    }
    h1 {
      color: #333;
    }
    form {
      background: #fff;
      padding: 20px;
      max-width: 400px;
      border-radius: 8px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
    }
    label {
      display: block;
      margin-top: 15px;
    }
    input, select {
      width: 100%;
      padding: 10px;
      margin-top: 5px;
      border: 1px solid #ccc;
      border-radius: 4px;
    }
    button {
      margin-top: 20px;
      padding: 10px;
      width: 100%;
      background-color: #4CAF50;
      color: white;
      font-size: 16px;
      border: none;
      border-radius: 4px;
      cursor: pointer;
    }
    button:hover {
      background-color: #45a049;
    }
  </style>
</head>
<body>

  <h1>Book Your Haircut</h1>

  <form action="#" method="post">
    <label for="name">Your Name:</label>
    <input type="text" id="name" name="name" required>

    <label for="date">Appointment Date:</label>
    <input type="date" id="date" name="date" required>

    <label for="time">Appointment Time:</label>
    <input type="time" id="time" name="time" required>

    <label for="stylist">Choose Your Stylist:</label>
    <select id="stylist" name="stylist">
      <option value="Ms.Big">Ms.Big</option>
    </select>

    <button type="submit">Book Appointment</button>
  </form>

</body>
</html>
