# Lab-01 SMACSS and Responsive Web Design

### Overview
In lab today, you will be building a single responsive web page based off of the provided design comp assets. These contain images of what you are striving to build in HTML and CSS, so be sure to open them up and keep them handy, but note that they are not for actual use on the page. You can also print out these comps and use them to mark up and sketch out page structure.

Your document must be designed in a mobile-first approach and must be responsive when the screen size changes and the page is refreshed. The details of the media query specifications are up to you, but your breakpoint must be at 768 pixels.

### Instructions
- Create a new repository named lab-01.
- Work on a non-master branch.
- Use good HTML structure to scaffold this site, using semantic elements where possible.
- Container elements (a box outside of your content box that might contain multiple content boxes) are very useful in managing layout. You will need to think about the relationship between parent and child / descendant elements as well as the order in which you place them in the HTML. Be thoughtful about your layout strategy.
- Add a reset.css file to your project, like this one.
Use SMACSS-style modularity to organize your CSS.
- Style the page using float-based layout to reflect the comp images provided as closely as possible. The only text you should have in each box is the identifying letter, which should be centered horizontally and vertically.
- For the desktop view, the content should be inside of a channel that is a maximum of 960 pixels wide and is centered on wider screen sizes.
- Each box should have a unique background color in mobile view and in desktop view. We are not working with jQuery events yet, so these changes should be observed when the screen size changes and the page is refreshed.

# References

I was getting an space betwwen elements when using the display inline-block. I searched the web and found this. I used this for the div's in sections 2 and 3. Later on I when I was working on the desktop version, I learned that I could have use a float left on the divs. 

https://css-tricks.com/fighting-the-space-between-inline-block-elements/

# Author 
- Chuck Li Villalobos

# License
- This project is licensed under the MIT License. 