<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Medication Side Effects</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="container">
    <header>
      <h1>Medication Side Effects</h1>
    </header>
    
    <div class="search-box">
      <input type="text" id="medicationInput" placeholder="Enter medication name..." />
      <button onclick="searchMedication()">Search</button>
    </div>
    
    <div id="results">
      <!-- Side effects will be displayed here -->
    </div>
  </div>

  <script src="script.js"></script>
</body>
</html>
