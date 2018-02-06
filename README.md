
# Winningtemp candidate tests

This is a repository for Winningtemp candidate tests. It is intended to provide insight into the range of your skill set. It is not a pass/fail test. Please do what you can.

**Guidelines for submitting your test:**

- Read the instructions
- Do the tasks
- E-mail your result to career@winningtemp.se with subject: "Candidate test"
	- The e-mail should contain your test or a link to your test (could be a link to a repo)
	- The e-mail should contain all the instructions that is needed to run and examine your test

If you have any questions, feel free to drop a line to: career@winningtemp.se.

Good luck!

Below are two tests, please read the instructions for the one suitable to your role:

- <a name="front-end-test">Front-end test</a>
- <a name="ux-designer-test">UX-designer test</a>

## <a name="front-end-test"></a>Front-end test

In the front-end folder there is a screenshot named "front-end-design.png". This is an actual screenshot from a feature in Winningtemp. 

#### Task 1
Re-implement this design with your own HTML and CSS.

**Requirements:**

 - The design should look as similar as possible to the screenshot
 - The design should be responsive, meaning it should look good on small devices as well as desktop devices
 - The values in the matrix are decimals with one decimal point from 0.0 to 10.0. A question mark is used when a value is missing (no value).
	 - The background colors in the matrix are based on the value:
		 - Value less than 2.0: #ff1f40
		 - Value between 2.0 and 4.0: #fc9526
		 - Value between 4.0 and 6.0: #f6d827
		 - Value between 6.0 and 8.0: #c9e223
		 - Value greater than 8.0: #97e126
		 - No value: #cccccc

#### Task 2
Implement your design in javascript using whatever framework you like (React, Angular, vue.js, jquery, plain javascript). 

**Requirements:**

- The javascript code should be able to render the design with a dynamic set of rows and columns based on some kind of data structure
- Extra points for providing unit tests with your code

## <a name="ux-designer-test"></a>UX-designer test

Your task is to implement a new feature to view and document one on one meetings between two users.

In the ux-designer folder there is a wireframe "Wireframe Employees one on one.png" that shows a basic view of the feature. For this task you should follow the design manners that Winningtemp uses today and the design proposal should follow the style according to "Design style Winningtemp.png".

At the top of the page the user should be able to select a user who they want to invite to the one on one meeting. When a user is selected the view should show a brief summary information about the user and previous meetings are presented. In the toolbar there should be a button to create a new meeting and filter controls to filter the contents of the timeline below. The timeline should contain information about previous meetings and each meeting should have a header and a functionality to expand and collapse detailed information. Users should be able to comment on each meeting. If there are any comments on a meeting these should be presented. At the right is information that should show whether the user has verified the meeting or not. 

#### Task 1
Create a complete design proposal based on the wireframe where the design is ready for implementation. 

The design proposal should be an image (.png, .jpg or any format that can be opened by a common image viewer).

#### Task 2
Implement your design proposal with your own HTML and CSS.

**Requirements:**

- It is important that the design is responsive, meaning it should look good on small devices as well as desktop devices.