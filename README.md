# Weekly Luck Counter for Studying in Switzerland

## Overview

This is a simple HTML page designed to help you track and record your friend's weekly luck while studying in Switzerland. The page includes a user-friendly interface where you can input and update luck scores for each week.

## Features

- **Luck Input**: Easily input your friend's luck score for each week.
- **Weekly Overview**: View a summary of luck scores for each week.
- **Visual Representation**: A graphical representation of luck scores over time.

## How to Use

1. **Input Luck Score**: In the designated input field, enter your friend's luck score for the current week. You can use a scale of 1 to 10, with 1 being the least lucky and 10 being the luckiest.

2. **Update Weekly Luck**: Click the "Update" button to record the luck score for the current week. The page will automatically update the weekly overview and graphical representation.

3. **View Weekly Overview**: Check the table to see a summary of luck scores for each week.

4. **Visualize Luck Trends**: The graph below the table provides a visual representation of luck scores over time, helping you identify any patterns or trends.

## Sample Code

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Weekly Luck Counter</title>
    <style>
        /* Add your custom styles here */
        body {
            font-family: 'Arial', sans-serif;
            text-align: center;
            margin: 20px;
        }
        /* Add more styles as needed */
    </style>
</head>
<body>
    <h1>Weekly Luck Counter</h1>

    <!-- Luck Input Form -->
    <label for="luckInput">Enter Luck for This Week (1-10): </label>
    <input type="number" id="luckInput" min="1" max="10" required>
    <button onclick="updateLuck()">Update</button>

    <!-- Weekly Overview Table -->
    <h2>Weekly Overview</h2>
    <table border="1">
        <thead>
            <tr>
                <th>Week</th>
                <th>Luck Score</th>
            </tr>
        </thead>
        <tbody id="weeklyOverview">
            <!-- Weekly overview will be dynamically populated here -->
        </tbody>
    </table>

    <!-- Luck Trends Graph -->
    <h2>Luck Trends</h2>
    <canvas id="luckChart" width="400" height="200"></canvas>

    <script>
        // Add your JavaScript logic here
        function updateLuck() {
            // Implement the logic to update luck scores
        }
        // Add more JavaScript functions as needed
    </script>
</body>
</html>
```

Feel free to customize the HTML, CSS, and JavaScript code to suit your preferences and requirements. If you're not familiar with JavaScript, you might want to explore JavaScript charting libraries for a more sophisticated visual representation of luck trends.
