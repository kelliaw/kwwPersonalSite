# kwwPersonalSite

For code louisville final project

Thought/Work Process --
The goal of this project was to recreate (as best as I could) my personal website I developed about a year ago with wix - https://kelliwhiteweaver.wixsite.com/kelliwhiteweaver . All of the features and designs built for my Code Louisville project were inspired by the design choices I made on Wix, so that's really a lot of my rational for why I designed it the way that I did. It was quite a challenge to get items to align in the way that I wanted, and I relied heavily on the guidance from the Pluralsight demos and our mentors. I also utilized the resources that the Pluralsight videos referenced; W3Schools and the Mozilla Developer Network. I used Coolers.co to come up with a new color palate (I just really didn't like the one from my Wix website) and Adobe Spark to design my Favicon. I got my square, hamburger button, and social media icons from Font Awesome. I used Gimp to format my pictures and I used Squoosh.app to pare down the sizes on some of my images. My fonts came from Google Fonts. Unfortunately I couldn't find all of the exact ones used onn Wix but I mostly like the way they came out.

Page-By-Page Breakdown --
For the "About Me" page, I used Flexboxes to divide my picture and header content to be size by side. When the screen size changes, the alignment changes to be stacked on top of each other. My navbar changes into a "hamburger" button when the screen size gets smaller. When the links are highlighted, I used CSS to change the color. I used a similar Flexbox styling for my "CV" page, to divide each section into columns and rows. When the screen size changes, these sections also become stacked for easier readability. I was quite stumped for how to display my works in my portfolio, because my Wix page makes a carousel. I also didn't really think about how I would style that early enough in advance. Dawson shared a code for a carousel (and it was really awesome!), but I didn't feel like I had the time or knowledge to put it in my project. I really tried to make it work though. And I will make it work eventually! So instead of the carousel, I decided to utilize another Flexbox model to lay out the images and links to my works. It's not what I wanted, but it does the job. Finally, my contact form stumped me, I just could't get it to work right and I'm not sure if it's a security issue on my end creating the errors? I could not get console.log to show up in the Inspect tab on Chrome. I went with another project requirement for the validated form, and that is another area of growth for next time. 

Project Requirement Highlights --
MEDIA QUERIES -- If you look through my code, each page has several media queries. This is to ensure that my website content will move to be in alignment with small and large screens, and if necessary, medium screens also. 
CSS FEATURES -- I used Flexbox to organize content areas based on my wix website. This included setting two separate flexboxes with content on the "About Me", "CV", and "Portfolio" pages. When the screen size changes, the content is rearranged. 
JAVASCRIPT FEATURES -- I utilized Javascript to show/hide my navbar through clicking a button.
ONE EXTRA FEATURE -- I also have a navigation menu that expands and collapses based on screen sizes, and is opened and closed by clicking the "hamburger" option.




