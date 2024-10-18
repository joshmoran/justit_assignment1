# Just IT - Assignment 1

# README & IMPORTANT - How this document is formatted
> Throughout I will be discussing specific sections / areas

> To review, please refer to "Chosen website - codeacademy - EDITRED.jpg"

> In the folder 'Task 2 - Analysis and Design' Please find a complete screen view for 
> - Mobile view
> - Tablet View 
> - Desktop 

# Index System
1. Assignment Task
2. Webpage breakdown 
3. Colors and fonts
4. Media queries - mobile, tablet and desktop versions 
  
# 1. Assignment 1 
## WEBSITE CLONE PROJECT:
### Objective ###
Utilize your HTML and CSS skills to recreate the landing page of a website of your choice. This project is an opportunity to deepen your understanding of web design and development. 

## Task Details:
1. Selection of Website:
   -  Choose a website with a landing page that you find visually appealing and technically interesting. 
   -  Ensure that your chosen website is complex enough to challenge you, but not so advanced that it becomes unmanageable with your current skill set.
2. Analysis and Planning:
  - Structure and Design: Analyze the structure of the website’s landing page. Identify the HTML elements used and their arrangement. Consider the page layout, navigation elements, headers, footers, and any unique sections.
  -  Styling: Pay attention to the CSS properties that contribute to the visual design. Note the fonts, colors, spacing etc.
  -  Developer Tools: Use the browser's developer tools to inspect the page. This can provide insights into the HTML structure and CSS styles. For example, Chrome's CSS Overview can reveal details about fonts and colour schemes used.

1. Development:
• HTML: Create the HTML structure based on your analysis. Use semantic HTML to ensure your code is accessible and meaningful.
• CSS: Apply CSS to style your page. Try to replicate the original design as closely as possible.
• Focus on Visual Design: Your task is to replicate the visual design and layout. You are not expected to recreate any backend functionality or add additional pages. Interactive elements should be limited to what can be achieved with HTML and CSS
(e.g., hover effects). 

## Stretch Goal:
Try to implement responsiveness into your design with media queries.

### Useful links: ###
• https://cssgradient.io/
• https://animista.net/
• https://scrollbar.app/
• https://www.cssportal.com/css-clip-path-generator/
• https://favicon.io/favicon-generator/
• https://hype4.academy/tools/glassmorphism-generator

# 2. Web breakdown 

## Header - Banner and Navigation
### Banner 
- Shown on all screen types
- Information on the most recent update / notification / discount 

### Navigation
- Objects that do not change, in order (left to right): 
  - Left side
    - Code Academy logo is always to the left of the screen
  - Right Side
    - Search icon
    - Login button
    - Sign up button
- Variation depending on the screen type 
  - On Mobile and Tablet, the navigation strip is removed and a collapsed icon is added to the far right on the navigation bar, right of the sign up button
  - On Mobile and Tablet, the entire options is shown to clicking the collapsed icon and a full screen view of the navigation can be seen and interacted with
  - On Desktop, the navigation is shown between the logo and the search icon 
    - Collapsed button is removed 
    - Drop down menus are enabled with hovering 


## Article 1 - Carousel and Register Form
### Carousel 
- Format has a very slightly variation, but overall the structure and how it looks, does not change
  - On desktop, an extra button is added to the five buttons on the right of the buttons, allowing the user to pause or play the changes between the buttons 
- Content of the carousel heading, two paragraphs and the carousel picture changes depending on which of the buttons are clicked, each buttons changes these four elements respectively 
- Using JavaScript allows the transition of the elements as well as adding a timer function to switch between buttons/scenes once it hits a certain time span
- Buttons to change the carousel scenes and the structure of the three text areas and background picture does not change

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

## Article 3 - Selection of courses available 
- Slight variation on format, style and sizing 
- Heading and a small paragraph are at the top of the article
- Their is a category of areas that a user can view some of the courses they have for those areas
  - On Mobile and Tablet, you click the area and a limit of 4 courses are inserted below the clicked heading
  - On Desktop, all categories are above the content, clicking on the categories remove the content and add the relevant categories content below the categories

