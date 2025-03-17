<h1>Bank Fraudulent Transaction Detection</h1>
<h3>Overview</h3
<p>This repository contains a dataset of bank transactions, which includes various details about each transaction such as transaction ID, sender and receiver account IDs, transaction amount, type, timestamp, status, fraud flag, geolocation, device used, network slice ID, latency, slice bandwidth, and PIN code. The primary goal of this project is to detect fraudulent transactions using machine learning techniques.</p>

<h3>Dataset</h3>
<ul>The dataset bank transaction_data.csv includes the following columns:

<li>Transaction ID: Unique identifier for each transaction.</li>
<li>Sender Account ID: Unique identifier for the sender's account.</li>
<li>Receiver Account ID: Unique identifier for the receiver's account.</li>
<li>Transaction Amount: The amount of money involved in the transaction.</li>
<li>Transaction Type: Type of transaction (e.g., Deposit, Withdrawal, Transfer).</li>
<li>Timestamp: Date and time when the transaction occurred.</li>
<li>Transaction Status: Status of the transaction (e.g., Success, Failed).</li>
<li>Fraud Flag: Indicates whether the transaction is flagged as fraudulent (True/False).</li>
<li>Geolocation (Latitude/Longitude): Geographical location where the transaction was initiated.</li>
<li>Device Used: Type of device used for the transaction (e.g., Desktop, Mobile).</li>
<li>Network Slice ID: Identifier for the network slice used during the transaction.</li>
<li>Latency (ms): Network latency in milliseconds.</li>
<li>Slice Bandwidth (Mbps): The bandwidth of the network slice in megabits per second.</li>
<li>PIN Code: PIN code associated with the transaction.</li>
</ul>

<h3>Data Preprocessing</h3>
<ul>
<li>Handle missing values.</li>
<li>Encode categorical variables.</li>
<li>Normalize numerical features.</li>
</ul>
<ol>
<li> Import the Dataset</li>
<li> Open Power BI Desktop.</li>
Click on Home > Get Data > Text/CSV.
Select the bank transaction_data.csv file and click Open.
Click Load to import the data into Power BI.
<li> <em>Data Preparation</em>em></li>
Once the data is loaded, you can see it in the Fields pane.
<em>Click on Transform Data to open the Power Query Editor.</em>
In the Power Query Editor, you can perform various data cleaning and transformation tasks such as:
<em>Removing unnecessary columns.</em>
<em>Handling missing values.</em>
<em>Changing data types.</em>
<em>Filtering rows based on specific criteria.</em>
<li> Create Relationships (if needed)</li>
If you have multiple tables and need to create relationships between them:

Go to the Model view.
Drag and drop fields to create relationships between tables.
<li>4. Create Visualizations</li>
Go to the Report view.
Use the Visualizations pane to create various charts and graphs. Here are some examples:</ol>
Fraudulent Transactions Analysis
Visualization Type: Bar Chart
Steps:
Select the Fraud Flag field.
Choose the Bar Chart visualization.
Add Transaction Amount to the values.
Filter the data to show only fraudulent transactions.
Transaction Amount Distribution
Visualization Type: Histogram
Steps:
Select the Transaction Amount field.
Choose the Histogram visualization.
Adjust the bins and formatting as needed.
Transaction Types Breakdown
Visualization Type: Pie Chart
Steps:
Select the Transaction Type field.
Choose the Pie Chart visualization.
Add Transaction Amount to the values.
Geolocation Analysis
Visualization Type: Map
Steps:
Select the Geolocation (Latitude/Longitude) field.
Choose the Map visualization.
Add Transaction Amount to the values.
5. Create Dashboards
Combine multiple visualizations into a single dashboard.
Use slicers to filter data dynamically.
Add titles, labels, and other formatting elements to make the dashboard more informative and visually appealing.
6. Publish and Share
Save your Power BI report.
Click on Publish to upload the report to the Power BI service.
Share the report with others by providing access through the Power BI service.
Example Visualizations
Here are some example visualizations you can create:

Fraudulent Transactions Analysis
!Fraudulent Transactions Analysis

Transaction Amount Distribution
!Transaction Amount Distribution

Transaction Types Breakdown
!Transaction Types Breakdown

Geolocation Analysis
!Geolocation Analysis

