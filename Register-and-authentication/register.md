# Register
[Site Map](poultry-palace/README.md)

![image](https://github.com/jar-RED/poultry-palace/assets/126373280/ae3dce62-f2eb-474e-8de2-8dfb26b16ac8)



## Register popup
This is used to register and create an account for the user.
### Input
The user shall fill in the credential input.
### Process
* The user shall create his/her username.
* The user shall provide his/her password.
* The user shall tap the “Let’s Go” button.

### Output
The registration is filled and submitted for registration
Leads to the “Login” interface.


### Data Dictionary
| Element ID | Element Text | Element Type | Data Type | Required | Rules? |
|------------|--------------|--------------|-----------|----------|--------|
| Register Header | Register | Header|  |  |  |
| Create username | Username | Text | Text | Yes |  |
| Create password | Password | Text| Text | Yes | Masked |
| Register Button | Let's Go | Button |  |  |  |
| HaveAccountLogin | Do you have an account? Log in | Link |  |  |  |

# Log in
![image](https://github.com/jar-RED/poultry-palace/assets/126373280/c92bad12-720c-472d-b080-9510aa7db78c)

## Login popup
This is used to authenticate the user with the application.
### Input
The user must enter his/her credentials.
### Process
* The user shall enter his/her chosen username.
* The user shall enter his/her chosen password.
* The user shall tap the “Let’s Go” button.

### Output
The user will be logged into the application by the system.
Leads to the “Dashboard” interface.



### Data Dictionary
| Element ID | Element Text | Element Type | Data Type | Required | Rules? |
|------------|--------------|--------------|-----------|----------|--------|
| Login Header | Login | Header|  |  |  |
| LoginUsername | Username | Text | Text | Yes |  |
| LoginPassword | Password | Text| Text | Yes | Masked |
| LoginInvalidUsername | Invalid username and password. | Text |   |  | Hidden |
| LoginForgotPassword | Forgot your password? | Link |  |  | Hidden |
| LoginSignUp | Create new account | Link |  |  |  |
