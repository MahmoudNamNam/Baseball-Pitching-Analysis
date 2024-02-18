## Baseball Pitching Analysis Project

### Overview:

This project focuses on analyzing pitching data for the Tampa Bay Rays in a baseball context. The dataset consists of information related to the pitches thrown during games, including details such as pitch type, pitch count, player positions, and outcomes.

### SQL Queries:

#### Question 1: AVG Pitches Per at Bat Analysis

- **1a AVG Pitches Per At Bat (LastPitchRays):**
  - Calculation of the average number of pitches per at-bat.

- **1b AVG Pitches Per At Bat Home Vs Away (LastPitchRays):**
  - Union query providing the average pitches per at-bat for home and away games.

- **1c AVG Pitches Per At Bat Lefty Vs Righty (LastPitchRays):**
  - Analysis of average pitches per at-bat for left-handed and right-handed batters.

- **1d AVG Pitches Per At Bat Lefty Vs Righty Pitcher | Each Away Team (LastPitchRays):**
  - Utilizing the `Partition By` clause to analyze pitches for lefty and righty pitchers during away games.

- **1e Top 3 Most Common Pitch for at bat 1 through 10, and total amounts (LastPitchRays):**
  - Determining the top 3 most common pitches for the first 10 pitches at-bat and total counts.

- **1f AVG Pitches Per at Bat Per Pitcher with 20+ Innings | Order in descending (LastPitchRays + RaysPitchingStats):**
  - Calculating the average pitches per at-bat for pitchers with 20 or more innings, ordered in descending order.

#### Question 2: Last Pitch Analysis

- **2a Count of the Last Pitches Thrown in Desc Order (LastPitchRays):**
  - Counting the occurrences of each last pitch thrown, ordered in descending order.

- **2b Count of the different last pitches Fastball or Offspeed (LastPitchRays):**
  - Differentiating and counting the occurrences of fastball and offspeed pitches.

- **2c Percentage of the different last pitches Fastball or Offspeed (LastPitchRays):**
  - Calculating the percentage of fastball and offspeed pitches.

- **2d Top 5 Most common last pitch for a Relief Pitcher vs Starting Pitcher (LastPitchRays + RaysPitchingStats):**
  - Identifying the top 5 most common last pitches for relief and starting pitchers.

#### Question 3: Homerun Analysis

- **3a What pitches have given up the most HRs (LastPitchRays):**
  - Determining which pitches have resulted in the most home runs.

- **3b Show HRs given up by zone and pitch, show top 5 most common (LastPitchRays):**
  - Displaying home runs given up by zone and pitch, highlighting the top 5.

- **3c Show HRs for each count type -> Balls/Strikes + Type of Pitcher (LastPitchRays):**
  - Analyzing home runs based on count types, including balls/strikes and pitcher type.

- **3d Show Each Pitcher's Most Common count to give up a HR (Min 30 IP):**
  - Identifying the most common count for each pitcher to give up a home run, considering a minimum of 30 innings pitched.

#### Question 4: Shane McClanahan Analysis

- **4a AVG Release speed, spin rate, strikeouts, most popular zone ONLY USING LastPitchRays:**
  - Calculating the average release speed, spin rate, strikeouts, and most popular zone for Shane McClanahan.

- **4b Top pitches for each infield position where total pitches are over 5, rank them:**
  - Identifying the top pitches for each infield position where the total pitches are over 5, ranked by frequency.

- **4c Show different balls/strikes as well as frequency when someone is on base:**
  - Displaying different balls/strikes and their frequency when a runner is on base for Shane McClanahan.

- **4d What pitch causes the lowest launch speed:**
  - Determining which pitch causes the lowest launch speed for Shane McClanahan.

### Conclusion:

This project showcases an in-depth analysis of pitching data, providing valuable insights into pitch tendencies, performance metrics, and strategic considerations for the Tampa Bay Rays. The combination of SQL queries demonstrates a comprehensive approach to baseball pitching analytics.

--- 
