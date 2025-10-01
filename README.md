# RPA-8-Basic-web-automation-Fill-a-web-form
## NAME:DHARUNYADEVI S
## REGISTER NUMBER:212223220018
## AIM:
To create a UiPath workflow that automates the process of filling out a basic contact form on a website and submits the form using Web Automation techniques.

## ALGORITHM:
### Step 1: 
Launch the Browser Open UiPath Studio and create a new project called WebFormAutomation.
Drag and drop the Use Application/Browser activity.
Indicate the browser window or enter the form URL manually in the Application Path:
https://form.jotform.com/242550815060449

### Step 2:
Fill Form Fields Inside the Use Application/Browser, add multiple Type Into activities for each field.

### Example:

Field Type Into Value First Name "DHARUNYADEVI", Last Name "S",
Email "dharunyadevi2006@gmail.com", Message "Welcome to the world of robotic process automation".
Use Click Before Typing and Activate options in Properties for accuracy.

### Step 3: 
Select Dropdown (Optional) Use the Select Item activity to choose a state or country from a dropdown if present.

### Step 4: 
Submit the Form Use a Click activity to click the Submit or Send button on the form.

### Step 5: 
Add Delay (Optional) Add a Delay activity if the form takes time to load or submit.

## PROGRAM:

<img width="1920" height="1080" alt="Screenshot (128)" src="https://github.com/user-attachments/assets/2f9ff179-2948-4d05-ba17-a6ba83b439d8" />

<img width="1920" height="1080" alt="Screenshot (129)" src="https://github.com/user-attachments/assets/ad63b954-d893-42dc-a9ee-f18982255be9" />

<img width="1920" height="1080" alt="Screenshot (130)" src="https://github.com/user-attachments/assets/30a57ac6-975d-4bda-b6ec-216e20493a34" />

## OUTPUT:

<img width="1920" height="1080" alt="Screenshot (131)" src="https://github.com/user-attachments/assets/57092276-9996-45ae-a3b5-3d1d9a0635f3" />


## RESULT:
UiPath successfully automates form-filling tasks in a browser and submits a web-based contact form using Web Automation techniques.
