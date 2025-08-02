MLB Standings Race Chart (2025)
An interactive, live-updating chart that visualizes the day-by-day standings for the 2025 Major League Baseball season. This tool allows users to track the performance of teams in each division and follow the Wild Card races as the season unfolds.

Live Demo
(You can paste your live GitHub Pages link here!)

https://YourUsername.github.io/Your-Repository-Name/

Features
Historical Performance Tracking: The chart is built using actual day-by-day game results, not a simulation.

Division Races: View the performance of all teams in any of the six MLB divisions (AL East, Central, West & NL East, Central, West).

Wild Card View: Special views for both the American League and National League Wild Card races, showing the top contenders.

".500" Benchmark: All graphs are anchored to the .500 line, making it easy to see how far above or below a .500 winning percentage each team is.

Live Data: The chart automatically fetches the latest game results every time the page is loaded, ensuring the data is always up-to-date.

Interactive Tooltips: Hover over the chart to see specific details for any team on any given day.

How It Works
This project is a self-contained, single-page web application that runs entirely in the browser.

Data Fetching: On page load, the application's JavaScript fetches game-by-game results for the entire 2025 season from a public ESPN sports API.

Data Processing: It processes the results chronologically to build a daily win-loss record for every team.

Visualization: The processed data is then rendered into an interactive line chart using the Chart.js library.

Technology Stack
HTML5: For the basic structure of the page.

Tailwind CSS: For modern, responsive styling.

JavaScript (ES6+): For data fetching, processing, and all application logic.

Chart.js: For creating the interactive and beautiful charts.

date-fns Adapter: Used with Chart.js to handle the time-series x-axis.

How to Use or Publish
Since this is a self-contained index.html file, it is very easy to run or host.

Running Locally
Download the index.html file from this repository.

Double-click the file to open it in any modern web browser like Chrome, Firefox, or Safari.

Publishing Your Own
Create a new public repository on GitHub.

Upload the index.html file to the repository.

Go to the repository's Settings > Pages.

Under "Branch," select main and /root, then click Save.

Your site will be live at the provided URL.

Data Source
All game and standings data is sourced from the publicly available, undocumented ESPN Scoreboard API.
