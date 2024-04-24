# 1. Introduction
This page allows administrators to add new users to the system. Admins can enter details about users such as username, display name, phone number, e-mail adress, role and enabled status.

# 2. User Interface
# 2.1 UI Components
Page consists of three containers. In ideal viweing conditions -on a desktop computer or tablet computer-, "Action" container should have the view width of the screen and should be placed in top of the page. "User Table" and "User Form" containers should fill the rest of the page's height and be placed side by side.

* Action Container
  - "New User" button opens an empty "User Form" for adding a new user.
  - A “Hide Disabled Users” checkbox allows filtering out disabled users from the "User Table" container.
  - "Save User" button saves the entered information inside the "User Form" container.
    
* User Table Container
  - Columns include ID, User Name, Email, and Enabled status.
  - Each row represents a user with the details displayed in the respective columns.

* User Form Container
  - Form includes fields such as Username Text Field, Display Name Text Field, Phone Input Field, Email Field, User Roles Selection Dropdown, Enabled Checkbox

# 2.2 UI Behavior
* On Initial Load
  - "User Table" container is populated with existing users.
  - "User Form" container is hidden.

* Adding New User
  - Clicking on "New User" changes display of "User Form" container and it is shown to the user.
  - Admin fills in all required fields.
  - Clicking on “Save User” adds the new user’s info to database, "User Table" container is updated with new user and "User Form" once again gets hidden.
 
* Filtering Disabled Users
  - Clicking the “Hide Disabled Users” Checkbox removes all disabled users from "User Table" container
