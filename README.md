# asg01
1. Customer Registration & Login
* Register a new account (email, username, password) – [CREATE]
* Login to the website (authenticate with username and password) – [READ]
* Update account details (change password, username, email address) – [UPDATE]
* Deactivate or delete account (request for account deletion to admin) – [DELETE]

⸻

2. Goals Management
* Create personal goals (e.g., savings, diet, etc.) – [CREATE]
* View all personal goals (list of goals created by the user) – [READ]
* Update personal goals (track progress on goals) – [UPDATE]
* Delete goals (when plans change, goal is no longer relevant, etc.) – [DELETE]

⸻

3. Admin – Manage Users
* Approve or reject new user accounts (accounts by default unapproved) – [UPDATE]
* View all registered users and their saving activity – [READ]
* Delete inactive or policy-violating accounts – [DELETE]
* Remove flagged or inappropriate public content (goals) – [DELETE]

⸻

4. Admin – Manage Goals and Announcements
* Create new goal categories (e.g., Health, Travel, Education) – [CREATE]
* Post system-wide announcements (saving tips, updates, etc.) – [CREATE]
* Monitor saving trends and platform statistics (e.g., most common goals) – [READ]
* Update or delete goal categories or tags – [UPDATE, DELETE]

⸻

5. Goal Progress Tracker
* Set goal milestones (mark specific progress points) – [CREATE, UPDATE]
* Track progress on goals (update saved amount, completion status) – [UPDATE]
* View visual progress indicators (progress bar, graphs) – [READ]
* Display reminder notifications (to remind users of goal deadlines or progress) – [CREATE, READ]

⸻

6. User Profile Management
* Set public or private goals (privacy options for sharing goals) – [CREATE, UPDATE]
* View and update personal profile (view goals, progress, etc.) – [READ, UPDATE]
* View success stories from other users (inspirational or motivational) – [READ]

⸻

Non-Significant Features
* Limit 3 wrong password attempts within 1 minute to prevent brute force attacks – [CREATE]
* Send reminders for unfinished goals (email or app notifications) – [CREATE]
* Automatically log out users after 15 minutes of inactivity – [CREATE]
