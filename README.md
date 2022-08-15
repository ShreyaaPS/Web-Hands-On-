# Web-Hands-On-
A number of simple interfaces built to understand and explore various  HTML,CSS,PHP,Angularjs,Ajax concepts
## Questions
# q4_forms
A form has only 2 fields - username and password (and a submit button). Perform the    following:
Ensure that the username consists of only lowercase letters and underscores.
(Verify using a regular expression (regex). If possible, try to validate this in the HTML itself (without using JavaScript) as it is faster)
Ensure that the password consists of at least 1 uppercase letter, 1 lowercase letter, 1 number and 1 special character (special characters include *,@, #, $)
(Write a function in Javascript to validate this. You can still write a regex for this, but it is a little complex!)
The form should not submit if either of the above criteria fail (Most Important!)
Add appropriate CSS and JS to indicate invalid input - To elaborate, simply highlight the input box and display an error message (in small font, below the input box) if the provided input is invalid. This should be done while the input is being typed by the user 

# q8_revenue
You are a manager of a grocery store and your store needs a new interface for calculating the revenue of each customer and an ‘add to inventory’ page. using Angular JS make 2 views, one for calculating the revenue and another to maintain an inventory checklist.
In the page for calculating the revenue, maintain two input fields, one for getting the name of the item and the other for getting the cost of the corresponding item. Once the two input fields are filled (* fields are mandatory), have a simple button that appends the item name and cost to a table (with columns as “ITEM NAME” and “COST”) below which the revenue is shown and updated for each addition of the item. Revenue = Revenue + 5% of the cost of each item.
In the ‘add to inventory’ page, maintain a checklist of items to be bought (you can hardcode the checklist or have a button to allow you to add items to the checklist dynamically) and once the checkbox for that item is checked, make that item disappear from the checklist.

# pallet
Write an angular application to make a color pallet. In the application, have a button to add an extra color and give an input tab to select the color and display the selected color beside the input filed. Make use of tables with ng-repeat attribute that takes the repetition value from a variable inside an angular controller. {ng-repeat="x in [].constructor(**var name**) track by $index"}, make use of this to perform repetition in the tables, use input type=”color”

# q10
Create a snowman using canvas

# q11_firing
Rumors of downsizing are once again floating around the office. Jim and Dwight decide to ally again to extract information on the employee performance score of all employees in the office. They manage to fetch the scores of all employees for the past 3 months and realize that if the average score is less than 60, then the chances of being fired are more likely. Both of them seek your help to build a web page that would take in employee performance scores for the past 3 months as input and print if that employee is likely to be fired or not. Use a custom AngularJS service to build the same. Validate the input keeping the following constraint in mind:
0 < Employee Performance Score < 100

# q14_jsanimations
It's leviOsa, not levioSA!”
It's the era of pandemic, even the greatest school of witchcraft wizardry,’Hogwarts’, have to switch to online education mode. 
You are in the 1st year of your schooling and you are required to perform the levitation charm and the illumination charm online.
You Produce the magic using angularJs animate supported by html and css.
Have 2 checkboxes with labels, Wingardium Leviosa and Lumos. Also a division box with black border.
On checking the first charm, the box should go up(change its position) and on unchecking it, it should be dropped.
On checking the second charm, the div should get a background color - ‘yellow’ and should turn off on unchecking.
The process should be made smooth and not abrupt. So provide appropriate time for proper transition.
Have fun exploring your magic!!

# q17_css3styles
Create a website that presents the new additions to CSS3. It should contain tags and elements that exhibit the following:
The different CSS Borders and Advanced Borders (5 minimum)
The different CSS Text Effects (5 minimum)
The CSS Transforms
Any five CSS Selectors
Each of these should be contained in a separate box which has a border size of 4 and the ‘aquamarine’ color. Make the website presentable by adding paddings and margins.

# q18_storedep
Suppose you are a web designer in charge of making a website for a departmental store. The owner of the store has asked for the following specifications:
It displays a list of 20 items that is available for shopping.
The items are grouped into 4 sets and are assigned a price for each set. These prices are the same for all the items in a particular set.
All these groups and their prices should be mentioned far below the item list.
Clicking on an item should lead to the bottom of the page where its group and price are mentioned.
A ‘Confirm’ button should be present below the prices list that finally displays the price of the item that is selected in user-friendly format.
Use HTML5, CSS3 and JavaScripts to create this website.

# q19_canvas
Create a website that draws two shapes based on user specifications. It should have the following: 
A simple rectangle using canvas in HTML5 that changes based on user inputs.
A simple circle using canvas in HTML5 that changes based on user inputs.
Use input tags to get the length and width of the rectangle and the radius of the circle. Also have a button ‘Draw’ to draw the shape in the canvas. The general order of the HTML page should be ‘Rectangle Inputs’ -> ‘Draw’ button -> ‘Canvas for Rectangle’ -> horizontal line -> ‘ Circle Inputs’ -> ‘Draw’ button -> ‘Canvas for Circle’-> horizontal line. Use JS to actuate the canvas and use CSS to make the page more presentable.

# q23_cvv
You are an entrepreneur who wants to start their first business. It is an online shopping website for quality stationery imported from across the globe. For this to be a success, you need to get the payment and shipping details from the customer.
Implement forms using HTML and CSS to accept the user details (such as first name, last name, age, gender, etc.), the card details(card number, CVV, card type(credit or debit), etc.) and the shipping details (current address, landmarks, city, state, pincode, etc.). You can also ask for a payment method, Cash on Delivery, or Online payment(using card is enough).
Validate the forms using a combination of HTML validators and JS validations as you see fit.
For the card details, find out the card issuer( mastercard, visa, etc.) using regex. You can use the following table as reference to derive the regex.

# video
Create a video player using angular with the following capabilities-play,pause,rewind,adjust playback speed,resize the window,forward the video,adjust volume.

# editor
Create an editor using angular which allows users to cut,copy,paste text within the application,save the text in the form of a text document and open an existing document

# q7_theme
Altering the theme of a website - 
Create a drop-down list that has 2 options - light and dark mode (light mode should be selected by default)
In the light mode, the background-color should be white and the font color should be black; it is vice-versa for dark mode
Create a custom directive or component (named theme) that allows you to change the theme of the website (light/dark) according to the input selected
(An example (need not be strictly followed))
<theme>
<!-- Main Content --> 
</theme>
Clarifications
The main content can be as simple as a “Hello World'' statement; the main-content should follow the styles of the mode specified in the theme tag (don’t forget to use the ng-transclude directive!)
Use the ng-style directive to dynamically change the style
(Syntax: <some-tag ng-style=“expression”>, where expression is of the form: {‘font-family’: ‘Times New Roman’, ‘font-size’: ‘12px’, …})

  
