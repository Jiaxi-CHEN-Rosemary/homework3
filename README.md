# homework3
Easy way to preview: https://htmlpreview.github.io/

## Objectives 
1. Gain familiarity with different CSS properties and values.
2. Demonstrate ability to use CSS Grid for layout of page content
3. Demonstrate ability to do styling on pseudo classes, including  “Skip to Content”
4. Demonstrate ability to use media queries to adjust how page content is displayed on different devices.
 
## Requirements
Note: the css code has comments to guide you through these requirements.  

1. When the mouse hovers over any link in the navigation add a wavy underline below it

Note: if you aren't seeing the wavy underline in Safari, try Google Chrome or Firefox.

2. The link using the skip class (“Skip to Main Content”) should be positioned 500px to the left, and 40px above of the link’s parent element. (So it is hidden by default when we open the page).
 
### Style the mobile view
1. Adjust the navigation so the text is aligned on the left side
2. .container class
* Uses grid
* Has three columns of 1fr 5fr 1fr
* Has a 30px gap between rows (use row-gap)
3. header element:
* Uses header.jpg as the background image with a fallback color of #DDDDDD, #858585, #707070, or #B3B3B3.
* Has a minimum height of 400px
4. .about, .clients, .method, and .contact:
* Are placed in 2nd column
* Set the width of all images to 100%
* You will only see a slight change
5. The .about-image, .clients-image, .method-image,  and .contact-image elements should:
* Span all three columns
* Have a maximum height of 500px
* Hide any part of the image that exceeds the div.  (Check that by making sure there is always a gap between the rows.)
6. Place the elements so that about and about-image are on the same row, clients, and clients-image are on the same row, etc.
7. The .text class elements:
* Are aligned in the center.
* Have a max-height of 25% of the viewport height
* Displays any overflow content via a scrollbar.  
 

### Style the desktop view
1. Adjust the navigation so that the nav is aligned to the right side
2. When the link using the skip class (“Skip to Main Content”) is in focus it is even with the left side of the screen and 20px down. 
3. container class uses grid with

Five columns: 50px, auto, 500px, auto, and  50px

Seven rows: 70px, 400px, 400px, 400px, 400px, 400px, 100px

4. The .about, .clients, .method-image, .contact-image elements:
* Begin in the third column and span two columns
5. The .method, .contact, .about-image, .clients-image:
* Begin in the second column and span two columns.

## Tips
1. Validate that your CSS has no syntax errors
2. Check your site on a mobile device, not just the emulator
 

## Submission Requirements
1. Place your code in a repo named homework3.
2. Submit the link to your repository and your deployed site (5 points will be deducted for only including one link)

