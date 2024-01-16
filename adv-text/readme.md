# Code Snippet Activity
In this activity, you will utilize more advanced text-level elements to define the purpose and semantic nature of the text.

## Activity Objectives
1. Create a code example component.
2. Style the components with CSS.

## Text Element Tutorials Directions
1. Open the `index.html` file created in a previous practice activity.
2. Use the Save As command to save a new file and save it in the same place as the `index.html` file with the name: `text-elements.html`.
3. Within the main section:
   1. Remove the definition list.
   2. Create a level 2 heading with the following text: `Code Snippet Example`
1. Save the file.
2. Apply a commit to the file with the following message: `added heading for example`.
3. Under the code snippet heading:
   1. Create a paragraph with the following text: `To create a definition list, you will need to add the dl element, the dt element, and the dd element(s), repeating the dt and dd elements as needed for each item in the list.`
   2. Create a `div` element with a `class` of `code-snippet` and then add the following within the element:
       1.  Add a `pre` element.
       2.  Add a `code` element as a child of the `pre` element. i.e., `<pre><code></code></pre>`
       3.  Within the `code` element, write the HTML code that would be needed to create a definition list with the associated child elements. Use placeholder text within the child elements. *Remember to escape the less than and greater than symbols. Also, remember that with the `pre` element however many spaces you indent your lines of code will be added to the code when displayed to the end user, so you may want to remove the indent to make it look good when displayed to the end user.*
4.  Save the file.
5.  Apply a commit to the file with the following message: `added the dl code snippet`.

## Styling Directions
1. Open the `main.css` file within the `css` folder.
2. Create a selector for the ordered list items and add a bottom margin of `8px`. This will help generate whitespace so the key styles don't overlap.
3. Create a selector targeting the code snippet element and apply the following styles:
   1. Apply a width of `85%`.
   2. Apply a margin of `auto`.
   3. Apply a padding of `10px`.
   4. Apply a background color of `hsl(193, 50%, 93%)`.
   5. Apply a text color of `hsl(193, 70%, 20%)`.
   6. Apply a thick, double border with a color of `hsl(193, 30%, 46%)`.
4. Create a selector targeting the `pre` element and apply the `white-space` property with a value of `pre-wrap`. This will ensure that the code will wrap within the code snippet container instead of overflowing.
5. Save the file.
6. Apply a commit to the file with the following message: `added code text stylings`

## Conclusion
1. When you are done with the activity, sync the files (i.e., push your changes) with the remote repo on GitHub.
> TIP: You can view any of your repos by going to the GitHub organization for the course - [RSC-CIS233DA-in-v8](https://github.com/rsc-cis233da-in-v8). You can bookmark the page for future reference. 