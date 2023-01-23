# transaction-reward
Spring Boot based Rest application for transaction-reward 
Steps to run
  1. Build using maven
  2. Go to target folder
  3. java -jar <jar-file>
  
Given n Number of transactions for  x customers. We need to generate reward points for each customer and combined based on the end point called.
/transactions - this endpoint gives all the transactions.
/rewards - this end point gives total reward points of all customers for last 3 months
/rewards/{customer-id} - this end point gives reward points of that particular customer for last 3 months
  
Following API's are avilable 
  1. api/rewards
  2. api/rewards/{customer-id}
  3. api/transactions 
