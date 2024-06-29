
# Sales Store Database




## About
An interactive Dashboard to get insights about sales of a company in different areas of North America 
## Dataset 

The dataset is easy to understand and self explainatory each row contains an order having its own unique order id, order date, ship date, ship mode along with customer id and customer name. 

Rest columns provides us the detailed information about the order like what is the segment of the order (is it Corporate order, Home office or Only for consumer) along with some neccesary details like the address (Country, State, City, Region) moreover it contains the order items like Product id, Catergory and sub-Catergory of the Product with its Product name its Price and how much Profit the Store makes from it by selling a particular order of it.

- With the help of this dataset we can analyse 
- Which regions have the most sales/profit 
- Which shipping mode used maximum in delivering the order 
- Which mode of payment used more by the Customer, is it COD/Online/Cards



## DAX Queries Used

to calculate the average shipping average_date

average_date = DATEDIFF(SuperStore_Sales_Dataset[Order Date], SuperStore_Sales_Dataset[Ship Date],DAY)


## Charts Used

1. **Donut Chart:-** 
- To Display Total Profit by Category
- To Display Total Sales by Category

2. **Stacked Bar Chart:-**
- Ship Mode vs Sum of Quantity
- Payment Mode vs Sum of Sales

3. **KPIs**
- No. of Order
- Total Profit
- Total Sales
- Average Ship Days 

4. **Stacked Area Chart**
- Profit by Month and year
- Sales by Month and year

5. **Slicer:**
- Used Region as Slicer to slice the data 
                
