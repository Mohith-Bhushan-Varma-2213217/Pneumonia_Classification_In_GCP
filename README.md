# Pneumonia_Classification_In_GCP

+ Project ID: - centering-line-406917 

+ Function: - predict

+ Bucket name: - pneumonia_grp

+ Command to Deploy: - gcp>gcloud functions deploy predict --runtime python38 --trigger-http --memory 512 --project centering-line-406917

+ The model, after training, found a home in a Cloud Storage bucket, offering a convenient hub for versioning and easy access. To operationalize predictions, a Cloud Function stepped into the scene, primed to ignite whenever a fresh image landed in the bucket. This nimble function smoothly synchronized its moves with a Flask web application.

+ In the unfolding visual narrative, a sequence of images mirrors the journey through our cloud-deployed project's API responses. Each image harmonizes with a specific API endpoint, capturing the ebb and flow of data and information during interactions with our cloud-powered creation. These responses, akin to a symphony, unveil the system's core functionality, showcasing the harmonious dance between clients and the robust infrastructure perched in the cloud.

+ [Deployment Link](https://us-central1-centering-line-406917.cloudfunctions.net/predict)
