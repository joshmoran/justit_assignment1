# Just IT - Assignment 1

# README & IMPORTANT - How this document is formatted
>> Throughout I will be discussing specific sections / areas
>> To review, please refer to "Chosen website - codeacademy - EDITRED.jpg"

# Index System
- 1. Assignment Task
- 2. Webpage breakdown 
- 3. Colors and fonts
- 4. Media queries - mobile, tablet and desktop versions 
  
# 1. Assignment 1 
## WEBSITE CLONE PROJECT:
** Objective: ** Utilize your HTML and CSS skills to recreate the landing page of a website of your choice. This project is an opportunity to deepen your understanding of web design and development. 

## Task Details:
1. Selection of Website: Choose a website with a landing page that you find visually appealing and technically interesting. Ensure that your chosen website is complex enough to challenge you, but not so advanced that it becomes unmanageable with your current skill set.
2. Analysis and Planning:
• Structure and Design: Analyze the structure of the website’s landing page. Identify the HTML elements used and their arrangement. Consider the page layout, navigation elements, headers, footers, and any unique sections.
• Styling: Pay attention to the CSS properties that contribute to the visual design. Note the fonts, colors, spacing etc.
• Developer Tools: Use the browser's developer tools to inspect the page. This can provide insights into the HTML structure and CSS styles. For example, Chrome's CSS Overview can reveal details about fonts and colour schemes used.

3. Development:
• HTML: Create the HTML structure based on your analysis. Use semantic HTML to ensure your code is accessible and meaningful.
• CSS: Apply CSS to style your page. Try to replicate the original design as closely as possible.
• Focus on Visual Design: Your task is to replicate the visual design and layout. You are not expected to recreate any backend functionality or add additional pages. Interactive elements should be limited to what can be achieved with HTML and CSS
(e.g., hover effects). 

## Stretch Goal:
Try to implement responsiveness into your design with media queries.
Useful links:
• https://cssgradient.io/
• https://animista.net/
• https://scrollbar.app/
• https://www.cssportal.com/css-clip-path-generator/
• https://favicon.io/favicon-generator/
• https://hype4.academy/tools/glassmorphism-generator

# 2. Web breakdown 

## Header - Banner and Navigation
### Banner 
- Shown no matter on what screen type 
- Information on the most recent update / notification 

### Navigation
- Objects that do not change
  - Code Academy logo is always to the left of the screen
  - Search icon
  - Login button
  - Sign up button
- Does change depending on the viewport
  - On Mobile and Tablet, the navigation is removed and a collapsed icon is added to the far right, right of the sign up button
  - On Mobile and Tablet, the entire options is shown to clicking the collapsed icon and a full screen view of the navigation can be seen and interacted with
  - On Desktop, the navigation is shown between the logo and the search icon 
    - Collapsed button is removed 
    - Drop down menus are enabled with hovering 


## Article 1 - Carousel and Register Form
### Carousel 
- Picture style does not change 
- Location of the carousel heading and two paragraphs changes depending on what screen size it is being viewed on
- Button to change the carousel picture/all three text areas does not change
  - On Desktop, an extra button is added to the right of the five buttons, which add play and pause support for playing or pausing the carousel

### Register an account 
- Does not change format, style or sizing. 
  - On mobile, it is below the carousel in a column
  - On tablet and desktop, it is to the right of the carousel in a row

## Article 2 - Questionnaire, 'Find what's right for you'
- Heading stays centered at the top of the article 
- Slight change in format, style and sizing 
  - The direction changes depending on the screen view, In order: heading, about sections then 3 buttons
    - On Mobile, it is a column
      - Buttons are in a row and at the bottom of the article
    - On Tablet and Desktop, it is a row
      - Buttons are in a column and are at the left of the main content
  - A picture of a notebook and pen 
    - On Mobile and Tablet, the image is hidden
    - On Desktop, it is in the row, farthest right
  - On Desktop

## Article 3 - Selection of courses available 
- Slight variation on format, style and sizing 
- Heading and a small paragraph are at the top of the article
- Their is a category of areas that a user can view some of the courses they have for those areas
  - On Mobile and Tablet, you click the area and a limit of 4 courses are inserted below the clicked heading
  - On Desktop, all categories are above the content, clicking on the categories remove the content and add the relevant categories content

## Article 4 - Showcasing their learning method, 'Hand-on learning'
- Heading and small paragraph above always stay at the top, centered 
- The content (image and selection boxes) vary to screen size
  - On Mobile, the image and selection boxes are in a column, image at the top
  - On Tablet and Desktop, the image and selection boxes are in a row, image to the right and selection boxes to the left
- Content boxes once clicked reveal and un-hide the paragraph below

