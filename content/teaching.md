+++
# Custom widget.
# An example of using the custom widget to create your own homepage section.
# To create more sections, duplicate this file and edit the values below as desired.
widget = "custom"
active = true
date = 2016-04-20T00:00:00

# Note: a full width section format can be enabled by commenting out the `title` and `subtitle` with a `#`.
title = "Teaching"
subtitle = ""

# Order that this section will appear in.
weight = 60

+++

I have been a TA for the following courses:

- **ECON 201**: Introduction to Microeconomics (Spring 18)
- **ECON 202**: Introduction to Macroeconomics (Fall 17)
- **ECON 311**: Intermediate Microeconomics (Winter 18)
- **ECON  421**: Introduction to Econometrics  (Winter 19)
- **ECON 607**: Core Macroeconomics I, III (Graduate Level, Fall 18, Spring 19)

Course reviews are available upon request.


You can leave anonymous feedback here:

<div class="container">
  <form action="action_page.php">

    <label for="fname">Course Name</label>
    <input type="text" id="cname" name="coursename" placeholder="Course name..">

  

    <label for="subject">Feedback</label>
    <textarea id="subject" name="subject" placeholder="Write something.." style="height:200px"></textarea>

    <input type="submit" value="Submit">

  </form>
</div>


input[type=text], select, textarea {
  width: 100%; /* Full width */
  padding: 12px; /* Some padding */ 
  border: 1px solid #ccc; /* Gray border */
  border-radius: 4px; /* Rounded borders */
  box-sizing: border-box; /* Make sure that padding and width stays in place */
  margin-top: 6px; /* Add a top margin */
  margin-bottom: 16px; /* Bottom margin */
  resize: vertical /* Allow the user to vertically resize the textarea (not horizontally) */
}

/* Style the submit button with a specific background color etc */
input[type=submit] {
  background-color: #4CAF50;
  color: white;
  padding: 12px 20px;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}

/* When moving the mouse over the submit button, add a darker green color */
input[type=submit]:hover {
  background-color: #45a049;
}

/* Add a background color and some padding around the form */
.container {
  border-radius: 5px;
  background-color: #f2f2f2;
  padding: 20px;
}
