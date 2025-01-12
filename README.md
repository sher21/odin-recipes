# Odin Recipes

### First half of the assignment:

We are creating a recipes homepage. No extra decoration, just homepage with a link to subpage.In the homepage, we learnt on how to redirect link to another page, optionally open a blank page while doing that. We also learnt to keep the link in an unordered list to make the link in one column.

For subpage, we created 3 pages for recipes. To ease our coding, we get the picture from the allrecipes.com as well as the recipes. 

There are lasagna, hotdog_roll and orange_chicken page that we create. For each page, we learnt on how to add picture to our page, setting the height and width. We also learnt on how to add unordered list for the ingredients and ordered list for the steps. Note that the difference between both list is unordered list comes with bullet point while ordered list comes with number. 

We also learnt on how to add paragraph as well as different heading. There are 6 heading but for our page, we only include 2 heading which is h1 and h3(for subtopic). Last, we also add the link to direct us to our homepage. (The link will not open to new tab since we are not redirecting it to new tab.)

In summary, what we learnt:
* adding relative and absolute link 
* redirect link to open in a new tab
* handle different heading (got 6 heading)
* add simple paragraph
* add unordered list (comes in bullet point)
* add ordered list (comes in numbers)
* add image and adjust the height and width.

Note: We did not add any text manipulation like strong, em, italic or bold. We also did not experiment with other heading except for h1 and h3. 


### Second half of assignment:

In second half, we learnt on CSS styling. CSS stand for Cascading Style Sheet. CSS is a way where we can turn our website into a piece of art with colors and more styles. This is the way where we add background color, set font type and size, change text color and more. 

The first thing we learnt about CSS is the selector. There are many types of selector:
- universal selector (syntax is *) . We added this in our style.css to initialize how all element look like
- type selector (syntax is the name of element). We have this selector in our css file such as h3, ol . We use this selector to add background color, to change font of the specific element.
- class selector (syntax is . with class name). We add this selector by adding class name in our html file. Example of class name we added is home, main and more. This type of selector is to change the specific class name. 
- group selector (syntax is mix between type and class (with comma)). We use this selector since some of the element or the class have same style 
- chain selector (syntax is .classname.classname). Both classname need to set so that the style takes effect. In our case, we added .recipes.lasagna, and we change it to yellow. So only the class name with recipes lasagna will have the yellow background. 
- descendant combinator (syntax is type or class name with spaces). We use this selector to add specific element for the child . In our case, we have ol li, to set the list (child) of li a specific style we already set.

Next, we also learnt on how the styling is:
- background-color . This refer to the background color of text. For example, if we add this to heading, and set it to green. The heading will turn green. But, we tried to add this to a element which is the anchor (link to another page), the color did change but it only border around the word. But if we add heading to that anchor element, the border will expand through the page. 
- color. This refer to the color of text, font color. The color change but we tried to change the text color for link but it did not change , since by default link color is blue. (Need to confirm why the color did not change)
- font-family. This is to set the font type. We added the font family that is built in VS code. Just note for font name , we need to add "", for sans-serif or serif, no need to add ""
- font-size. Change the font size to smaller or bigger. Right now, the smallest font size we added is 15px. 
- text-align. this is to align the position of element either center or left, or right. We tried to img element but it does not work, but we add the text-align:center to universal selector, the image change the position to center. (Need to confirm why the image did not change position)
- font-weight. this change the boldness of text. Right now, we just add bold, but we can also set number to font-weight
- height and width for image. Right now, we set the height and width for image in px. but we can also set the image size to its initial size by using "auto" or "initial"

Note: the selector we did not use is id selector and multiple selector. There are also few confusion with cascade. Sometimes, some style override or overwrite the style we already set. Need to practice more and understand more on this. 
