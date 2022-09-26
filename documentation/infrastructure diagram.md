
## infrastructure diagram

  
1) Front-end hosted on AWS S3 bucket takes User
login, registration, and post data and sends it
through AWS Elastic Beanstalk

  
  
2)  AWS Elastic Beanstalk API queries AWS RDS
Postgresql database with information provided
by the front-end

3) AWS Elastic Beanstalk sends post data to be
stored inside AWS S3 bucket that the front-end
can display to the User

 4) AWS RDS Postgresql database stores
information about User and sends query results
to the API running on AWS Elastic Beanstalk

  

- AWS S3 bucket

  

- AWS RDS PostgreSQL

  

- AWS Elastic Beanstalk