## Article 5 - Career Checker Section, 'Job Readiness Checker'
- Slight variation of the format, style and sizing 
- Content is split into two boxes: an image (Job Ready Checker) and details (heading, paragraph text and a link )
  - On Mobile, the boxes are in a column, image top and details bottom
  - On Tablet and Desktop, the boxes are in a row, image left and details right 

## Article 6 - Showing partnerships, code academy helping to engage organizations to reach their goals with technical training
- Slight variation of the format, style and sizing 
- Content is split into two boxes: firstly showing partnerships: airbnb, amazon, daily motion and reverb and the second, the details (code academy teams logo, heading, paragraph text and a link )
  - On Mobile, the boxes are in a column, details box is above and the partnership box is on the bottom
  - On Tablet and Desktop, the boxes are in a row, details on the left and partnerships on the right 

## Article 7 - Stories and personal accounts for using code academy, 'Stories from real people'
- Variation of the format, style and sizing 
- Uses a header and a small paragraph at the top center in all screen sizes
- Main content where each story is in their own container, a total of four stories
  - On Mobile, the individuals stories are in a column 
  - On Tablet, the individuals stories are in a 2x2 grid, set initially to row with overflow being on the second row
  - On Desktop, the individuals stories are all in a row
- A link for 'Explore more stories' changes based on screen size
  - On Mobile, the link is at the bottom of the column of stories
  - On Tablet and Desktop, it is aligned at the top, parallel to the paragraph 
 
## Article 8
- Variation of the format, style and sizing
- Content is split into two boxes: first has a single heading ('Join in on something big') and the second, has three statistics for code academy
  - On Mobile, the boxes are in a row with both boxes being columns themselves 
  - On Tablet and Desktop , all items (heading and all statistics) are in a row

## Article 9 
- Variation of the format, style and sizing
- Content is split into two boxes: firstly with two pictures, each a different person and the second box is details containing a header, paragraph text and a link
- The boxes are always in a row with each box aligning in a column
  - On Mobile, the second image in the first box is hidden

## Footer 






# 3. Colour and fonts 
> I used 'Microsoft Power toys - Color Selector' Feature to get these colors 

## Fonts 
- On Body and Div = 'sans serif'

## Header 
### Banner
#### Colors 
- Background Color = #10162f
- Text Colour = #ffffff
- 'UPSKILLNOW' text color = #ffd300
- 'UPSKILLNOW' hover text = #262b42

#### Effects
- 'UPSKILLNOW' on hover fades the background color and applies a lighter shade
  
### Navigation
#### Colors
- Background color = #fff0e5
- Desktop View, Nav button on hover  = #9362e5
- Desktop View, Nav button text color = #10162F
- Codeacademy Logo on hover = #3a10e5
- Search icon, 'Log In', and collapsed menu (mobile and tablet screen size) on hover = #3a10e5
- Sign up Button, text color = #ffe2ff
- Sign up Button, background color = #5533ff

#### Effects 
- Code academy logo on hover changes from grey to #3a10e5
- Hovering over an item, a tooltip with a description is shown next to the icon 
- Buttons on hover changes text color and shows a padding around each element
- Search icon and 'Log In' also change to the hovered color and have a padding around them 
- Desktop View, the navigation buttons also change text color and show a padding around each hovered element 
- Mobile and tablet screen sizes changes the collapsed menu icons text color and shows a padding around each element
  
## Article 1
### Carousel 
#### Colors 
- Button selected = #10162f
- Button on hover = #e2d6cf
- Button background = #fff0e5

#### Effects 
- Original carousel image (first button selected) set a Background image = '/images/sections/
- Desktop view, add a button on the end of the buttons, allowing pausing and playing the carousel 
- On any view, clicking one of the five buttons changes the background carousel picture and the text on the heading and two paragraphs within the carousel
- Hovering over a carousel button, shows a darker color and a small padding around 
- Border radius applied on the button container 

### Register an account
#### Colors 
- Title color = #10162f, bolded
- Text Colour = #10162F
- Any other text color = #10162f
- Input element when selected border color = #3a10e5
- Input element, error color (email already taken, password not strong enough) = #be1809
- 'Sign Up' Button background color = #3a10e5
- 'Sign Up' Button text color = #ffffff
- 'Sign Up' Button on click event = #fff0e5, transparent
- Terms and conditions text color = #2b3045
- terms and conditions hyperlink colour = #3a22e5, underlined 
- Terms and conditions hover color = #3a22e5, not underlined
- 'Or sign up using' text color = #10162f
- 'Or sign up using' background color = #ffffff
- 'Or sign up using' on hover background color = #e2d6cf

#### Effects 
- Hyperlinks in the terms and conditions are normally underlined, when clicked they loose the underline, color does not change 
- Input elements change to show which element is active
- 'Sign Up' button looses background color when clicked, shows it has been clicked
- 'Or sign up using' on hover darkens the third party providers color 

