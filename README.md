# Super Store RFM Analysis - Python
Use Python to find out customer segmentations based on RFM scores
## 1. Introduction Business Context
SuperStore Company is a global retail company - Global. So the company has many customers. On the occasion of Christmas and New Year, the Marketing Department wants to run marketing campaigns to thank customers who have supported the company over the past time. As well as exploiting customers who have the potential to become loyal customers.

However, the Marketing Department has not yet been able to group each customer this year because the data set is too large to be processed manually like in previous years, so we asked the Data Analysis Department to assist in implementing a classification problem. Segment each customer to deploy each marketing program suitable for each customer group.

The Marketing Director also suggested using the RFM model, but in the past, when the company was small, the team could calculate and classify it themselves using Excel. Currently, the amount of data is too large, so we want the Data Department to build a flow to deploy Segmentation evaluation through Python programming.

## 2. Analysis 
### 2.1 Get the data
![data](https://github.com/phuonght3001/Super-Store-RFM-Analysis---Python/assets/150796721/66f3931d-8d26-4449-8245-e022b5be813d)
### 2.2 Data preparation
- DataFrame dimension:

![image](https://github.com/phuonght3001/Super-Store-RFM-Analysis---Python/assets/150796721/7bf43ed0-805b-4df8-944d-834b3174cbc3)


- Delete rows when CustomerID is null and rows are duplicated; Convert some columns to the correct data type

DataFrame Dimension after dropping:

![image](https://github.com/phuonght3001/Super-Store-RFM-Analysis---Python/assets/150796721/3337a481-99ff-448f-b393-68ec7a080ed7)

- Caculate "Loss" of orders which is cancelled:

![image](https://github.com/phuonght3001/Super-Store-RFM-Analysis---Python/assets/150796721/fdac237d-ff69-457c-9be3-e5c0890054fb)

- Caculate "Revenue" of orders which is delivered:
  
![image](https://github.com/phuonght3001/Super-Store-RFM-Analysis---Python/assets/150796721/823c5ad4-ad60-4041-8d42-2bfe003c09a4)
### 2.3 Caculate RFM values:
- R Values:

![image](https://github.com/phuonght3001/Super-Store-RFM-Analysis---Python/assets/150796721/f7a4c092-09b8-4af0-93bc-8c5124109bc6)



