# CS643_Wine_Prediction
Wine Quality Prediction

Goal: The purpose of this individual assignment is to learn how to develop parallel machine learning (ML) applications in Amazon AWS cloud platform. Specifically, you will learn: (1) how to use Apache Spark to train an ML model in parallel on multiple EC2 instances; (2) how to use Spark’s MLlib to develop and use an ML model in the cloud; (3) How to use Docker to create a container for your ML model to simplify model deployment.


#Readme File




#Docker Image Link



#Before Running Program
1) Input file should be under data/ and have name as TestDataset.csv
2) Input file must have save format as of TrainingDataset.csv and ValidationDataset.csv. Column names in double quotes with exact name number of column with same names and separator ';'



#Docker Commands

docker pull pratik1596/CS643_Wine_Prediction

docker run -v [fullLocalPath of TestDataset.csv: data/TestDataset.csv ] pratik1596/CS643_Wine_Prediction

