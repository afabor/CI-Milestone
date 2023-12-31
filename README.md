# SneaKlean Premium Sneaker Cleaning Service.

This website was creating using Bootstrap.

The idea of creating a website that fulfils a much needed niche in the sneakerhead community is a passion point of mine.

This website can be used for all types of shoes but the main audience would be people in the sneaker community as they frequently run into issues with shoe maintenance.

# Table of Content

1. UX

   - Project Goals
   - Business Goals
   - User Story
   - Wireframes

2. Features
3. Technologies Used
4. Testing
5. Deployment
6. Credits

# UX

## Project Goals

The primary objective of this project was to display the services that we offer to customers within the sneaker community at large.

This has generally been quite an untapped market and one with no large scale competitors.

In order to differenciate our online presence from being exclusively on social media, using a website adds a level of formality that I have no seen displayed by competitors.

Our audience is mainly going to be of the younger generation, so striking images and clear to read titles are going to draw them in more than larger lines of text. Utilising necessary imagery also helps the audience know whether this is a service they can associate with and benefit from.

## Business Goals

From the perspective of the business, the main goal would be to increase online presence and have further reach.

As previously mentioned, other competitors mainly operate through social media and do not have a formal means by which to communicate with their business. This gives a neutral platform by which anyone can make an order with our business.

Having more orders processed through the website also creates a better focus on the business as they wouldn't have to sift through direct messages on all platforms. Centralising all communications through the website and business email would create less stress for processing orders, especially in the events of high volume.

## User Story

### As a user aged 16-30 with an interest in sneakers, I want to:

    - Be able to view the services being provided by the business.
    - See sneakers that are relevant to current fashion trends.
    - Be able to view their other social media accounts to further investigate.
    - Have a visual representation of the service being provided.
    - Have an understanding of how to use the service.
    - Be able to navigate around the page effectively.
    - Not have to read to much to understand what is being provided.

All of these things collectively will let a user know whether this a service they need currently or may use in the future.
The visuals of the website itself should bring more traction to other parts of the business, namely social media and Instagram in particular would give users access to a portfolio of images showing the work we have done with our clients.

## Wireframes

![Main Page Wire Frame](./assets/images/dt-frame-head.png)
![Content Wire Frame](./assets/images/dt-frame-content.png)
![Mobile Main Wire Frame](./assets/images/mb-frame-head.png)
![Mobile Content Wire Frame](./assets/images/mb-frame-content.png)

# Features

The main features that were added to this website was a carousel that walks through the essense of our business and the services that will be provided.

There was also information provided as to how they can use the service and it directs you further down the page with a button.
From there, you mainly get some more explanations and imagery surrounding how our business operates and the different way in which you can use our services.

An added benefit of this page is that you can effectively use every page on the screen without ever having to scroll on a desktop.
Every page you will ever need is made accessible via buttons that smoothly take you to the relevant parts of the website.
As everything is located on one page and not multiple pages, it condenses the total user experience and you understand the purpose of the website once you open it.

## Bonus Features (not yet added)

One additional feature that I would have liked to add to this project would have been a gallery page showing some before and after images using a carousel slider to give users additional visuals of the services provided.

If this were a real business, it would likely be a preview of what had already been posted on social media sites, Instagram in particular, in order to draw users into following our other pages and keeping up to date with us.

I would have also liked to have added a button that can toggle between light and dark mode. This is a skill set that I have yet to acquire, but I greatly appreciate it on websites as it generally makes viewing a website more bearable. Especially on a brighter screened desktop.

# Technologies Used

This project was created using Bootstrap and was styled with some custon CSS.

I have used CSS and SCSS in the past, so using Bootstrap as a different means of layout definitely took getting used to. The grid system in Boostrap seems quite intuitive in how it works. On top of the lessons provided, I also looked at the Bootstrap docs as well as some YouTube videos to gain a further grasp on how to effectively utilise Bootstrap.

The convenience of certain components being a part of Bootstrap made it much easier to create parts of my page including the carousel as well as the cards used on two of my pages.

The icons I used were also from Bootstrap and Font Awesome.

Wireframes were made using Figma.

# Testing

## Validating my Code

To ensure that my code was free of any bugs that I may have not been able to see first hand, I made sure to validate my code using W3C. I did this by address as well as the actual HTML and CSS code. My CSS had no issues, but my HTML had to go through some changes. These were mainly from trailing slashes that were created by my formatting tool that I use with VS Code and a small issue with my buttons being nested within an anchor tag in the services page. 

