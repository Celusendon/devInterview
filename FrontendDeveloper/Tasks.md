# **Tasks - Frontend Developer Interview**

## **Task Nr. 0 - "How old is the capitan?"**
> Warm-up task

### **Statements**
1. We have 4 vehicles.
2. We know the type for 3, which are the following:
	- a fishing boat
	- an aircraft carrier
	- an oil tanker

### **Goal**
Solve the following:
1. Place all of the vehicles, but they need to keep the same distance from each other.
2. Name the type of the 4th vehicle.

---
## **Task Nr. 1 - "Two robots with parachutes"**
> Solve a small problem.

### **Statements**
1. Two robots are to be parachuted onto random locations on an infinite line.
2. When they land, their parachutes detach and remain where they are.
3. The robots may be programmed from the following instruction set:
```
left --> Go left one unit 
right --> Go right one unit 
skipNext --> Skip next instruction if there is a parachute here.
goto myLabel --> Go to label named "myLabel" 
```
4. Each of these instruction can be prepended by an optional label.(label: instruction). 
5. They both run the same code.

### **Goal**
Your goal is to program the robots to meet (collide).

### **Test framework**
You can use the [following](https://david-peter.de/parachuting-robots/) page to test your code.

---
## **Task Nr. 2 - Coding**
> Write a simple algorithm.

### **Option Nr. 1**
Find whether a number is a prime number or not. 

### **Option Nr. 2**
Given an input string, reverse the string word by word.

**Statements**
1. A word is defined as a sequence of non-space characters. 
2. The input string does not contain leading or trailing spaces.
3. The words are always separated by a single space.

**Example**
```
Given: "the sky is blue"
Return: "blue is sky the"
```

---
## **Task Nr. 3 - HTTP**

> Can you name some HTTP methods and what they do?

> What does Idempotency mean? Whitch HTTP methods are idempotent? 

---
## **Task Nr. 4 - TypeScript, Angular**

> How could you check null and undefined in TypeScript? 

> How will you add border images to an HTML element? 

> What does Data binding mean in Angular? 

> Can you name some built-in Angular directives? 

> One of you colleague wrote this code as a temporary placeholder: 
> ```ts
> <select aria-label="Customers" class="form select customerpicker" [>(ngModel)]="maxEntries" (change)="customerChange()" *ngIf="computedTreeContent.length > 0 && !loading">
> 	<option value=1>Paul</option>
> 	<option value=2>Jack</option>
> 	<option value=3>Mark</option>
> 	<option value=4>David</option>
> 	<option value=5>Joe</option>
> </select>
> ```
> Now we are getting the customers from the backend, the response is stored in the variable evoCustomers like this: 
> ```json
> [
> 	{
> 		"id": "1424",
> 		"name": "John Doe"
> 	},
> 	{
> 		"id": "1543",
> 		"name": "Paul Reed"
> 	}
> ]
> ```
> Modify the code so that we are able to select all the customers we get back from the backend by their names, but use their IDs as value. 