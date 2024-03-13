# The Project Reivent
# Strategie: Kubernetes
## Backup/Restore Postgres production Databases to/from AWS S3 Bucket

        # Instructions

1- create an image capable of login in postgres and aws

2- create a kubernetes cronjob 

3- backup data from database called s6-user

4- create a folder on aws with your prefer name under the bucket called s6-db-backup 

5-backup data in form of tar file to your folder

6- create a database with your prefer name 

7- Restore your the data under your database