## Article 4 - Showcasing their learning method, 'Hand-on learning'
- Heading and small paragraph above always stay at the top, centered 
- The content (image and selection boxes) vary to screen size
  - On Mobile, the image and selection boxes are in a column, image at the top
  - On Tablet and Desktop, the image and selection boxes are in a row, image to the right and selection boxes to the left
- Content boxes once clicked reveal and un-hide the paragraph below the categories
  - When a heading it clicked, all other paragraphs descriptors are hidden 
  
## Article 5 - Career Checker Section, 'Job Readiness Checker'
- Slight variation of the format, style and sizing 
- Content is split into two boxes: an image (Job Ready Checker) and details (heading, paragraph text and a link)
  - On Mobile, the boxes are in a column, image on the top and details on the bottom
  - On Tablet and Desktop, the boxes are in a row, image on the left and details on the right 

## Article 6 - Showing partnerships, code academy helping to engage organizations to reach their goals with technical training
- Slight variation of the format, style and sizing 
- Content is split into two boxes: firstly showing partnerships: airbnb, amazon, daily motion and reverb and the second, the details (code academy teams logo, heading, paragraph text and a link )
  - On Mobile, the boxes are in a column, details is above and the partnership is on the bottom
  - On Tablet and Desktop, the boxes are in a row, details on the left and partnerships on the right 

## Article 7 - Stories and personal accounts for using code academy, 'Stories from real people'
- Variation of the format, style and sizing 
- Header and a small paragraph at the top always being centered, no matter the screen sizes
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
- The parent container is always in a row, no matter the screen size, but:
  - On Mobile, the statistics box is in a column
  - On Tablet and Desktop, the statistics box is in a row

## Article 9 
- Variation of the format, style and sizing
- Content is split into two boxes: firstly with two pictures, each a different person and the second box is details containing a header, paragraph text and a link
- The container is always in a row with each box aligning in a column
  - On Mobile, the second image in the first box is hidden
  - On Tablet and Desktop, the second image is revealed and the two images are displayed in a row

## Footer 
- Variation between the structure and format; text, links, logos, the content does not change
- Footer can be best understood in the Tablet or Desktop view, the footer is split into 3 specific containers
  - At the top of the footer is two containers in a row, 
    - Left side = company, social media links, resources, support, plans, community
    - Right side = subjects, languages, career building, catalog, beta content, mobile app store links 
  - At the bottom of the two in a row is a container which spans the full with of the webpage = Privacy policy, cookie policy, do not sell my information, terms, logo and copyright printed
- Depending on the screen size, depending on how it flows
  - On Mobile, all three containers are stacked in a column
  - On Tablet and Desktop, the top two containers are in a row, whilst the bottom is below and is the full width of the parent

# 3. Colour and fonts 
> I used 'Microsoft Power toys - Color Selector' Feature to get these colors 

## Fonts 
- On Body and Div = font-family: "Apercu",-apple-system,BlinkMacSystemFont,"Segoe UI","Roboto","Ubuntu","Cantarell","Fira Sans","Droid Sans","Helvetica Neue",sans-serif;

## Header 
- On Mobile, the header is always fixed a the top of the page 

### Banner
#### Colors 
- Background Color = #10162f
- Text Colour = #ffffff
- 'UPSKILLNOW' text color = #ffd300
- 'UPSKILLNOW' hover text = #262b42

#### Effects
- 'UPSKILLNOW' on hover fades the background color and applies a lighter shade
- An image of a cross is on the right, which allows the user to close the banner, then it is saved in to browsers cookies to store their response 
  
### Navigation
#### Colors
- Background color = #fef0e5
- All elements, except sign up button text color = #151725
- All elements, except sign up button text on hover = #3b09ec
- Sign up Button, text color = #fff
- Sign up Button, background color = #3b09ec
- Sign up button, on hover = #5533ff

