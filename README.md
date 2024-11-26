# DAT535_detecting_network_attacks

Load the dataset into the hadoop filesystem:
  hdfs dfs -put train_data.gz /data_serving/train_data.gz
  hdfs dfs -put test_data.gz /data_serving/test_data.gz

Clean the data:
  run all cells in data_cleaning.ipynb

Train the classifiers:
  run all cells in data_serving.ipynb
