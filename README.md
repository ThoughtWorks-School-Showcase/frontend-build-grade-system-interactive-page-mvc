# Build Interactive Page for Grade System(HTML CSS Bootstrap Integrated Implementation) 

## Business Requirements:
Apply HTML, Bootstrap, Javascript to implement a Student Grade System front end ,it should include below feature:
Add a student info on a single page.  
Query multiple students Infomation by student Name or ID.
Update a indicated student infomation.
Delete a indicated student.

1. Implementation a static page which display the student grade information
Apply Bootstrap table style. 
Allow write related information on page directly.

2. Implementation the feature “Add a student information via a single page”

* Student information should be submit via HTML Form element.
* Apply JavaScript listen to the form submit event.
* Validate after input information，The format mast be：
```
Format：Name, Number, Subject1: Score1, ... 
```
* If the input format is incorrect,，the view will display：
```
Please input the correct format（Format：Name, Number, Subject1: Score1, ...）： 
```

 * Student infomation should be stored in browser.


3. Base on the completed static page，implement“Query multiple students Infomation by student Name or ID ”

* Allows the user to query the results of multiple students .
* Check number for the student 
```
format: student number, student number, ...) 
```
in the correct format.
* Validate after input information，The format mast be：
```
Format：Name, Number, Subject1: Score1, ... 
```
* If the input format is correct , page will show the student's information , score , their total score and the median of the total score

4. Implment the feature “Update a indicated student infomation” 

* Allows the user to update the student information after querying the student information list.
* Validate after update information，The format mast be：
```
Format：Name, Number, Subject1: Score1, ... 
```
* If the input format is incorrect,，the view will display：
```
Please input the correct format（Format：Name, Number, Subject1: Score1, ...）： 
```
* Modify the student information if the format is correct.

5. Implement the feature “Delete a indicated student”

* Allows the user to delete the student after querying the student's infomation list.
* Delete the pop-up confirmation to determine whether the deletion of "name + school number" is right?

## Practice Challenges:
* Base on the new requirement, refactor the old code and implement new feature.
* Obtain input data from page via Javascript in correct way.
* Apply CSS adjust the page display.
* Understand and apply Javascript DOM amend event of HTML element.
* apply Javascript event strategy to listen and response user action.

## Practice Requirements:
* Use pure Javascript to operate page element.
* All input data should store in browser.
* Requirement should be implemented one by one in order.
* Each implementation of requirement should be commited to local Git repository.

## Practice Output:
Please push your practice repo to the incated site which coach will tell you.
Repository should includes：
1.implemented code

## Environment Require
Chrome

## How to begin：
git clone https://github.com/tws-online-quiz/frontend-build-grade-system-interactive-page
Stack Initial and build:
Open the index.html with browser direatly, you will see the result of any change.

## Learn Resourse(Chinese Version):

* HTML W3school教程：http://www.w3school.com.cn/html/index.asp
* CSS W3school教程：http://www.w3school.com.cn/css/index.asp
* Bootstrap中文文档：http://www.bootcss.com/
* JavaScript 闯关记：https://github.com/stone0090/javascript-lessons/
