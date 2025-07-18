# Amazon Product Review Analysis

Amazon is an online selling platform  with lots of consumers buying products ranging from Electronics to household appliances and so on. Amazon has morphed into an internet-based business enterprise that is largely focused on providing e-commerce, cloud computing, digital streaming and artificial intelligence (AI) services. This dataset gives an insight into the product reviews from customers who have used this platform.

### Dataset Cleaning.
  The uncleaned dataset consisted of 16 columns and 1465 rows, of which the product detail had the name, category, discount,and  ratings. The customer engagement had the user review, titles, and content. Each unique product ID had aggregated reviewers' data(User ID and Review ID) in the form of comma-separated values (8 each per cell). 


<img width="698" height="356" alt="Amazon Data Cleaning" src="https://github.com/user-attachments/assets/6d939e30-055d-47b4-b50a-c514341d4533" />

Columns that were unnecessary for the analysis, like Image link, User name etc, were removed. Also using the delimeter(|), the Product category was split into columns and cleaned. 
