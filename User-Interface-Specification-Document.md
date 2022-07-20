# User Interface Specification Document
User Interface Specification Document

# Introduction
This document will be used by Software developers who will develop this user interface. 

## Totaly Screen
Total screen include 3 different section.

![All_Screen](https://user-images.githubusercontent.com/53150892/179973393-ef37ea52-ca61-4a25-bf44-389c40c3eaae.PNG)

This screen include 3 different section. These are; <br>
#### 1)Top Bar <br>

   1.1) New Users Button <br>
   1.2) Hide Disabled User Checkbox <br>
   1.3) Save User Button <br>
  
#### 2) User Information <br>
   2.1) Sorting by ID button<br>
   2.2) Sorting by User Name button <br>
   2.3) Sorting by Email button <br>
   2.4) Sorting by Enabled button <br>
  
#### 3) New User Register  <br>
   3.1) Username Textbox <br>
   3.2) Display Name Textbox <br>
   3.3) Phone Textbox <br>
   3.4) Email Textbox <br>
   3.5) User Role Menu <br>
   3.6) User Status Checkbox <br>
   
  
## 1)Top Bar
-Table divided into 3 columns

![UI_1_](https://user-images.githubusercontent.com/53150892/179984982-503048b6-ae96-48e9-a212-c0ac6d337e4f.PNG)

##### 1.1)  New User Button
- Action: The new user button is pressed and the new user add panel is opened and the necessary    information is entered into the panel.
- Button color to be Blue
- Butter shape to be Rectangle  

##### 1.2) Hide Disabled User Checkbox
- Action: Hides all users from the user list that do not have the enabled check box checked (enabled != true)
- Check Box: Blue color, with white colored ✓ (tick) symbol inside, shape of box should be square

#### 1.3) Save User Button
- Action: Action: Pressing this saves the new user entered in the new user prompt that appears after pressing the new user button in the header
 This button saves the user data written on the screen and sends it to the database.
- Light blue colored button, same size as new user button 
  
## 2) User Information
- Table divided into 4 columns.
- Table to display the list and whitespace below until the end of the screen.

![UI_2_](https://user-images.githubusercontent.com/53150892/180003914-0fe391a2-cf2a-404f-ac04-ae67d394469c.PNG)

##### 2.1) Sorting by ID button
- By pressing this button, the IDs are filtered from large to small or large to small.
- Symbols are 'solid up arrow head' on the left and 'Solid Filter Icon' on the right 

##### 2.2) Sorting by User Name button 
- This button sorts by User Name. User Name is string variable. It sorts alphabetically. (A-Z or Z-A)
- Symbols are 'solid up arrow head, solid down arrow head (up arrow head above the down arrow head)' on the left and 'Solid Filter Icon' on the right. 
- 
##### 2.3) Sorting by Email button 
- This button sorts by Email. Email is string variable. It sorts alphabetically. (A-Z or Z-A).
- Symbols are 'solid up arrow head, solid down arrow head (up arrow head above the down arrow head)' on the left and 'Solid Filter Icon' on the right. 

##### 2.4) Sorting by Enabled button
- This button sorts by User Status. User Status is boolean variable. Boolean working principle is true or false. So it sorts enabled to disabled or disabled to enabled.
- Symbols are 'solid up arrow head, solid down arrow head (up arrow head above the down arrow head)' on the left and 'Solid Filter Icon' on the right. 


## 3) New User Register
- Table divided into 6 columns.
- This opens on the right half of the body when the new user button in the header is pressed.
![UI_3_](https://user-images.githubusercontent.com/53150892/180003876-ec59bf6d-e64d-45cd-afa1-019ecdeba7e1.PNG)


##### 3.1) Username Textbox 
- Action:The username of the user to be registered is entered here.
- Bold and black text as shown here
-
##### 3.2) Display Name Textbox 
- Action:The phone number of the user to be registered is entered here.
-
-
##### 3.3) Phone Textbox 
- Action:The phone number of the user to be registered is entered here.
-
-
##### 3.4) Email Textbox 
- Action:The email of the user to be registered is entered here.
-
-
##### 3.5) User Role Menu 
- Action:User roles are divided into three parts 1-guests (can only see their own information) 2-Admin (Can see, edit but not delete all users) 3-Super Admin (Can do all operations)
-This is continued by selecting the required roles.
-
##### 3.6) User Status Checkbox 
- Action:If the user is an active user, then this is marked. After all the necessary boxes are filled in, click the save user button and the page is refreshed. The new user switches to the user list.
- In the Username, display name, phone, and email options, there is an empty white rectangular box approximately slightly larger than the label text, with a light grayish-white border around each box. When clicked, a black cursor appears in each box where the user can type the required information.
- The user roles label also has a rectangular box in front of it with all the same specifications as above but has a gray colored text in it that is: 'Select user roles' (without the quotes), clicking the box takes this text away and shows a drop down menu box.

