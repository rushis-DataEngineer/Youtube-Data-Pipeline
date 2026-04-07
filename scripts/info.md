Bronze Bucket - yt-datapipeline-bronze-ap-south-1
Silver Bucket - yt-datapipeline-silver-ap-south-1
Gold Bucket - yt-datapipeline-gold-ap-south-1

Scripts Bucket - yt-datapipeline-script-ap-south-1

SNS ARN - arn:aws:sns:ap-south-1:338764933231:yt-dp-alerts:f7d0ff21-3c37-4618-a4ec-35a04c7df94e

Glue Bronze DB - yt-dp-glue-bronze
Glue Silver DB - yt-dp-glue-silver
Glue Gold DB - yt-dp-glue-gold

--bronze_database yt-dp-glue-bronze 
--bronze_table raw_statistics 
--silver_bucket yt-datapipeline-silver-ap-south-1 
--silver_database yt-dp-glue-silver 
--silver_table clean_reference_data

--silver_database yt-dp-glue-silver 
--gold_bucket yt-datapipeline-gold-ap-south-1 
--gold_database yt-dp-glue-gold