# GETTING STARTED

1. Download ZIP
2. `cd` into the folder
3. `npm install`
4. `npm start`
5. Should be able to view the site from `localhost`

# HOW I BUILT

1. I decided to use React to build this, because I think it's a great tool and I am always trying to gain a better understanding of how I could use it. 

2. I used CSS Flexbox to design the structure of the page, because I think it worked really well with the design layout given. 

###### Header

1. Built the structure of the nav links manually
2. Normally I would do this programmatically, but wasn't sure how the other links acted.. if they had sub-menus as well, but I would do so instead of manually adding HTML, you could just add more data, or if you were using something like wordpress it would work smoothly without having to look into the code. 
3. Imported logos for header/sub menu .. made sure there was `counter` for the `cart logo`
4. Toggled classes with a `onClick` function if the link had a submenu.. if not it would Route to the link provided

###### Body

1. Made the body have a scroll effect where the images were below the sections with white backgrounds using `background-attachment: fixed`
2. After the fact, I wish I made one or two components for each section and populated the HTML with `props`. This would make much cleaner code, and just makes the most sense. 
3. I made a `Button` component that only needed `text` to fill out HTML. In the future you could add actions, classes, etc. depending on the button and what it might do.
4. For the `JuiceMenu` and `Location` hovers, I built out components that looped through data containing an `image source`, `text`, `desc`, and `date` so you don't have to build multiple HTML hover divs. I also assumed this could be updated in the future, where more were added. Also, these could easily link to a page that is populated by the same data.

###### What I didn't get to 

4 hours went by pretty quickly so I didn't get to everything. Here is what I missed and what I would do with more time.

1. Make sure everything is mobile friendly.. especially the nav (would make a hamburger nav at a certain size), and the juice/location hovers towards the bottom (I would make these stack with flexbox and media queries). 
- A lot of it worked in mobile, but I would definitely go back and make sure everything looked clean and tidy, and also make sure it would for different browsers
2. I didn't have the correct font downloaded. Normally I do this first at the start so I don't have to think about it, but I didn't own the font given. 
3. The carousel effect on one of the sections. I was going to come back to the this and use `react-slick` to build it, but I ran out of time because I thought getting the rest of the page down was more important.
4. I didn't get to the footer unfortunately.

###### What I would do next

1. Fix for mobile
2. Make the nav menu build programmatically 
3. Make the `steps` in the second section of the body build programmatically
4. Clean up margin/padding sizes
5. Add a intro loader