## Article 2 - Questionnaire, 'Find what's right for you'
### Colors 
- Background Image = '/images/sections/
  - Content has a large margin around so both the image and color can be seen 
- Background color = #fff0e5
- Title color = #10162f
- Text color = #2b3045
- Border around categories = #cec4c1
- Background color of categories = #ffffff
- Background color of categories when hovered = #f5f5f5
- Buttons, enabled, background color = #8a858c
- Buttons, disabled, background color = #beb4b3

#### Effects 
- Category when hovered is dimmed and a darker color is used, shows interactivity
- This section is a questionnaire, this is the initial screen, once an element is selected, button number 1 is greyed, button 2 is now lighter and shows a new selection of answers, this goes on through three different screens 
- The buttons show which stage of the questionnaire the user is at

## Article 3 - Selection of courses available 
### Colors 
- Title color = #ffffff
- Background color = #10162f
- Free course banner background color = #eafdc6
- Career course banner background color = #10162f
- 'Explore full catalog' background color = #cca900
- 'Explore full catalog' text color = #10162f
- Catalog options border top color = ffffff

### Effects
- Able to click on a course category, the courses are refreshed and shows courses relevant to that category
  - Mobile and tablet, the courses are shown under the course category
  - Desktop, the categories are between the title section and the courses and are shown in a row
- Hovering over a course, applies a transform effect where a second box is created behind put slightly to the left and below the course itself
- 'Explore full catalog' on hover changes the background color to a darker color 
- Bottom right of the media is a play/pause button, adds interactivity to the media 

## Article 4 - Showcasing their learning method, 'Hand-on learning'
### Colors 
- Background color = #10162f
- Title text color = #ffffff
- Inactive section text color = #afb1b9
- Active section background color = #262b42
- Active section title text color = #ffffff
- Active section paragraph text color = #b3b5bd
- 'Get started' text color = #10162f
- 'Get started' background color = #cca900
- 'Get started' on hover background color = #ffd300
- 'Explore features' text color = #ffd30a
- 'Explore features' background color = #10162f
- 'Explore features' on hover background color = #262b42

### Effects 
- Clicking on a section, replaces the initial picture/video with a relevant image/video
- Clicking on a section, darkens the others and lightens the selected/clicked section
- Clicking on a section, reveals a text paragraph below the active section title, all other description paragraphs are hidden 
- Clicking 

## Article 5 - Career Checker Section, 'Job Readiness Checker'
### Colors 
- Background color = #fffae5
- Media border color = #262835
- Title text color = #10162f, bolded
- Paragraph text color = #10162f
- 'Try it out' background color = #fffae5
- 'Try it out' text color = #3a10e5
- 'Try it out' on hover = #e2dfcf

### Effects 
- Interactivity on the button, shows if the button/link is hovered
- Bottom right of the media is a play/pause button, adds interactivity to the media 


## Article 6 - Showing partnerships, code academy helping to engage organizations to reach their goals with technical training
### Colors 
- Background color = #10162f
- Title text color = #ffffff
- Paragraph text color = #ffffff
- 'Explore business plans' background color = #ffd300
- 'Explore business plans' text color = #10162f
- 'Explore business plans' on hover background color = #cca900
- Organizations logo color = #acaeb6

### Effects 
- 'Explore business plans' darkens when hovered

## Article 7 - Stories and personal accounts for using code academy, 'Stories from real people'
### Colors 
- Background image slighly used at the top of this section = 'images/
- Background color = #fff0e5
- Title text color = #10162f
- Paragraph text color = #10162f
- Individuals story border = #000080
- Individuals story title text color = ##10162F
- Individuals story paragraph text color = ##10162F
- Individuals story text color on hover = #3a10e5
- 'Explore more stories' text color = #3a45e5
- 'Explore more stories' background color = #fff0e5
- 'Explore more stories' background color on hover = #e2d6cf, with padding 

### Effects 
- Hovering over an individual changes the black text to the hovered color of blue 
- 'Explore more stories' on hover darkens and shows it is being hovered on

## Article 8
### Colors 
- Background color = #ffd300
- Title text color = #10162f
- Paragraph text color = #10162f

### Effects
- Not applicable  

## Article 9
### Colors 
- Background color = #3a10e5
- Title text color = #ffffff
- Paragraph text color = #ffcef3
- 'Sign up' background color = #ffd300
- 'Sign up' text color = #10162f
- 'Sign up' background color on hover = #cca900

### Effects 
- Mobile and Tablet, only one image is shown on the left. On Desktop, the left column un-hides the second image
- 
## Footer 
















































# 4. Media queries - mobile, tablet and desktop versions 
### Pixel details 
| Screen Size | Minimum Pixel Size | Maximum Pixel Size | 
|:---:|:---:|:---:|
| Mobile | 0 | 490px
| Tablet |  | | 
| Desktop | | |