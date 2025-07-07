# Admission_Enquiry_Form
## Date:07.07.2025

## Objective:
To design a simple Admission Enquiry Form using basic HTML that collects student details such as name, contact, program of interest, and a message for further communication.

## Tasks:
#### 1. Set Up the HTML Structure:
Use ```<!DOCTYPE html>```, ```<html>```, ```<head>```, and ```<body>``` tags to define the document structure.
Set the ```<title>``` as "Admission Enquiry Form".

#### 2. Add a Page Heading:
Use ```<h1>``` to title the page as “Admission Enquiry”.

#### 3. Create the Form Layout:
Use the ```<form>``` tag to wrap all input elements. Set method="post" for structure.

#### 4. Add Input Fields:
Include the following fields using appropriate HTML elements:

Full Name

Email Address

Phone Number 

Program of Interest 

Message

#### 5. Add Submit and Reset Buttons:
Use submit and reset at the bottom of the form.

#### 6. Use HTML-only:
No CSS or JavaScript is to be included. Focus on structure and accessibility.

## HTML Code:
```
<html lang="en">
    <head>
        <title> Saveetha Engineering College-Admission Enquiry</title>
    </head>
    <body>
        <h1>Admission Enquiry Form</h1>
        <form>
            <label>Full Name:</label><br>
            <input type="text"><br>

           <label>Email Address:</label><br>
           <input type="email"><br>

           <label>Mobile Number:</label><br>
           <input type="mobile"><br>

           <label>Gender</label><br>
           <input type="radio"   value="Male">
           <label>Male</label><br>
           <input type="radio"   value="female">
           <label>Female</label><br>
           <input type="radio"  value="other">
           <label >Other</label><br>
           <label>DOB:</label>
           <input type="date"><br>

           <label for="department">Department:</label><br>
           <select id="department"name="department">
                <option value="">Select Department</option>
                <option value="CSE">CSE</option>
                <option value="IT">IT</option>
                <option value="AIDS">AIDS</option>
                <option value="ECE">ECE</option>
                <option value="Mech">Mech</option>
                </select><br>


                <label for="qualification">Academic qualification:</label><br>
                <textarea  rows="3" cols="40"></textarea><br>
                
                <label for="address">Address:</label><br>
                <textarea  rows="3" cols="40"></textarea><br><br>

                <input type="submit"value="Submit">
        </form>
    </body>
</html>
```
## Output:
![Screenshot 2025-07-07 140358](https://github.com/user-attachments/assets/7a015493-7ec8-443a-b338-dc0bdb0e01ac)

## Result:
An Admission Enquiry Form using HTML that collects student details and message for institutional follow-up is successfully created using semantic and readable HTML.
