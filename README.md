<h1>Bank Fraudulent Transaction Detection</h1>
<h3>Overview</h3
<p>This repository contains a dataset of bank transactions, which includes various details about each transaction such as transaction ID, sender and receiver account IDs, transaction amount, type, timestamp, status, fraud flag, geolocation, device used, network slice ID, latency, slice bandwidth, and PIN code. The primary goal of this project is to detect fraudulent transactions using machine learning techniques.</p>

Dataset
The dataset bank transaction_data.csv includes the following columns:

Transaction ID: Unique identifier for each transaction.
Sender Account ID: Unique identifier for the sender's account.
Receiver Account ID: Unique identifier for the receiver's account.
Transaction Amount: The amount of money involved in the transaction.
Transaction Type: Type of transaction (e.g., Deposit, Withdrawal, Transfer).
Timestamp: Date and time when the transaction occurred.
Transaction Status: Status of the transaction (e.g., Success, Failed).
Fraud Flag: Indicates whether the transaction is flagged as fraudulent (True/False).
Geolocation (Latitude/Longitude): Geographical location where the transaction was initiated.
Device Used: Type of device used for the transaction (e.g., Desktop, Mobile).
Network Slice ID: Identifier for the network slice used during the transaction.
Latency (ms): Network latency in milliseconds.
Slice Bandwidth (Mbps): Bandwidth of the network slice in megabits per second.
PIN Code: PIN code associated with the transaction.

Project Structure
data/: Contains the dataset file bank transaction_data.csv.

Data Preprocessing
Handle missing values.
Encode categorical variables.
Normalize numerical features.

1. Import the Dataset
Open Power BI Desktop.
Click on Home > Get Data > Text/CSV.
Select the bank transaction_data.csv file and click Open.
Click Load to import the data into Power BI.
2. Data Preparation
Once the data is loaded, you can see it in the Fields pane.
Click on Transform Data to open the Power Query Editor.
In the Power Query Editor, you can perform various data cleaning and transformation tasks such as:
Removing unnecessary columns.
Handling missing values.
Changing data types.
Filtering rows based on specific criteria.
3. Create Relationships (if needed)
If you have multiple tables and need to create relationships between them:

Go to the Model view.
Drag and drop fields to create relationships between tables.
4. Create Visualizations
Go to the Report view.
Use the Visualizations pane to create various charts and graphs. Here are some examples:
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

