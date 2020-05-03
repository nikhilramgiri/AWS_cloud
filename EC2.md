**AWS-EC2 (Elastic Compute Cloud)**
----------
**How to Create an Instance**


*STEPS-*

1.Go to the service and click on EC2 (Click on launch instance)

![instance](https://user-images.githubusercontent.com/63799117/80917384-21c15180-8d7c-11ea-8746-071397dcb012.PNG)
--------------
3. Click on launch instance and you will get the list of OS
![OS](https://user-images.githubusercontent.com/63799117/80917502-eecb8d80-8d7c-11ea-8638-068cfe582076.PNG)
-----------
4.Create an instance of any OS eg,Amazon Linux

5.Choose Ram and Processor as per your requirement
![ram-rom](https://user-images.githubusercontent.com/63799117/80917591-9648c000-8d7d-11ea-8de7-bf84e0075b9b.PNG)
--------
6.In configure instance dont make any changes

7.Create Storage as per your requirement
![storage](https://user-images.githubusercontent.com/63799117/80917703-71a11800-8d7e-11ea-9fcf-e0e562392dc5.PNG)
---------
8.In (Add tags) add Name (key) and give name to your instance eg. kamlesh-021

9.In Configure security group give Seurity group name and description(Optional)

10.Review and Launch the Instance

11.Download the new key pair so that you can launch the instance
![key-pair](https://user-images.githubusercontent.com/63799117/80918020-5fc07480-8d80-11ea-830f-99042dd70051.PNG)
-------
12.You will get the instance running and also copy the pubic ip address
![public-ip](https://user-images.githubusercontent.com/63799117/80918137-f7be5e00-8d80-11ea-9864-98141e65cd10.PNG)
---------
13.Download [Mobaxterm](https://mobaxterm.mobatek.net/download.html)

14.Open Mobaxterm and select New Section
  * Paste public ip and give user name
    * Amazon linux (ec2-user)
    * Windows (Administrator)
    * Ubuntu (ubuntu)

![settings](https://user-images.githubusercontent.com/63799117/80918427-7962bb80-8d82-11ea-9592-bd1f924f890e.PNG)
---------
15.In Advance setting Upload your key pair
![advance-setting](https://user-images.githubusercontent.com/63799117/80918534-263d3880-8d83-11ea-8748-3797c835621e.PNG)
--------
16.Click Ok and your Instance is created
![Instance-Created](https://user-images.githubusercontent.com/63799117/80918647-aa8fbb80-8d83-11ea-8af4-9e0f141aa549.PNG)