![W3C Validated By Address](./assets/images/wc3-validator-sneaklean.png)
![W3C Validated By HTML](./assets/images/w3c-validator-html.png)
![W3C Validated By CSS](./assets/images/w3c-validator-css.png)


## Client stories testing

Viewing my website from the clients perspective, I expect them to know what my business is about, the types of services we offer and how they can contact us to get a quote for our services. This generally leads them from:

- Home > About > Services > Contact

Within those, there are quick access buttons on each page to lead them to either the Contact page or Services page in one instant for ease of navigation. The logo on the top right also automatically leads to the home page.

The home page is one of the most intuitive pages, as it allows for a user to access each page on the website through each slide without necessarily having to use the navbar. With there being a small piece of information pertaining to the information they will receive on those pages, it allows users to be more intruiged to parts of the site that appeals to them the most. 

The structure with which the website was built makes in entirely possible to view all contents of this site without ever having to scroll the page. The use of bright and contrasting buttons that stick out to the user, make it that much easier to see more information about what is being sold.
 

## Lighthouse Summary

Mobile Lighthouse Summary
![Mobile Lighthouse Summary](./assets/images/Lighthouse-mobile-sneaklean.png)

Desktop Lighthouse Summary
![Desktop Lighthouse Summary](./assets/images/lighthouse-desktop-sneaklean.png)



## What Went Wrong - Including Bugs Discovered and Fixed

As I have worked with HTML, CSS and JavaScript before, working with Bootstrap was a completely new but good experience to have as a lot of things you may have to make yourself are made easier through Bootstrap.

However, not all my time using Bootstrap was smooth sailing as I am still having some issues with certain aspects of my page. In particular, when I change screen sizes, the consistency of my cards change due to there being more text in some cards than others. This causes some to be longer than others, although they never go under each other and stay within their particular row.

This is defintely something that I would like to be able to quick fix so I will do further research into this topic.

Another issue I have had with this project is with media queries.

When I put my website on a smaller screen, the divs after the carousel all seeem to merge into one. The way in which I fixed this was by removing each page from having a height of 100vh and just gave them a minimum height of 300px. This was a really big discovery as my screens would only work cohesively until a certain breakpoint, before they all started to merge into one.

I had also faced and issue with getting my carousel to slide on its own, without having to press the individual buttons to get it to slide. The slide class should work in Bootstrap, but this may be another thing that I have to work out.  



## What Went Well

On the brighter side, the website in full desktop size looks great and all the components work and flow as intended.

Everything from top to bottom is extremely readable and there is a clear direction in which the website goes.

Using Bootstrap for the carousel really simplified what I would have had to do otherwise so it was greatly beneficial.

I had experimented a lot with the grid system, seeing the sorts of layouts I could implement into my rows but generally opted for the more even look as it was easier to grasp visually.

# Deployment

This projet was developed using Visual Studio Code, committed to git and pushed to GitHub using the terminal built in Visual Studio Code.

To deploy this website to GitHub Pages from its [GitHub Repo](https://github.com/afabor/CI-Milestone), the following steps were taken:

1. Log into GitHub
2. From the list of repositories on the screen, select afabor/CI-Milestone.
3. From the menu items near the top of the page, select Settings.
4. Scroll down to thte GitHub Pages section.
5. Undeer Source, click the drop down menu labelled None and select Master Branch.
6. On selecting Master Branch, the page is automatically refreshed and the website is now deployed
7. Scroll back down to the GitHub Pages section to retrieve the link to the deployed website.

This website has been deployed to GitHub Pages, using [this link](https://afabor.github.io/CI-Milestone/), you can view it for yourself.

# Credits

## Images

[Carousel Slide 1](https://unsplash.com/photos/hRmlaSdNwaA)

[Carousel Slide 2](https://unsplash.com/photos/kKObh7tUPNc)

[Carousel Slide 3](https://www.pexels.com/photo/two-unpaired-black-and-gray-adidas-sply-350-v2-1032110/)

## Code

Some code for [cards](https://getbootstrap.com/docs/5.3/components/card/), [navbar](https://getbootstrap.com/docs/5.3/components/navbar/) and [carousel](https://getbootstrap.com/docs/5.3/components/carousel/) were taken from the Bootstrap Docs.
