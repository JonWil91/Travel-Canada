Milestone Project 1

# Travel Canada Website

The website can be found at [Travel Canada](https://jonwil91.github.io/milestone-1/)

This website is my first project after the culmination of studying the fundamentals of HTML, CSS, and responsive design.

I have a personal history of having lived and worked in Canada on a 2 year working visa and I wanted to create a website for anyone who was considering a similar decision. The website provides a simple landing page announcing the purpose of the website, an overview of what seasonal life would be like in winter and summer, a step by step approach for attaining a working visa and what to expect when making the move to live in Canada, and a contact page is available for any additional information a user may require.

## UX

This website was developed for anyone who is searching for information regarding getting a Canadian working visa. As such, the landing page is simple and open as the intention of the website was to make the purpose very clear from the start. The idea behind the website was to guide the user from the home page which includes a brief sentence explaining my relevent knowledge of the subject, onto the seasonal page with pictures I have taken myself alongside informative text about winter and summer life in Canada. This is followed by a timeline image giving a step by step approach for attaining a visa and what to expect of Canadian living. The final page is a simple contact form in case there was something a user failed to learn after visiting the website.

The seasonal page is largely opinion based as the text is based purely on personal experience and exists to give an account of someone who has had the time to experience the vast differences in lifestyle and living conditions of winter and summer. This page is responsive and allows users to read or hide text so it doesn't take up the whole page. This page was written in a blog style of wishing to inform and give an idea of what living in Canada could be like.

The website was designed with the idea that it would be something I would have found useful myself. There are links to a government website with details on what the user needs to look for, a working holiday company example with an explanation of the services they provided me and my personal opinion on them. As well as this there is information on health insurance, and a brief introduction into Canadian culture. This is all useful information I personally never encountered in one place, in a bite size display that is easy to disgest. This would be the first page a user would study for the essential information they need.

[Link to images folder to view wireframe initial sketches](https://github.com/JonWil91/Milestone-project-1/tree/master/images)

The final design of the website followed the themes from the sketches, but evolved upon viewing what worked best and looked best for the user on different devices. My mentor was also very helpful in pointing out the difference that it would make changing the seasonal page to stack the content for mobile and tablet, and for image and text content side by side on desktop. It was part of the learning process to produce more detailed wireframe work for future projects.


## User stories:

As a user, I want to be able to access any page within the website. This can be achieved by clicking any desired links on the navbar or the navbar brand Travel Canada for the home page.

As a user I want each page to have a clear purpose and be guided through the website with clear titles stating what each page's purpose is. 

As a user I wish to be able to access content for the website on any device and be able to view it clearly.

As a user I want to be able to ask questions on anything that was missed on the website on the contact page.

## Features

Every page has the following features:

* A navigational bar to navigate through the website's pages. This is operational as a dropdown menu for mobile devices.
* A navbar brand on the top left of the page to act as an addiional link to the home page.
* A footer with copyright information


### Index page:

The index page has a callout container with a background image that takes up the whole screen and declares what this website is for. This idea was inspired by www.simplesite.com

### Seasonal page:

The seasonal page layout is responsive to all devices. The images and corresponding text containers are stacked ontop of each other for tablet and mobile. The accordion effect is also implemented for text in mobile view to make browsing the page a nicer experience. On a desktop screen the images and corresponding text are side by side. These features give users an insight into my personal account of winter and summer life in Canada.

### Info page:

The info page has a simple timeline item layout to guide a user through the essential steps of attaining a Canadian working visa. On mobile and tablet devices this is all the information displayed. Desktop utilises more space with a Canadian flag image and additional information underneath. The timeline provides links to external tabs to guide them to sites they may wish to visit for more information.

### Contact page:

The final page utilises a simple contact form. There is no JavaScript used in this project so the information provided would not be sent to another server. But each form has a required element ensuring users don't mispell or misuse the contact box. If a user required further information or hadn't learnt something from the website they would be able to enquire here.

### Additional features to be implemented:

I have a video of my travels through Canada that I would like to add to the website. I would like to add pictures on the seasonal page to supplement each piece of text in the additional features section.



## Technologies Used

1. HTML
2. CSS
3. Cloud9 was the IDE used in the development of building this website.
3. Bootstrap4 was used to aid the development process in the layout and responsiveness of the website.
4. Google Fonts
5. Font Awesome
6. jQuery framework was used in conjunction with Bootstrap4 to refer to JavaScript technologies used to improve the efficiency of the website. It was used to make the navbar dropdown and the accordion effect on the seaonal page responsive for mobile users.


## Testing

1. Navigation links:
* Links in navigation bar all function and allow users to visit one page from another without any issue. The navigational bar is also mobile responsive and presents a dropdown menu
in the navbar. The navbar brand Travel Canada also allows users to visit the homepage from any page. 

2. Responsive Design:
* The website is employs mobile first design and allows users to view content as efficiently as possible via different viewing devices. This includes a navbar dropdown menu on mobile devices, blocking out the image on the info page for mobile and tablet devices,  and an accordion effect on the seasonal page to present the content more effectively. The default class is collapse, and if a user clicks the title the accordion effect taken from bootstrap is triggered revealing hidden content. Users can click the titles in the collapse show class to revert back to hidden content.

3. Contact form:
* If a user fails to enter details in the name form an error message appears telling to fill in this field.
* If a user fails to enter a valid email type in the email form an error message appears telling to fill in this field.
* If a user fails to enter details in the name form an error message appears telling to fill in this field.

The HTML and CSS code has been run through validators, and any errors found have been dealt with.

The website has currently been tested across multiple mobile and tablet devices, and the following browsers:
* Safari
* Chrome
* Firefox
* Opera

## Deployment

The website was developed using the cloud9 IDE, committed to git and pushed onto Github using the cloud9 Git Bash system. In order to deploy the site to go live on Gighub Pages the following actions were followed:

1. Log into Github.
2. Select Milestone-project-1 from JonWil91 repository
3. Select the settings option from the top right
4. Sroll down to GitHub pages, and select master branch as Source
5. Upon giving GitHub a few moments to complete the task, the website was refreshed and it was possible to select the live link for the website under GitHub Pages.



## Credits

### Content:

All text content contained in this project is original and was not copied from outside sources.

The navigation menu and responsive drop down that is present on all four pages was based on the project "Whiskey Drop" with Code Institute. This was modified and styled to suit the needs of my project, leaving only the navbar brand and four links pushed to the right.

The landing page style was inspired by www.simplesite.com, with the idea of a background image taking up the whole screen and little additional content to the page. The image used was a photo I took myself.

The layout for the seasonal page came largely from inital plans with esecially with words of advice and encouragement from my mentor. Both images included are photos that I took myself.

The info page took inspiration from the "Resume project" in the use of the timeline item, with it being modified to suit my needs of a step by step layout of content. The image used on desktop devices was taken from www.shutterstock.com. The idea behind the layout of the three divs at the bottom of this page on desktop devices was inspired by the "Whiskey Drop" project.

To supplement my content I used third party websites, which provided links to different tabs with the goal that the user should be able to view the additional website and be able to come back to mine easily. The following websites were used:

[SilverStar Mountain](https://www.skisilverstar.com/)

[Government website](https://www.gov.uk/foreign-travel-advice/canada/entry-requirements)

[Working Holiday Club](https://www.theworkingholidayclub.com/canada/)

[Travel Councellors](https://www.travelcounsellors.co.uk/gb/leisure)

[Canadian Affair](https://www.canadianaffair.com/blog/safely-responsibly-watch-wildlife-canada/)

### Disclaimer:

The content of this website is for educational purposes only.
