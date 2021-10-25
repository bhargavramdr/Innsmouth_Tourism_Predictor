# Innsmouth_Tourism_Predictor

About 92 percent Accurate prediction of the Tourist Density in the regions of Innsmouth. Deployed using django.

## Running the project

- Install the requirements by: `pip install -r requirements.txt`
- Run migrations : `python manage.py migrate`
- Run the server: `python manage.py runserver`

## Here's how the site looks:

![Screenshot (166)](https://user-images.githubusercontent.com/72303641/138700222-f4e72af7-1335-4f69-806c-ba8d71b1332b.png)


## Importing necessary libraries
![image](https://user-images.githubusercontent.com/72303641/138649322-68ceda9f-da8d-414e-93bd-96053d02a5d7.png)

 
## Reading the Data:
![image](https://user-images.githubusercontent.com/72303641/138649376-e13a0b9e-efc1-4685-9a7d-4b9edd4486e5.png)


## Dealing with the missing value
![image](https://user-images.githubusercontent.com/72303641/138649413-7cac5432-beeb-4c76-a05c-cdfaa22ceb82.png)

![image](https://user-images.githubusercontent.com/72303641/138649454-5cb1400b-1147-4d33-8d0f-62d8e8cbd23c.png)

 
## XGBoost Regressor:
![image](https://user-images.githubusercontent.com/72303641/138649485-0b2b9af3-3f8d-4807-a3fc-12e84a4b4ead.png)

## Prediction:

![image](https://user-images.githubusercontent.com/72303641/138649551-53351a56-39bb-405a-b80c-710bca981ca8.png)

**Accuracy of 92 percent is not bad all!**
