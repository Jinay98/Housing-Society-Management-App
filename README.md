# Housing-Society-Management-App
A Housing Society Management App built using Django <br/>
# Techstack <br/>
1. Django == 3.0.5 <br/>
2. Python == 3.6 <br/>
3. HTML5 <br/>
4. Javascript <br/>
5. Ajax <br/>
6. CSS <br/>
7. Materialize CSS <br/><br/>

# Screenshots of the features <br/><br/>

## 1.) Login Page: <br/>
A standard login page to sign in the users of the system. It will check both the username along with his corresponding password and will only allow the user to login if both are correct. <br/><br/>
![login](https://user-images.githubusercontent.com/32198451/80204317-457eec00-8646-11ea-83ef-8ba1a11948f9.png)

<br/><br/>

## 2.) Registration Page: <br/><br/>
A standard registration page which takes the Username, First Name, Last Name and Password. The page will ask the user to input the password twice for verification and also ensure that the password is strong by following these rules :<br/>
a.) The password can’t be too similar to your other personal information.<br/>
b.) The password must contain at least 8 characters. <br/>
c.) The password can’t be a commonly used password. <br/>
d.) The password can’t be entirely numeric. <br/>
<br/>
![register](https://user-images.githubusercontent.com/32198451/80204792-20d74400-8647-11ea-9c7f-00605fb96990.png)
<br/><br/>

## 3.) Home Page: <br/><br/>
If the user is a new user then a detailed form is shown at the home page for the user to fill containing details like Designation, Address, Age, Phone No. and Display Picture.<br/>
![home_2](https://user-images.githubusercontent.com/32198451/80204999-85929e80-8647-11ea-9d3c-5b529b584e95.png)
<br/><br/>
If the user has already filled the above form all the information is updated accordingly in the user profile page and the next time he comes on the home page a brief description of the Society along with its image is displayed.<br/>
![home_1](https://user-images.githubusercontent.com/32198451/80205036-96dbab00-8647-11ea-9365-052f51a25ea2.png)
<br/><br/>

## 4.) Add Event Page: <br/><br/>
This page is present to add any important event that is going to take place in the society such as a Birthday Party, Festival Celebration or a Society meeting etc. The user can simply add the event details including the Title, Description, Date, Location of Event, Image of Event etc. and notify other society members to come for the event. <br/>
![add_event](https://user-images.githubusercontent.com/32198451/80205224-df936400-8647-11ea-9e31-bf0cbce26643.png)
<br/><br/>

## 5.) Event Detail Page: <br/><br/>
This page is used to display all the events that are added by the society members in the descending order of date. <br/>
![event_details](https://user-images.githubusercontent.com/32198451/80205266-ede18000-8647-11ea-9e4f-28ace2c1295b.png)
<br/><br/>

## 6.) View Society Members: <br/><br/>
Very often we don't know the people living in our society. Hence this page gives us detailed information about all members living in the society with fields  like name, age, designation and address. <br/>
![society_member_details](https://user-images.githubusercontent.com/32198451/80205418-3731cf80-8648-11ea-9b1d-6dd50ea83100.png)
<br/><br/>

## 7.) Generate Rent Receipt : <br/><br/>
This feature is ONLY for the Super Users of the system such as the Chairman, Treasurer, President, Vice President etc. They can issue rent receipts to all the members of the society by just clicking a button. A PDF is generated in the name of that society member using a third party API named “pdfcrowd”<br/>
### For Users having Admin Privileges : <br/>
![generate_rent_receipt](https://user-images.githubusercontent.com/32198451/80205637-97c10c80-8648-11ea-86d0-52bf16a61ad3.png)
<br/><br/>

### For Normal Users: <br/>
![rent_receipt_2](https://user-images.githubusercontent.com/32198451/80205679-a7d8ec00-8648-11ea-867c-a474810189eb.png)
<br/><br/>

### Rent Receipt: <br/>
![rent_receipt](https://user-images.githubusercontent.com/32198451/80205710-b2938100-8648-11ea-9be1-b642148eb631.png)
<br/><br/>

## 8.) View Profile Details: <br/><br/>
The user can see his profile details and also see if he has paid the monthly rent 
 <br/>
![profile](https://user-images.githubusercontent.com/32198451/80205916-18800880-8649-11ea-9c58-3718c2449359.png)
<br/><br/>


## 9.) Edit Profile Page: <br/><br/>
The user can edit his profile by changing his Email First Name and Last Name
 <br/>
![edit_profile](https://user-images.githubusercontent.com/32198451/80205941-22097080-8649-11ea-8d7c-b0bbb5d9dd06.png)
<br/><br/>

## 10.) Change Password Page: <br/><br/>
The user can change his password by entering his old password and the new password
 <br/>
![change_password](https://user-images.githubusercontent.com/32198451/80206122-6f85dd80-8649-11ea-808c-8d3008b136c4.png)
<br/><br/>


## 11.) Logout Page: <br/><br/>
Landing Page when the user decides to log out
 <br/>
![logout](https://user-images.githubusercontent.com/32198451/80206141-7a407280-8649-11ea-9fd6-fa4827142f64.png)
<br/><br/>



