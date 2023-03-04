Download [link](https://drive.google.com/file/d/1t4O8UC4vGs1OuIo9H2AprB7OPrMEVZO7/view?usp=sharing) for the database

The `train.csv` and `val.csv` files contain the training and dev 
data for this assignment. Each query is associated with a db_id.

The details of the corresponding db_id are contained in the 
tables.json file. The table_names entry denotes the names of all
tables. The column_names have an (table_index, column_name) tuple
for each column which links them to the appropriate table. The
foreign_keys entry indicates the column IDs which form a foreign 
key. Similarly the primary_keys entry denotes the primary key 
for each table. Rest of the entries are self-explanatory. 

To evaluate your inferences, enter the evaluator directory and 
use the following command:

`python evaluation.py --gold <GOLD_FILE> --pred <PRED_FILE> --db ../database/ --table ../tables.json --etype all`

An example of a <GOLD_FILE> and <PRED_FILE> is given in the 
evaluator folder.

