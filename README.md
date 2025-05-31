# Denemo-A.I-Calculator-
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>AI Calculator</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      max-width: 400px;
      margin: 40px auto;
      padding: 20px;
      border: 2px solid #ccc;
      border-radius: 10px;
    }
    input, button {
      margin: 10px 0;
      padding: 8px;
      width: 100%;
    }
    .results {
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <h2>AI Calculator</h2>
  <form id="calcForm" onsubmit="calculate(event)">
    <label>Enter number 1:</label>
    <input type="number" id="num1" required>

    <label>Enter number 2:</label>
    <input type="number" id="num2" required>

    <button type="submit">Calculate</button>
  </form>

  <div class="results" id="results"></div>

  <p>Thanks for using AI Calculator</p>
  <p>Visit again!</p>
  <p><strong>(Founder - Harshith)</strong></p>

  <script>
    functio
