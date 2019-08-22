# README.md

## AC/DC Website

My project is a website for the popular rock bank, AC/DC. The website was created so that both existing fans and people discovering the band for the first time have easy access to their popular music videos, a list of their popular albums and songs, tour dates, information about the band and their latest social media posts. 

The website was designed so that both people who are familiar with the band and newcomers find it useful and interesting to browse. The main page that a user first sees shows a slideshow with some iconic moments in the bands history, notably their live shows. Since the website is a single page the user then has the choice to begin scrolling through the website, or they can click a section they're interested in on the navigation bar at the top of the page. If the user decides to scroll through the website they are first presented with 5 mmusic videos. This is very important because it allows someone discovering the band to very easily and quickly discover some of their music and see if they'd be interested in the band. Once they scroll past that section they are shown several of the band's main albums, along with a list of their top songs. This further allows someone to discover their music but also allows someone who is familiar with AC/DC to simply listen to their favourite songs. These keep playing as the user browses the website. Avoding autoplaying music was important to limit ruining the user experience. If the user is interested in the music that they hear they can scroll a little further and read about the band. This is a very short section which is followed by their latest tour dates, with links to buying a ticket to a specific show. Finally, the user is shown several social media posts. A social media presence is important in this day and age and this reassures the user that the band has an active social media presence. 

Placeholder songs were used on the website to avoid havinng to purchase/illegally download the music. 

## UX

This website is both for fans of the band looking to listen to some music and book tickets, and people who've head about them and are interested in learning about the band and discovering some of their greatest hits. The website also provides links to their social media pages if the user is interested in following them on their platform of choice. 
- A newcomer wants to watch a music video to their most popular songs. They go on the home page and click the "videos" tab, or scolls down a single section. 
- A newcomer wants to listen to their music and plays it in the background while reading about the band by playing it in the "music" section.
- An existing fan wants to book a ticket to go see one of their shows live but isn't sure if they're going to be playing near them. They can check the "schedule" section on the website. 
- A fan is interested in buying some cd's and want to make sure to support the band by buying them directly instead of going through spotify or amazon, they click the "shop" section. 
- As a fan I want to see if they have a social media presence. I click the follow tab and am presented with the latest posts and links to their several social media pages.

### Mockups

[Here](https://github.com/DanielJMaia/milestone-project-1-band/blob/master/assets/Mockups/Starting%20Ideas.png) is the link to the original idea for the look of the website  Done in microsoft paint. Vast improvements needed in the future. 


## Features

### index.html

- Interesting slideshow as a front page showing pictures of the band playing live. This instantly gives an idea of what they look like, and the energy they create when performing. 
- Five music videos to give users an idea of the range of music this band creates, while highlighting that they are a rock band that has stood the test of time since some are quite old. 
- Albums and songs are readily available if the user is very interested in going further in discovering the band's music. 
- About us section which provides some basic information about the band's history. 
- Tour dates organised as a easy to view table which provides a simple user experience which easy access to the booking page as to avoid confusing and potential scam websites offering fake tickets. 
- Social media page so that the user can easily follow the band on their preferred platform. 

### shop.html

- Simple online store for people interested in buying albums and merch. The albums sectiion is the same as on the main page, and the merch is displayed in a bootstrap carousel. 

## Features to add in the future

- Nice scrolling animation when using the navigation bar instead of jumping to the section. 
- Similar scrolling when using the navigation button to go back to the very top of the page.
- More in-depth forms for booking tickets, and additional pages for each album. Pop up notification to confirm tickets have been booked. 
- Additional JavaScript to make the website feel more professional such as improved slideshow, animations as the user scrolls through the page.
- Each album should link to the spotify page for that album when clicked. 

## Technologies Used

### HTML

This was used to create the markup. 

### CSS

This was used to style the webpage. [Bootstrap](https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css) was the mobile-first framework that enabled the website to be responsive using the grid layout.

### Validators

When the website being developed the both the HTML and CSS was validated using the W3 "Jigsaw" [validation](https://validator.w3.org/) 

## Testing

The pages were at the various screen sizes available in Chrome Dev Tools.

### index.html

- Click all the links on the navigation menu to ensure that they work regardless of screen size, including the up arrow in the bottom right.
- Ensure the slideshow works in all browsers.
- Ensure that the music videos play even on a very slow computer by using chrome dev tools to throttle performance. 
- Accessed website on Firefox, Chrome and Edge.
- Ensured all the songs are working.
- Ensured all the "book now" buttons in the schedule section linked to the appropriate pages.
- Clicked on all the social media posts to make sure the embeds were working correctly. Repeaped once again for the youtube videos too.

### shop.html

- Made sure carousel works correctly.
- Clicked all the links to ensure that they led to the correct amazon page.

### Problems Encountered & Self Reflection

- Initially I used several custom containers and redundant CSS classes which ended up clashing with the bootstrap. As my project grew I ended up removing large amounts of CSS. This was due to not having the correct mobile-first mindset when approaching the project. I have since learnt the importanece of the mobile first approach from the very beginning, but there is most likely still some redundant CSS. 
- The carousel at the beginning wasn't working correctly and required some knowledge of JQuery to fix. I instead chose a very simple bootstrap carousel without controls. From then on I always looked at the bootstrap framework to see if they provided classes for what I needed before trying to create them myself.
- Youtube embeds were very difficult to resize, and I ended up having to push them apart manually with CSS right and left properties to get them to have nice spacing on screens above a certain size. Changing padding and margins ended up resizing the videos very strangely. 
- Social media posts don't look as nice as they could, with each embed having different sizing properies. In the future I will most likely link to the social media page instead of trying to display elements from it on my website. 
- I could have added a contact-us page as practice even though it wouldn't really make sense for a band like AC/DC. 
- The conscious decision to not include a footer might make the website unprofessional, but I didn't see any additional value brought by including it. The next website I create will be designed with the idea of adding a footer with important information such as copyright information and social media links.
### Mobile First Approach

Each page was tested using chrome dev tools. The device presets used were iPad Pro, iPad, iPhoneX, iPhone 6/7/8 + Plus equivalent. Pixel 2 XL, Pixel 2 and Samsung S5.


## Deployment 

To deploy my project I pushed my AWS Environment to my Github repository named milestone-project-1-band via the command line. I did this every time I changed something in my code, although to begin with I didn't do it as often as I should have resulting in poor version documentation. I have since learned the importance of pushing all changed to GitHub no matter how insignificant. Please find my GitHub [here](https://github.com/DanielJMaia/milestone-project-1-band).

## Credits

### Content

- About us section taken from their [Wikipedia Page](https://en.wikipedia.org/wiki/AC/DC)
- 

### Media Locations

### Acknowledgements and Thanks

- Thank you to my tutor, Antonija Simic, for their help guiding me along the right path and sending me several extremely useful links regarding embeds, mobile first approach, padding vs margins and pixels vs rems vs %. These were all areas I was unsure in when beginning my project.
- Thank you to Neil Kavanagh for sending me emails and making sure I was getting along with the course even when I had to take a significant break due to personal reasons. I greatly appreciated their patience. 