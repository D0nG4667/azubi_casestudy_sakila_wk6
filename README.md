### Requirements
You are to connect to a remote database using python code. Properly set up your connection to the database using the database credentials provided below. It is a must to hide sensitive information like password, hostname, username, etc. using environment variables.
Once your setup is done, query the database to answer the following analytical questions by writing an SQL query in your Jupyter notebook and supply the appropriate visualization.

### Questions
1. Determine how much we made in revenue from active and inactive members. Visualize the result as a bar chart.<br>
2. We have 2 staff members, Mike and Jon. Determine the staff member that contributed the most to our revenue in the month of August in 2005. Visualize their percentage contribution as a pie chart.<br>
3. Create a simple line chart showing the monthly rental count of the store. Do you notice any patterns or trends?<br>
4. Create a basic bar chart to show the monthly revenue for the rental store.<br>

# Install needed packages
%pip install sqlalchemy mysqlclient mysql-connector-python python-dotenv

# Summary
#### Store 1:
- May 2005: **2,459.25** rental revenue.
- June 2005: Increases to **4,734.79**.
- July 2005: Peaks at **14,308.66**.
- August 2005: Maintains strong revenue at **11,933.99**.
- September 2005 to January 2006: No recorded revenue, indicating inactivity.
- February 2006: Revenue resumes at **243.10**.

#### Store 2:
- May 2005: **2,364.19** rental revenue.
- June 2005: Increases to **4,895.10**.
- July 2005: Peaks at **14,060.25**.
- August 2005: Maintains strong revenue at **12,136.15**.
- September 2005 to January 2006: No recorded revenue, indicating inactivity.
- February 2006: Revenue resumes at **271.08**.