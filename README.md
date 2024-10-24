## Image Labels Generator using Amazon Rekognition

This project demonstrates how to build an image labeling tool powered by Amazon Rekognition. Once complete, the tool will automatically recognize and label objects within an image. For example, if you upload a picture of a cat, Amazon Rekognition will detect it and label the image accordingly.




<img width="603" alt="Screenshot 2024-10-24 at 13 34 10" src="https://github.com/user-attachments/assets/c541945a-95b6-43dc-983f-6626b7e3b4e1">
<img width="246" alt="Screenshot 2024-10-24 at 13 34 20" src="https://github.com/user-attachments/assets/956299cc-b663-4aee-bf7b-79264ac15f59">


### Steps Covered 👩‍💻
<img width="692" alt="Screenshot 2024-10-24 at 12 54 20" src="https://github.com/user-attachments/assets/0ca5044f-a0a2-443c-b61b-fefe45df3c6c">

- Setting up an Amazon S3 bucket
- Uploading images to S3
- Installing and configuring the AWS Command Line Interface (CLI)
- Importing necessary libraries
- Writing a `detect_labels` function to process images
- Creating a `main` function to run the program
- Running the Python script

### Services Used 🛠
- **Amazon S3**: For storing the images used in the labeling process.
- **Amazon Rekognition**: For analyzing and generating labels for the uploaded images.
- **AWS CLI**: For interacting with AWS services through the command line.
