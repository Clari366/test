# test
```
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Weather</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #d0f9fd;
      padding: 20px;
    }

    .box {
      max-width: 400px;
      margin: auto;
      background-color: rgb(255, 255, 255);
      padding: 20px;
      border-radius: 10px;
    }

    h2 {
      text-align: center;
      color: #6400b6;
    }

    input {
      width: 100%;
      padding: 8px;
      margin-bottom: 20px;
      border-radius: 5px;
      border: 1px solid #cccccc;
    }

    .weather {
      text-align: center;
      margin-bottom: 20px;
    }

    details {
      background-color: #d1caf8;
      margin-bottom: 10px;
      padding: 10px;
      border-radius: 5px;
    }

    summary {
      font-weight: italic;
      cursor: pointer;
    }
  </style>
</head>
<body>

<div class="box">
  <h2>Weather</h2>

  <input type="text" placeholder="Enter city name">

  <div class="weather">
    <p><strong>City:</strong> India</p>
    <p><strong>Date:</strong> May 2, 2025</p>
    <p><strong>Time:</strong> 11:00 AM</p>
    <p><strong>Temperature:</strong> 32°C</p>
    <p><strong>Condition:</strong> Sunny 🌞</p> 
  </div>

  <details>
    <summary>Friday - 30°C 🌞</summary> 
    <p>Condition: Sunny 🌞</p> 
    <p>Humidity: 40%</p>
  </details>

  <details>
    <summary>Saturday - 28°C ☁</summary>
    <p>Condition: Cloudy ☁</p>
    <p>Humidity: 50%</p>
  </details>

  <details>
    <summary>Sunday - 25°C 🌧</summary>
    <p>Condition: Rainy 🌧</p> 
    <p>Humidity: 70%</p>
  </details>
</div>

</body>
</html>
```
