
# Pre-Ingestion and Ingestion 


# Pre-ingestion 

The pre-ingestion is used to perform similarity (image semantic similarity) between a group of items

The pre-ingestion is used to perform tags extraction of an items (via image or text)

To do such machine learing tasks we use transfer-learning (fine-tuning) of pre-trained models where 500 training items are enougth. 

For example we could use the transformer BERT. 


# Ingestion 

Could be one shot or recursive.

We might use [CDC](https://docs.microsoft.com/en-us/sql/relational-databases/track-changes/about-change-data-capture-sql-server?view=sql-server-ver15) 