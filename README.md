# RetailSalesAnalysis

On the terminal:

Command for ProductSales: 
bin/spark-submit --class com.prerna.retail.ProductSales ../jars_file/productjar.jar ../data/Retail_Sample_Data_Set.txt ret-out-prod-01

Command for StoreSales:
bin/spark-submit --class com.prerna.retail.StoreSales ../jars_file/salesjar.jar ../data/Retail_Sample_Data_Set.txt ret-out-store-01

Command for TotalSales:
bin/spark-submit --class com.prerna.retail.TotalSales ../jars_file/totalsalesjar.jar ../data/Retail_Sample_Data_Set.txt ret-out-total-01
