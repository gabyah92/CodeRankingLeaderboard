### ALL PLATFORM RATING APP

<img width="462" alt="Screenshot 2023-11-26 220157" src="https://github.com/gabyah92/CodeRankingLeaderboard/assets/22296232/cfc06213-3fc4-42f0-8b40-b672498317c9">

Hello everyone!

I have created this project(overnight) to scrape ratings from platforms which include CodeChef, LeetCode, GeeksforGeeks and Codeforces, for my batch in **CMRIT** and through my consultancy **Pyramid**.

The usage is quite simple! Just upload an excel sheet of users and it automatically generates an excel sheet printing out their ratings and scores(gfg) across the above mentioned 4 platforms.

An Excel sheet must be selected which contains columns in this **EXACT** order: {Handle, GFG_Handle, Codeforces_Handle, LeetCode_Handle, CodeChef_Handle}

The Excel sheet will be generated in the same directory as the jar file, in a folder called Leaderboards, which contains the following columns: {Handle, Codeforces_Handle, Codeforces_Rating, GFG_Handle, GFG_Contest_Score, GFG_Practice_Score, Leetcode_Handle, Leetcode_Rating, CodeChef_Handle, Codechef_Rating}

<img width="1220" alt="Screenshot 2023-11-26 232103" src="https://github.com/gabyah92/CodeRankingLeaderboard/assets/22296232/8f1ff523-b61c-4cb8-94ea-78342f512cee">


The following metric was used in calculating the ranking: 35% Codeforces_Rating + 30% GFG_Contest_Score + 10% GFG_Practice_Score + 15% Leetcode_Rating + 10% Codechef_Rating. Since contest score can be inadequate when compared to ratings, normalization was performed for the exact metric.

Please let me know if you have any questions or need further clarification.

Leave a star if you liked it. Follow me on Instagram : **[gabyah92](instagram.com/gabyah92)**

USAGE : 
- Download and install Java **[here](https://www.java.com/en/download)**.
- Download the latest release zip file and extract **[here](https://github.com/gabyah92/CodeRankingLeaderboard/releases)**. 
- Run the CodeRankingLeaderboard.jar file in extracted folder.
