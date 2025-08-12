# Line-Productivity-Excel
Excel,  Line efficiency,   Line downtime 

**<ins>Introduction<ins/>**

The data was collected from 8/29/2024 to 9/3/2024 (6 days).

This analysis examines the production line downtime across various operators to assess overall efficiency and identify key sources of error impacting productivity. By evaluating downtime and frequent error types, such as machine adjustments, we can provide insights into targeted improvements. The findings serve as the foundation for enhancing manufacturing line productivity, suggesting adjustments such as scheduled maintenance and production oversight which could help minimize disruptions and elevate efficiency.

The project is made with line managers in mind providing them with a detailed breakdown of production line performance, operator efficiency, and recurring downtime issues. 

**<ins>Processing the data before Analysis</ins>**

1. Unpvoting the Line donwtime and factor table.
  
   The factor columns are spread with null values in most rows meaning we can unpivot them to a single column for better viewing and esy table joining. 
   
2. Joining the four tables using power query.

   The tables have common columns that can be used to merge them together into a final table providing a comprehensive view of the data.

**<ins>What the project is answering</ins>**

1. Calculate the line efficiency
2. identify main downtime factors
3. calculate downtime by operator and factor

**<ins>Insights Derived<ins/>**

1. There is a total of 6 days when the data was collected. Through the 6 days, 61 errors occured with 32 of them caused by operators errors.
2. The overall efficiency of the production line is 80.27% with operators Charlie and Dee perfoming with higher efficiency than the overall efficiency.
3. Downtime occurs mainly as a result of machine adjustment, machine failure, and inventory shortage errors. This suggests opprtunities for line improvement in preventive or scheduled maintenance, better inventory planning, and equipment upgrades which could help reduce downtime and improve overall line productivity.

4. Charlie and Dee have the highest downtime minutes. The distribution of downtime suggests that some operators face specific recurring challenges such as machine adjustment for Charlie and Dennis. This shows that tailored interventions including improved production floor oversight should be implemented to reduce error recurrence.
5. As the batch volume increases the number of erros increase. This suggests that increased workload as a result of increased production volumes may strain the operator or the processes, potentially leading to increased errors as opertors try to handle a large batch volume.


**<ins>Tool Used<ins/>**

Microsoft Excel





