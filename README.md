# SCD1-Implementation-using-HIVE

Hive implementation of slowly changing dimention 1

Implemented a slowly changing dimention type 1 using Hive Sqoop and Sql.

After every run, save the updated data to Hive table in ORC format with Snappy compression.

partition implementation type is based on year ,month ,day 


problem statment : From client we used to get data in single file in csv formate and we need to implement the SCD1
                    **Requirment in details **
                    1) Daily files are recived in csv formate
                    2) Data is uncleared and not formated 
                    3) Flow of data should be matched as per diagram 1.a 
                    
                  **  Required ouput **
                  1) Hive table which contain clear and structured formate
                  2) data should not be redundancy (based on 3 column as per client requirment)
                  
                  
                  
                  
                
                    

