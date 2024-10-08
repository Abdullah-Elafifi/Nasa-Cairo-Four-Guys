<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Four Guys Team - Emissions Anomalies Map</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #e0e0e0;
            color: #333;
        }
        header {
            background-color: #003366;
            color: white;
            padding: 10px 20px;
            display: flex;
            align-items: center;
            justify-content: flex-start;
        }
        .header-content {
            display: flex;
            align-items: center;
        }
        .header-content img {
            margin-right: 5px;
        }
        h1 {
            margin: 0;
            font-size: 2.5em;
        }
        h2 {
            text-align: center;
            font-size: 2em;
            margin: 20px 0;
        }
        h3 {
            text-align: center;
            font-size: 1.5em;
            margin: 10px 0;
        }
        p {
            font-size: 1.2em;
            margin: 5px 0 10px;
        }
        .iframe-container {
            display: flex;
            justify-content: space-between;
            align-items: flex-start;
            padding: 20px;
        }
        .map-container {
            width: 48%;
            text-align: center;
        }
        .map {
            width: 100%;
            height: 500px;
            border: none;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.2);
            border-radius: 8px;
        }
        footer {
            background-color: #003366;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        .logo {
            max-width: 350px;
            max-height: 150px;
        }
    </style>
</head>
<body>

<header>
    <div class="header-content">
        <img src="Nasa_Logo.png" alt="Logo" class="logo">
        <div>
            <h1>Four Guys Team</h1>
            <p>Project Name: Integrated AI Framework for Predictive Environmental and Emission Analysis</p>
            <p>Category Name: Uncover the Role of Greenhouse Gases in Your Neighborhood!</p>
        </div>
    </div>
</header>

<div class="iframe-container">
    <div class="map-container">
        <h3>The Automated Map for Anomaly/Normal Detection <br>of Carbon Monoxide & Methane Emissions</h3>
        <iframe class="map" src="emissions_anomalies_map_virginia_with_ripples.html"></iframe>
    </div>
    <div class="map-container">
        <h3>Historical Predictive Map & Scenario Exploration <br> for Factroies and Diffenrt Energy Projects</h3>
        <iframe class="map" src="virginia_environmental_analysis_map.html"></iframe>
    </div>
</div>

<footer>
    <p>&copy; 2024 Four Guys Team. All rights reserved.</p>
</footer>

</body>
</html>
