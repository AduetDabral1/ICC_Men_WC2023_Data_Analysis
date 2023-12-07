<h1>ICC Men's Cricket World Cup 2023 Analysis</h1>
This project aims to build insights and identify the best 11 players for the 2023 ICC Men's Cricket World Cup using data scraped from ESPN Cricinfo.

<h3>Project Overview</h3>
<p>We all know just how popular cricket is globally. It is recorded that half a billion people tuned in for the most recent ICC Men’s ODI World Cup and that around 1.25 million people attended the game live at the venues. The final match was watched by 300 million people on TV while digital streaming of the match was watched by 59 million users, the most for any live-streamed sports event. These are some pretty big numbers and show just what an impact the game has around the world.

The 2023 ICC Men's Cricket World Cup was the 13th edition of the Cricket World Cup, a quadrennial One Day International (ODI) cricket tournament, in which ten national teams participated. The tournament was hosted by India. It started on 5 October and concluded on 19 November 2023, with Australia winning the tournament.

<strong>Your goal is to use the data of the matches available to build insights on a best 11 players team of the tournament.</strong></p>

<h3>Data and Methodology</h3>
The project utilizes three datasets scraped from ESPN Cricinfo:
<ol>
  <li>
    <strong>Match Summary:</strong> Contains information about each match, including winner, win margin, and scorecards (URL espncricinfo ON https://www.espncricinfo.com/records/tournament/team-match-results/icc-cricket-world-cup-2023-24-15338).
  </li>

  <li>
    <strong>Batting and Bowling Scorecard:</strong> Provides detailed statistics for each batsman and bowler in every match (Data scraped from espncricinfo)
  </li>

  <li>
    <strong>Player Data:</strong> Includes information about each player, such as batting and bowling styles, playing role, and team (Data scraped from espncricinfo).
  </li>
</ol>

 <h3>Implementation</h3>
<p>The data is processed and analyzed using Python libraries like <strong>Beautiful Soup</strong> and <strong>Selenium</strong> for web scraping and <strong>Pandas</strong> for data manipulation. The project utilizes various data analysis techniques to identify key performance indicators and select the best players based on performance metrics and team balance.</p>
