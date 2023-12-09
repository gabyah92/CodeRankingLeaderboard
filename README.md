### ALL PLATFORM RATING APP

<img width="466" alt="Screenshot 2023-11-29 185520" src="https://github.com/gabyah92/CodeRankingLeaderboard/assets/22296232/51a4d877-a8e4-48f1-8243-fac7484f8681">

Hello everyone!

I have created this project(overnight) to scrape ratings from platforms which include CodeChef, LeetCode, GeeksforGeeks, Codeforces and HackerRank, for my batch in **CMRIT** and through my consultancy **Pyramid**.

The usage is quite simple! Just upload an excel sheet of users, provide usernames of all HackerRank Contests to be considered and it automatically generates an excel sheet printing out their ratings and scores(gfg, hackerrank) across the above mentioned 5 platforms. Note that Providing HackerRank Contests or HackerRank Usernames is Optional.

An Excel sheet must be selected which contains columns in this **EXACT** order: {**Handle, GFG_Handle, Codeforces_Handle, LeetCode_Handle, CodeChef_Handle, HackerRank_Handle(Optional)**}

The Excel sheet will be generated in the same directory as the jar file, in a folder called Leaderboards, which contains the following columns: {Handle, Codeforces_Handle, Codeforces_Rating, GFG_Handle, GFG_Contest_Score, GFG_Practice_Score, Leetcode_Handle, Leetcode_Rating, CodeChef_Handle, Codechef_Rating, HackerRank_Handle, HackerRank_Practice_Score, Percentile}

<img width="1169" alt="Screenshot 2023-11-29 185722" src="https://github.com/gabyah92/CodeRankingLeaderboard/assets/22296232/f1ab1f55-3406-4ff7-8793-a53e2ae79524">

The following metric was used in calculating the ranking: 

If Hackerrank Usernames & Contest ID's are provided :

30% Codeforces_Rating + 30% GFG_Contest_Score + 10% GFG_Practice_Score + 10% Leetcode_Rating + 10% Codechef_Rating + 10% HackerRank. 

If NOT:

35% Codeforces_Rating + 30% GFG_Contest_Score + 10% GFG_Practice_Score + 15% Leetcode_Rating + 10% Codechef_Rating. 

Since contest score can be too big when compared to ratings, normalization was performed for the exact metric.

Please let me know if you have any questions or need further clarification.

Leave a star if you liked it. Follow me on Instagram : **[gabyah92](instagram.com/gabyah92)**

USAGE : 
- Download and install Java **[here](https://www.oracle.com/java/technologies/downloads/#jdk21-windows)**.
- Download the latest release zip file and extract **[here](https://github.com/gabyah92/CodeRankingLeaderboard/releases)**. 
- Run the CodeRankingLeaderboard.jar file in extracted folder.
