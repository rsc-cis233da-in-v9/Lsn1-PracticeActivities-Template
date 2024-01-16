# Account Login Form Activity
In this activity, you will create a form component that is common on many websites. 

## Activity Objectives
1. Create a component to allow a person to sign into an account.
2. Style the components with CSS.

> For any forms in this course, you can post the form to the script found at https://secure.riosalado.edu/cis-course-resources/postscript.aspx.

## Account Components Directions
1. Open the `accounts.html` file.
2. Within the main section:
   1. Create a level 2 heading with the text: `Login Component`.
   2. Add a paragraph with the following text: `The following component can be used to add login functionality to a website.`
3. Under the login heading and after the paragraph:
   1. Insert a form that will post to the postback script listed within the online lesson and the note above. 
   2. Apply an `id` of `form-login`.
   3. Create a fieldset with the following elements:
      1. Create a legend for the fieldset with the text of: `Account Login`.
      2. Create 3 `div` elements with a class of `field-group`.
      3. Within the first `field-group`:
         1. Create a label with:
            1. The text `Username`.
            2. Indicate that it is `for` the `login-username` input field.
         2. Create an text input field with:
            1. An `id` and `name` with a value of `login-username`.
            2. Apply the `required` attribute.
      4. Within the second `field-group`:
         1. Create a label with:
            1. The text `Password`.
            2. Indicate that it is `for` the `login-password` input field.
         2. Create a password input field with:
            1. An `id` and `name` with a value of `login-password`.
            2. Apply the `required` attribute.
            3. 
      5. Within the third `field-group`:
         1. Create a label with the text of `Remember me` and `for` the `remember-me` input field.
         2. Create a checkbox input field with an `id` and `name` with a value of `remember-me`.
      6. Create a submit button with the display text of `Login`.
4. Save the file.
5. Apply a commit to the file with the following message: `added login component`.

## Styling Directions
> TIP: Unless otherwise specified, most of the selectors you need to create use the descendant selector type to target the specific element, which has a space between the selectors and would follow this pattern: `#id .class element {}` or `#id element {}`.

1. Open the `main.css` file from the `css` folder.
2. Create a selector for the `form-login` element and apply the following styles:
   1. Add a width of `35%`.
   2. Set the margin to `auto`.
3. Create a selector for the fieldset within the `form-login` element and apply the following styles:
   1. Set the border style to `outset`.
   2. Set the border color to `hsl(271, 30%, 46%)`.
   3. Set the background color to `hsl(271, 30%, 46%)`.
4. Create a selector for the legend within the `form-login` element and apply the following styles:
   1. Set the font weight to be bolder.
   2. Set the background color to `white`.
   3. Add a top and bottom padding of `3px` and a left and right padding of `10px`.
   4. Create a thin, solid border with a color of `hsl(271, 30%, 46%)`.
5. Create a selector for the `field-group` element within the `form-login` element and apply the following styles:
   1. Set the top and bottom margin to `8px`. 
6. Create a selector for the label within the `field-group` element within the `form-login` element and apply the following styles:
   1. Set the width to be `100px`.
   2. Change the `display` property to be `inline-block`.
7. Create a selector for `input[type=checkbox]` (this is an attribute selector that you'll learn about in the next lesson) and apply the following styles:
   1. Set the width and height to be `16px`.
   2. Set the margin to `0`.
8. Create a selector for the button within the `form-login` element and apply the following styles:
   1. Float the element to the right.
   2. Change the border color to use `hsl(271, 30%, 46%)`.
   3. Add a top and bottom padding of `4px` and a left and right padding of `16px`.
   4. Set the background color to use `hsl(271, 30%, 46%)`.
   5. Change the text color to use `hsl(271, 30%, 95%)`.
9.  Save the file.
10. Apply a commit to the file with the following message: `added login form styles`.

After applying the styles to the forms, it should look similar to the following image:

![screenshot of the two forms with styles applied](../images/L1-PA-form-examples.png)

## Conclusion
1. When you are done with the activity, sync the files (i.e., push your changes) with the remote repo on GitHub.
> TIP: You can view any of your repos by going to the GitHub organization for the course - [RSC-CIS233DA-in-v8](https://github.com/rsc-cis233da-in-v8). You can bookmark the page for future reference.