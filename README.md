# Student-Streaks-Analysis-with-SQL
A key metric that stands out in the online education field is the streak—the number of consecutive interactions counted by days. EdTech businesses and learning platforms leverage this type of user data to reveal patterns of commitment, consistency, and dedication.


Streaks are a crucial part of such companies’ data analysis processes as they communicate important insights about how (and how often) people engage with the product. In this Student Streaks Analysis with SQL project, we’ll work with real-world data in SQL and a provided learning streak table to identify those students who’ve spent the most time on the 365 Data Science website.  
Identifying your most engaged students is important as they can give you insights into how and why they engage with the product. For example, once you’ve recognized the top students, you can contact them for a testimonial and feedback—in other words, how they use the product, what they like about it, and what improvements or new features they wish to see. This information then acts as a steppingstone to enhance your unique selling proposition.

The Database: To identify the most engaged students, the SQL project provides a MySQL database for you to use in Workbench. Inside, you’ll find a user streaks table that includes the following fields:

 streak_id  – Unique identifier for each streak record
 user_id  – Identifier for each user
 streak_active  – A Boolean field indicating whether the streak is currently active (True) or not (False)
 streak_frozen  – A Boolean field indicating whether the streak is currently frozen (True) or not (False)
 streak_platform  – The platform on which the streak was recorded
 streak_created  – The date when the streak was started or updated

Calculating User Streaks: The objective for this SQL project is to calculate each user’s most extended streak length. The metric’s duration increments each day the user remains active, and they haven’t frozen their streak manually to preserve their progress. The length is not extended when there are no new daily interactions or when the streak is frozen.

## Project requirements
The Student Streaks Analysis with SQL project requires MySQL and Workbench 8.0 or higher on your computer

## Project files
The data in the Student Streaks Analysis with SQL project contains information about learning streaks and daily entries about streak status and freezes of users.

#### Database Download
[Download User Streak SQL Database Script](https://raw.githubusercontent.com/zooviee/Student-Streaks-Analysis-with-SQL/main/user_streaks_database.sql)
