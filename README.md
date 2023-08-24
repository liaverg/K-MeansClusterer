# K-MeansClusterer
 K-MeansClusterer is a clustering program based on the k-means algorithm.
 The project was developed for the [MYE035-Computational Intelligence](https://www.cse.uoi.gr/course/computational-intelligence/?lang=en) course [@cse.uoi.gr](https://www.cs.uoi.gr/)
 
  ## How to Run
  ### Windows Host
  1. Compile with: `javac -cp ".;jars/*" main/*.java`
  2. Create a new dataset with: `java -cp ".;jars/*" main/DatasetGenerator` - This is not necessary
  3. Run java application with: 
  `java -cp ".;jars/*" main/Kmeans <dataset_name.txt> <number_of_clusters> <number_of_runs>`  
  example: `java -cp ".;jars/*" main/Kmeans dataset.txt 9 20`

  ### Linux Host
  1. Compile with: `javac -cp ".:jars/*" main/*.java`
  2. Create a new dataset with: `java -cp ".:jars/*" main/DatasetGenerator` - This is not necessary
  3. Run java application with: `java -cp ".:jars/*" main/Kmeans <dataset_name.txt> <number_of_clusters> <number_of_runs>`  
  example: `java -cp ".:jars/*" main/Kmeans dataset.txt 9 20`