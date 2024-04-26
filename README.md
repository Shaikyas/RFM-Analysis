# RFM-Analysis
This is my first project on GitHub " RFM Analysis ". My project is used to understand and segment customers based on their buying behavior. here R=Recency, F=Frequence, M=Monetary.   
To deal with data we have to import related lybraries which we are using in this . 
After importing we have to Upload Data set. 
like data=pd.read_csv("rfm_data.csv")
print(data.head())
To know more about dataset use
data.dtypes
import datetime to change the PurchaseDate
Convert 'PurchaseDate' to datetime
Calculateing Frequency
Calculating Monetary Values
#After Calculating rfm values data is looking like this
   CustomerID PurchaseDate  TransactionAmount ProductInformation  OrderID  
Calculating RFM Scores
Converting RFM scores to numeric type value
RMF value Segmentation
RMF Customer Segments
