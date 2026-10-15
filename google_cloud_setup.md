## Creating Google Cloud Credentials
So that DVC is able to save datasets to google drive


Select or Create a Project:
![alt text](assets/images/image-13.png)
- then click on api and services
![alt text](assets/images/image-14.png)
- then click on library and search for `Google Drive API`
![alt text](assets/images/image-15.png)
- after selecting google drive api, click enable, then click on manage
![alt text](assets/images/image-16.png)
![alt text](assets/images/image-12.png)
- click on create credentials
![alt text](assets/images/image-17.png)
- select user and click next

![alt text](assets/images/image-19.png)
![alt text](assets/images/image-18.png)

- Create the Client ID and Client Secret by selecting Desktop app for the Application type(Under OAuth Client ID)
- add the Client ID and Client Secret into the dvc-setup project directory by using:
```
dvc remote modify --local storage gdrive_client_id "YOUR_CLIENT_ID"
```

```
dvc remote modify --local storage gdrive_client_secret "YOUR_CLIENT_SECRET"
```

![alt text](assets/images/image-20.png)
- go to Google Auth Platform and click on Audience to add your gmail account as an authorized Test users
![alt text](assets/images/image-21.png)
![alt text](assets/images/image-22.png)
![alt text](assets/images/image-23.png)
![alt text](assets/images/image-24.png)
![alt text](assets/images/image-25.png)
![alt text](assets/images/image-26.png)
![alt text](assets/images/image-27.png)
![alt text](assets/images/image-28.png)