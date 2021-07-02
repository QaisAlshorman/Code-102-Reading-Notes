#### HTML borrows the concept of a form to refer to different elements that allow you to collect information from visitors to your site. 


![image](https://user-images.githubusercontent.com/85091281/124309758-e1be5000-db73-11eb-87ff-9705fcba275c.png)

![image](https://user-images.githubusercontent.com/85091281/124309797-f4d12000-db73-11eb-8d98-8091dd8bb5d7.png)
![image](https://user-images.githubusercontent.com/85091281/124309840-04506900-db74-11eb-9fd7-b2fa5362e92a.png)
#### How Forms Work
A user fills in a form and then presses a button to submit the information to the server.

A form may have several form controls, each gathering different information. The server needs to know which piece of inputted data corresponds with which form element.You should never change the name of a form control in a page unless you know that the code on the server will understand this new value.

![image](https://user-images.githubusercontent.com/85091281/124310292-a7a17e00-db74-11eb-85ad-0569610473d5.png)

![image](https://user-images.githubusercontent.com/85091281/124310675-36ae9600-db75-11eb-927a-31cfb8381293.png)

#### method
Forms can be sent using one of two methods: get or post.With the get method, the values from the form are added to the end of the URL specified in the action attribute. The getmethod is ideal for:
● short forms (such as search boxes)
● when you are just retrieving data from the web server (not sending information that should be added to or deleted from a database)

### Form Structure
With the post method the values are sent in what are known as HTTP headers. As a rule of thumb you should use the post method if your form:
● allows users to upload a file
● is very long
● contains sensitive data (e.g. passwords)
● adds information to, or deletes information from, a database
If the method attribute is not used, the form data will be sent using the get method

You have probably seen forms on the web that give users messages if the form control has not been filled in correctly; this is known as form validation.
- Whenever you want to collect information from visitors you will need a form, which lives inside a <form> element.
- Information from a form is sent in name/value pairs.
- Each form control is given a name, and the text the user types in or the values of the options they select are sent to the server.
- HTML5 introduces new form elements which make it easier for visitors to fill in forms.
  
  ![image](https://user-images.githubusercontent.com/85091281/124313664-d79f5000-db79-11eb-947e-7807d0a12d35.png)


width to set the width of the table
padding to set the space between the border of each table cell and its content
text-transform to convert the content of the table headers to uppercase
letter-spacing, font-sizeto add additional styling to the content of the table headers
border-top, border-bottomto set borders above and below the table headers
text-align to align the writing to the left of some table cells and to the right of the others
background-color to change the background color of the alternating table rows
:hover to highlight a table row when a user's mouse goes over it .
Here are some tips for styling tables to ensure they are clean and easy to follow:
Give cells paddingIf the text in a table cell either touches a border (or another cell), it becomes much harder to read. Adding padding helps to improve readability.
Distinguish headingsPutting all table headings in bold (the default style for the <th> element) makes them easier to read. You can also make headings uppercase and then either add a background color or an underline to clearly distinguish them from content.
Shade alternate rowsShading every other row can help users follow along the lines.
Use a subtle distinction from the normal color of the rows to keep the table looking clean
.Align numerals You can use the text-alignproperty to align the content of any column that contains numbers to the right, so that large numbers are clearly distinguished from smaller ones

If you have empty cells in your table, then you can use the empty-cells property to specify whether or not their borders should be shown.
Since browsers treat empty cells in different ways, if you want to explicitly show or hide borders on any empty cells then you should use this property.
It can take one of three values:
#### show
This shows the borders of any empty cells.
#### hide
This hides the borders of any empty cells.
#### inherit
If you have one table nested inside another.
 the inheritvalue instructs the table cells to obey the rules of the containing tableList markers can be given different appearances using the list-style-type and list-style image properties.
  
- Table cells can have different borders and spacing in different browsers, but there are properties you can use to control them and make them more consistent. 
- Forms are easier to use if the form controls are vertically aligned using CSS.
- Forms benefit from styles that make them feel more interactive

![image](https://user-images.githubusercontent.com/85091281/124316131-c8220600-db7d-11eb-9e6f-6a506af05442.png)

![image](https://user-images.githubusercontent.com/85091281/124316217-ee47a600-db7d-11eb-8c27-70b057446ce2.png)
 
![image](https://user-images.githubusercontent.com/85091281/124316309-159e7300-db7e-11eb-80f1-f70bc80d6d1e.png)

  ![image](https://user-images.githubusercontent.com/85091281/124316605-8776bc80-db7e-11eb-8a5b-596bd8b73718.png)

####THE EVENT OBJECT 
When an event occurs, the event object tells you information about the event, and the element it happened upon. 

Events are the browser's way of indicating when something has happened (such as when a page has finished loading or a button has been clicked). 
Binding is the process of stating which event you are waiting to happen, and which element you are waiting for that event to happen upon. 
When an event occurs on an element, it can trigger a JavaScript function. When this function then changes the web page in some way, it feels interactive because it has responded to the user. 
You can use event delegation to monitor for events that happen on all of the children of an element. 
The most commonly used events are W3C DOM events, although there are others in the HTMLS specification as well as browser-specific events. 

  
