# Register and Login
![image](https://github.com/jar-RED/poultry-palace/assets/126373280/13204a0e-f42b-4cec-a3d3-eac1ea1a1d0d)


## Register popup
This is used to register and create an account for the user.
### Input
The user shall fill in the credential input.
### Process
The user shall create his/her username.
The user shall provide his/her password.
The user shall tap the “Let’s Go” button.

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

## Login popup
This is used to authenticate the user with the application.
### Input
The user must enter his/her credentials.
### Process
The user shall enter his/her chosen username.
The user shall enter his/her chosen password.
The user shall tap the “Let’s Go” button.

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
