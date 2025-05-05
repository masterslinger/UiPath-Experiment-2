# UiPath-Experiment-2
# Date:05/05/2025
# Register No.:212224040346
# Name: Syed Abu Hanifa. L
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
![Screenshot 2025-05-05 092027](https://github.com/user-attachments/assets/564cdc37-66c9-41b1-9a68-6f60a83e3ba2)

![Screenshot 2025-05-05 092140](https://github.com/user-attachments/assets/de93573d-536c-47a0-9ed0-b62a30ecb10b)
