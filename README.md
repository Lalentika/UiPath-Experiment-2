# UiPath-Experiment-2
# Date:05.05.2025
# Register No.:212224220052
# Name: Lalentika Twisha M
# AIM:
Get input of name from user and if name is "RAM", Display message as "Welcome Mr. Ramachandran" otherwise "Welcome " followed by Given name.  When using Switch case, use different message for every input it gets.  
# Requirements:
1.) Laptop

2.) Internet

3.) UiPath Studio
# Process:
1. Create a New Process in UiPath Studio
Name it something like SwitchCaseWelcome.

2. Add a Sequence
Drag a Sequence to the workflow.

3. Add Input Dialog Activity
Label: "Enter your name"

Store the result in a variable, e.g., userName of type String.

4. Add Switch Activity
Expression: userName.ToUpper (ensures case insensitivity)

Cases:
Case "RAM"
→ Message Box: "Welcome Mr. Ramachandran"

Case "JOHN"
→ Message Box: "Welcome Mr. Johnathan"

Case "VIJAY"
→ Message Box: "Welcome Mr. Vijay Kumar"

Default Case
→ Message Box: "Welcome " + userName


# Workflow Process Image:

![image](https://github.com/user-attachments/assets/7cd1e8a0-2403-40c0-96d4-f3ccbf615e66)


![image](https://github.com/user-attachments/assets/e52bf699-c99f-435d-a7ee-2efffe0caf82)

