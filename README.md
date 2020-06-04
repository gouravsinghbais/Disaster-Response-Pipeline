# Disaster-Response-Pipeline

## Run the model:
1. Clone the repository.
2. Open terminal and move to the cloned directory.
3. Run "python data/process_data.py data/disaster_messages.csv data/disaster_categories.csv data/DisasterResponse.db" on               terminal to create database.
4. Run "python models/train_classifier.py data/DisasterResponse.db models/classifier.pkl" to train the classifier. 
5. Once classifier is trained move to the folder containing run.py and run "python run.py". 
6. Go to http://0.0.0.0:3001/ 
