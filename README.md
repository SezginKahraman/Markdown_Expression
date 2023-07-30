# Navbar

- New User Button -> When Click, a modal will open in the right side, the informations of the user is going to be given. In the upper right corner of the navbar, 'Save User' button will be placed. When it is clicked, the creating proccess will be started.
- Hide Disabled User -> When clicked, give the function which calls the user as the parameter active. Show only the active users.
- Save User Button -> Saves the users information. If user exists, updates its informations, else creates new one.

# Body

- ## Modal 1 -> Table
  - ### Thead
    - There will be 4 column which are, Id (primary key), user name, email, enabled. -> Id parameter is users unique id, not row's count. email is users email, user name is user's user name and enabled is user's status.
  - ### TBody
    - Display the informations that related with the columns.
- ## Modal 2 -> Form
  - ### Form Title -> New User
  - ### Form Body
    - User Name -> in the size of Bootstratp, form - control class.
    - Display Name - in the size form - control.
    - Phone - in the size form - control
    - email - in the size form - control
    - User Roles - a dropdown list.
      - Guest
      - Admin
      - SuperAdmin
    - Enabled - a check box button.
