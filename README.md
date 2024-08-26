# Customer-Exit-EXIT_SAPLRSR0_001

In BW , we often restrict some value at report level with the help of characteristic restrictions in the BEx software. At times though we have to get through a logic to restrict a particular thing. Such things are implemented with the help of customer exit EXIT_SAPLRSR0_001. Where we can write our custom logic in the Include ZXRSAU01. 

## Opening Bex and the query where we want to enhance 

![image](https://github.com/user-attachments/assets/f93106c3-f961-4706-8cba-c267df8db6bc)


Here we will be finding the 'Service level date' as it is the one where we have to do the logic. that the document should not be older than 01.01.2023 in the report. 

So we will be maintaining this raange in a variant and after that we will be using the FM EXIT_SAPLRSR0_001. 
Go to T code se37 and open the source for this particular FM. 

![image](https://github.com/harrycodeswhileworldsleeps/Customer-Exit-EXIT_SAPLRSR0_001/assets/94862735/2d0867ec-b8bf-4253-bf92-a39295b24155)

Then go inside Include. 
Now we have written a logic here in such a way that separately a new report can be written for the customer exit. 
Look into the code for this.

## Result 
![image](https://github.com/harrycodeswhileworldsleeps/Customer-Exit-EXIT_SAPLRSR0_001/assets/94862735/d6386b5a-8297-4a54-a3c6-6ed44251b669)
