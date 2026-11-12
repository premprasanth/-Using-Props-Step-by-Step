# React Lab Exercise 2: Using Props — Step by Step
## Name: PREM PRASANTH J
## Roll no: 2305001028
## Department: CSE

## AIM
### To create a React application that demonstrates how to pass data from a parent component to a child component using Props.

## PROGRAM
### i) App.jsx
```py
import Employee from "./Employee";
function App() {
return (
<div>
<h1>Employee Information</h1>
<Employee
name="NISHAL K"
id="101"
department="CSE"
designation="Software Developer"
/>
<Employee
name="PREM PRASANTH "
id="102"
department="IT"
designation="Web Developer"
/>
<Employee
name="MARUDHU"
id="103"
department="AIDS"
designation="Data Analyst"
/>
</div>
);
}
export default App;
```
## OUTPUT
<img width="1280" height="694" alt="image" src="https://github.com/user-attachments/assets/819e5ed1-abee-418a-9b31-32c19ea90827" />


## RESULT
### The React application was successfully created using Props to pass employee information from the parent component to the child component. Three employee details were displayed successfully using Props and Props Destructuring.
