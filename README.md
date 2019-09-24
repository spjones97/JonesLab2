# Instructions
Remember that CSS organizes HTML elements into boxes, each of which includes four components: content, padding, border, and margin. 

See Chapter 5 in HTML5 & CSS3, the current class slideset, and the MDN pages on all things box model for reference.

This lab will introduce how Google Chrome's DevTools can be used to view the box around each element on a web page.

# Part 1: VIEW CSS STYLES AND BOX MODEL DIMENSIONS WITH CHROME DEVTOOLS
You can use Google Chrome's DevTools to view the styles and box model of every element on a web page. To do this, click View > Developer > Developer Tools. Or if the developer tools are already active in your browser, you can just right-click or control-click on any element on the page that you want to inspect, select Inspect, and the DevTools will open up automatically in your browser, as described below.

If you are a beginner or could use some extra help figuring out what Chrome's DevTools are or how they work, check out this article: How to Use Chrome DevTools for the Absolute Beginner.

1. The Elements Window
By now, you should have the DevTools open within your browser so that you can view all the HTML and CSS associated with the element you're inspecting,  Along with a smaller view of the web site you're trying to inspect, you'll see a menu that reads Elements - Console - Sources - Network above some new windows containing HTML, CSS, and some other stuff. The Elements tab will probably be active by default (the Console tab opens the JavaScript console, if you're interested; we'll do more with that later).

The Elements window is split into two or more panels. In one, you'll see the current page's HTML elements; in another, you'll see its CSS styling; and if the box model panel is open by default you'll see that too. You can select specific elements to focus on by clicking on each line of HTML in the DevTools pane; as you scroll through the HTML, you can see the corresponding elements highlighted in the page view. When you select an element, the CSS rules that apply to that element will appear in the CSS pane. Styles that have been overridden by other styles or are invalid for other reason will appear in strikethrough text.

Again, for a more detailed guide and some images of what you should be seeing when DevTools are open, see How to Use Chrome DevTools for the Absolute Beginner.

2. Viewing the Box Model
A sketch of each selected element's box model, with measurements, may appear automatically when you open the DevTools. If it does not, look for a menu in the DevTools interface that starts with Styles. Is there a tab entitled Computed next to it? If so, click on that, and the box model sketch should appear.

If you know the element you want to inspect, going through all of the steps listed above is unnecessary. Instead, you can right click the element you want to observe and select the Inspect button. This will display DevTools on the right side of the browser with the element selected in the Elements tab. To view the element's box, you can select the Computed tab.

3. Find the Website's Box Model Dimensions and Properties
Complete the following steps within the current browser view, with DevTools remaining open.

Open a new tab. Navigate to UNC-Chapel Hill's Wikipedia page.
Right click or control-click on the Contents navigation box on the left-hand side of the page.
Select Inspect/Inspect Element. The DevTools panes will appear. If you don't see the box model image right away, select the Computed tab at the top of the rightmost column, and the box model of the Contents box element should appear.
Hover over the different properties within the box model image. The corresponding space on the web page should be highlighted when you do this.
4. Modify the Website's Box Model Properties, and Take a Screenshot
Now let's try modifying the box models of elements on UNC-CH's Wikipedia page.

Double click on an element on the page. Take a look in the CSS. Find declarations that govern the padding, margin, or border of that element.
Change the box model properties of various elements on the page, and observe, until the page looks significantly different.
If this gets boring, find a website of more complex design and try the same process.
When you feel like you're in control of things and have made significant changes, take a screenshot of the website you've been playing with--with all its new dimensions intact--and save it. You'll submit it with the html and css files you'll create in part 2 of this assignment. (If you've uploaded a screenshot of a site other than UNC-CH's Wikipedia page, paste the URL of that site in the text box of this assignment as well.)
Remember: changes you make in DevTools are only previews; they're not forever. If you're using DevTools to experiment with adjustments to a personal project, make sure to adjust those values in your actual HTML and CSS documents.

Note: If you inspect an element and find that the border is set to -, adding a numerical value will not make a border appear. The border color, style, and width must be set in the CSS document in order to see the border.

# Part 2: DEVELOP IT
Using what you've learned about the box model, CSS, fonts, color, opacity, and more, create two web pages, each comprising an html document linked to a CSS stylesheet, that look like the sites pictured in the two images attached to this assignment. Call the first set of documents--the ones that create a site that looks like image1--"image1.html" and "image1.css", and call the second set--the documents that create a site that looks like image2--"image2.html" and "image2.css".

DO NOT simply place image1.jpg and image2.jpg in html documents and call it a day. The point is to create web sites from scratch that look like those images, not to embed those images into html documents. Your image1 site should contain a background image with at least three different--and differently styled--HTML text elements on top of that background. (See the box model section of the Lecture 1 slideset and this Codepen for an example of how to do this.) Your image2 site will contain a background color and two different--and differently styled--HTML text elements.

Here's a link to the page where you can download the image used as the background in image1 below: https://newmedia.report/images/classes/intro-to-interactives/background.png . There is also a separate .png version of this image attached below that you can download directly from this assignment, if that's easier for you.

The image should cover the entire background of image1.html, with no space around it and no distortion. You can use this image (linked above) or a photo of your own, then position the text elements on top of it.As

As a reminder, here's an example of a full-page background image: https://codepen.io/tkjn/pen/daYpJQ?editors=1100

Here's a bit more about the background-image property: https://www.w3schools.com/cssref/pr_background-image.asp

And if you're accustomed to (or want to try) using the background property to handle your backgrounds, you can do that too, as follows: https://www.w3schools.com/cssref/css3_pr_background.asp

Your image2 site won't require a background image; just try to match the color as best you can. You must use an RGB, RGBA, HEX, HSL, or HSLA code for the color.

Match the fonts as best you can. They don't need to be absolutely identical. You can use any of the web-safe fonts listed at W3Schools, or for more options try using a Google Font, as shown in these examples: http://www.webdesigndev.com/16-gorgeous-web-safe-fonts-to-use-with-css/ More Google fonts are here: https://fonts.google.com/; the article in the first link shows you how to use them in a project. We'll do more with Google Fonts later on; they're easy to use, so don't be afraid to give it a try!

Part 3: SUBMIT YOUR FILES
When you're done, put the files you create into a folder called YourlastnameLab2, compress/zip the folder, and attach it here by the deadline.

So YourlastnameLab2 should contain five files in total, plus the background image file you used.

A screenshot of a web page with modified box model properties 
image1.html, containing the html that creates a web page that looks like image1, and fully validated
image1.css, properly linked to image1.html, comprising the styles you've applied to image1.html
The background image you link to in your image1 site.
image2.html, containing the html that creates a web page that looks like image1, and fully validated
image2.css, properly linked to image2.html, comprising the styles you've applied to image2.html
