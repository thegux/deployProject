# Pipeline Documentation
The pipeline was constructed using Circle CI. It consists of simple steps, such as: installing dependencies, building steps and deployment steps. To view all of the mentioned steps, please check the images listed below.

## Environment variables
Please Configure the following environment variables in your circle CI project:

- POSTGRES_USERNAME
- POSTGRES_PASSWORD
- POSTGRES_DBPOSTGRES_DB
- PORT
- POSTGRES_HOST
- AWS_REGION
- AWS_PROFILE
- AWS_BUCKET
- URL
- JWT_SECRET
- AWS_ACCESS_KEY_ID
- AWS_SECRET_ACCESS_KEY
- AWS_ACCESS_KEY
- AWS_REGION

## CIRLECI
<img width="816" alt="image" src="https://user-images.githubusercontent.com/60764149/159112674-d3c873ac-544f-4a3a-9f6f-31db9c442c98.png">
<img width="798" alt="image" src="https://user-images.githubusercontent.com/60764149/159111795-80291643-b1d7-4da3-ad01-9bf5850d663f.png">

### Environment Config Screenshot
<img width="953" alt="image" src="https://user-images.githubusercontent.com/60764149/159112713-c9fe0aea-eabd-40d1-9a25-cd3f307335d0.png">

### Pipeline's Overview Diagram
![AWS (2019) horizontal framework](https://user-images.githubusercontent.com/60764149/159111993-8b97c3cc-85bf-4516-9b1c-2c7d8ee78764.jpeg)


#### Pipeline note
Please note that only changes applied to master will be deployed.
<img width="648" alt="image" src="https://user-images.githubusercontent.com/60764149/159121589-3f1f5e71-9948-4bfe-b550-0dbf834c8b8d.png">