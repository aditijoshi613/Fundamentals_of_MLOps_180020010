Link to the repo: https://github.com/aditijoshi613/MLOps_Assignment 

List of commands (in sequence) that were used to accomplish the tasks mentioned in Part 1:
   1. git clone https://github.com/aditijoshi613/MLOps_Assignment
    
   2. cd MLOps_Assignment
    
   3. git init
    
   4. git remote add origin https://github.com/aditijoshi613/MLOps_Assignment
    
   5. git branch -M main
    
   6. dvc init
    
   7. mkdir data
    
   8. cd ../
    
   9. mkdir external_cache
    
   10. cd MLOps_Assignment
    
   11. dvc cache dir C:\Users\user\external_cache
    
   12. dvc add data/creditcard.csv
    
   13. git add data/creditcard.csv.dvc data/.gitignore
    
   14. git commit -m "Add raw data"
    
   15. dvc remote add -d storage s3://mlopsa2/datastore
    
   16. git add .dvc/config
    
   17. git commit -m "Configure remote storage"
    
   18. dvc push
    
   19. git push origin main
    
     
Values of Accuracy & Weighted F1 Score obtained from both the experiments conducted in Part 2

Screenshot of S3 bucket, after completion of Part 2
![image](https://user-images.githubusercontent.com/64677521/126045893-d696627d-d519-4584-a02e-2b0c6496edcd.png)
![image](https://user-images.githubusercontent.com/64677521/126045902-d9651850-ec1f-4d99-b61d-90dbe3b27028.png)