#### Effects 
- Code academy logo on hover changes from grey to the hovered colour 
- Hovering over an item, a tooltip with a description is shown next to the icon 
- Buttons on hover changes text color and shows a padding around each element
- Search icon and 'Log In' also change to the hovered color and have a padding around them 
- Desktop View, the navigation buttons also change text color and show a padding around each hovered element 
- Mobile and tablet screen sizes changes the collapsed menu icons text color and shows a padding around each element
  
## Article 1
### Carousel 
#### Colors 
- Background image = 'Task 2 - Analysis and Design/layers/article1 sprite grid.svg'
- Title, text color = #0c1330
- Title, background color = #fbf1e8
- Two paragraphs, text color = #deede6
- Two paragraphs, background color = #000000
- Two paragraphs, plus icon = #bfbab6
- Button active background color = #06152f
- Button inactive background color = #fbf1e8
- Button inactive border color = #06152f
- Button on hover = #e2d6cf

#### Effects 
- Original carousel image (first button selected) set a Background image = '/images/sections/
- Desktop view, added an extra button on the end, allowing pausing and playing the carousel, with the relevant image to go with the current state
- On any view, clicking one of the five buttons changes the background carousel picture and the text on the heading and two paragraphs within the carousel, each buttons changes all four elements
- Hovering over a carousel button, shows a darker color and a small padding around 
- Border radius applied on the button container 

### Register an account
#### Colors 
- Background color = #fff4e6
- Title text color = #15062f
- Required text color = #321515
- Label text color = #43423c
- Input border = 2px solid #000
- Input border on focus = 4px solid #3a10e5
  Input border error color (e.g. email already taken, password not strong enough) = #be1809
- Sign up button background color = #3a0ce4
- Sign up text color = #15062f
- Sign up background color on hover = #15062f
- Sign up background color on active state = #fff0e5
- Terms and conditions text color = ##7e6467
- Terms and conditions hyperlinks text color = #3f246d underlined
- Terms and conditions hyperlinks text color on hover  = #3f246d non-underlined
- Providers title text color = #241506
- Providers background color = #e2d6cf
- Providers background color on hover = #10162f

#### Effects 
- Hyperlinks in the terms and conditions are normally underlined, when clicked they loose the underline, color does not change 
- Input elements change to show which element is active
- 'Sign Up' button looses background color when clicked, shows it has been clicked
- 'Or sign up using' on hover darkens the third party providers color 

## Article 2 - Questionnaire, 'Find what's right for you'
### Colors 
- Background Image = 'Task 2 - Analysis and Design/layers/article2 sprite.svg'
  - Content has a large margin around so both the image and color can be seen 
- Background color = #fef0e5
- Title color = #111325
- Text color = #6d5968
- Sub text color (What do ypu want to learn about) = #11132a
- Border around answers = #5a5657
- Answer text color = #3f3d47
- Background color of answers = #ffffff
- Background color of answers when hovered = #5a5657
- Button border  color = 1px solid #171120
- Buttons, active border color = 1px solid #171120
- Buttons, inactive border color = 1px solid #686672

#### Effects 
- Category when hovered is dimmed and a darker color is used, shows interactivity
- This section is a questionnaire, this is the initial screen, once an element is selected, button number 1 is greyed, button 2 is now lighter and shows a new selection of answers, this goes on through three different screens 
- The buttons show which stage of the questionnaire the user is at

## Article 3 - Selection of courses available 
### Colors 
- Background color = #0c132f
- Title color = #ffffff
- Text color = #fff
- Course free course banner background color = #eafdc6
- Course free course banner text color = #000
- Course career path banner background color = #fff
- Course career path banner text color = #000
- Course background color = ##ffffff
- Course text color, title and text = ##000
- Course border color = 2px solid #151515
- 'Explore full catalog' background color = #ffd300
- 'Explore full catalog' text color = #0f2000
- 'Explore full catalog' background color on hover = #fef0e5
- Catalog options border top color = #effefb
- Line color (at bottom) = #848a97
- Title text color (at bottom) = #effefb

### Effects
- Able to click on a course category, the courses are refreshed and shows courses relevant to that category
  - Mobile and tablet, the courses are shown under the course category
  - Desktop, the categories are between the title section and the courses and are shown in a row
- Hovering over a course, applies a transform effect where a second box is created behind put slightly to the left and below the course itself
- 'Explore full catalog' on hover changes the background color to a darker color 
- Bottom right of the media is a play/pause button, adds interactivity to the media 

## Article 4 - Showcasing their learning method, 'Hand-on learning'
### Colors 
- Background color = #0c132f
- Text above title text color = #ffe1e1
- Title text color = #fffbf6
- Active section (AI-assisted learning) background color = #252941
- Active section title text color = #fff
- Active section paragraph text color = #fff
- Inactive section title text color = #a6b3b9
- 'Get started' text color = #251300
- 'Get started' background color = #fdd400
- 'Get started' on hover background color = #fffbf6
- 'Explore features' text color = #fdd400
- 'Explore features' background color = #0c132f
- 'Explore features' on hover background color = #fffbf6

### Effects 
- Clicking on a section, replaces the initial picture/video with a relevant image/video
- Clicking on a section, darkens the others and lightens the selected/clicked section
- Clicking on a section, reveals a text paragraph below the active section title, all other description paragraphs are hidden 
- Clicking 

## Article 5 - Career Checker Section, 'Job Readiness Checker'
### Colors 
- Background color = #fcfae3
- Image border = 1px solid #898579
- Paragraph above title (AI.... ) text color = #1a0f15
- Title text color = #151129
- Paragraph text color = #281515
- 'Try it out' background color = #fcfae3
- 'Try it out' text color = #3219ae
- 'Try it out' on hover = #e2dfcf

### Effects 
- Interactivity on the button, shows if the button/link is hovered
- Bottom right of the media is a play/pause button, adds interactivity to the media 

## Article 6 - Showing partnerships, code academy helping to engage organizations to reach their goals with technical training
### Colors 
- Background color = #0c132f
- 'Teams' text right of code academy logo = #fff
- Title text color = #ffffff
- Paragraph text color = #ffffff
- 'Explore business plans' background color = #fdd400
- 'Explore business plans' text color = #251c00
- 'Explore business plans' border = 2px solid #261700;
- 'Explore business plans' on hover background color = #ffffff
- Organizations logo color = #acaeb6

### Effects 
- 'Explore business plans' darkens when hovered

## Article 7 - Stories and personal accounts for using code academy, 'Stories from real people'
### Colors 
- Background color = #fff0e5
- Title text color = #13172d
- Title paragraph text color = #300c1c
- Individual story image border = 1px solid #0c0329
- Individual title text color = #0c0c2e
- Individual paragraph text color = #210c29
- Individual hover color = #3f0fc3
- Explore link text color = #fff0e5

### Effects 
- Hovering over an individual changes the black text to the hovered color of blue 
- 'Explore more stories' on hover darkens and shows it is being hovered on

## Article 8
### Colors 
- Background color = #ffd300
- Title text color = #0f1511
- Paragraph text color = #0f1511

### Effects
- Not applicable  

## Article 9
### Colors 
- Background color = #3a0ce4
- Title text color = #fffdff
- Paragraph text color = #e9fcff
- 'Sign up' background color = #ffd200
- 'Sign up' text color = #1c1f00
- 'Sign up' background color on hover = #6049e5

### Effects 
- Mobile and Tablet, only one image is shown on the left. On Desktop, the left column un-hides the second image
- 'Sign up' button dims and darkens when the user hovers on it
- 'Sign up' a white border is added around when the button is clicked

## Footer 
### Colors 
- Background color = #fef0e5
- Text colour = #060c13 
- Text colour on hover and clicked = #6049e5
- Logo Colors = #0f1529

### Effects 
- Links in the footer, change from grey to blue, on hover and clicked state 
- Store links links and refer to the app on the relevant app store

# 4. Media queries - mobile, tablet and desktop versions 
### Pixel details 
| Screen Size | Minimum Pixel Size | Maximum Pixel Size | 
|:---:|:---:|:---:|
| Mobile | 0 | 490px
| Tablet |  | | 
| Desktop | | |