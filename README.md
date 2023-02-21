# Cat that Got the Cream Cafe

## User Experience (UX)

 ### User Stories

#### First Time Visitor Goals
* As a first time visitor, I want to be able to easily navigate between the site pages.
* As a first time visitor, I want to see the range of cats available to visit and find out more about them.
* As a first time visitor, I want to easily view the menu to see the food available, opening times and how to get to the cafe.

#### Returning Visitor Goals

* As a returning visitor, I want to easily find social media links to see updated photos and information on the cats.
* As a returning visitor, I want to see if there have been any cats adopted or added since my last visit.

#### Frequent Visitor Goals

* As a frequent visitor, I want to check if the menu has changed or any items have been added.
* As a frequent visitor, I want to sign up to a newsletter for updates on the cats.

## Design
### Colour Scheme
* I have based the colour scheme around my hero image, the primary colours used are browns and creams.
### Typography
* I have primarily used the Poppins font with Sans Serif as the fallback in case of errors with importing fonts into the site.

### Imagery

## Wireframes
* [Index page wireframe](assets/images/wireframe-index-page.png)
* [Menu wireframe](assets/images/wireframe-menu-page.png)
* [Meet the Cats wireframe](assets/images/wireframe-cats-page.png)
* [Mobile wireframe](assets/images/wireframe-phone.png)

## Credit
### Code
* The hero image code came from [this Unsplash post](https://unsplash.com/photos/OjB_lkGKhX8).
* The images of the cats from the 'Meet the Cats' section also came from Unsplash, see links below:
    * [Harry](https://unsplash.com/photos/75715CVEJhI)

## Features
 * Interactive elements of the site.
 * Fully responsive on devices of all sizes.

## Technologies Used
### Languages Used
* HTML5
* CSS3

## Frameworks, Libraries & Programs Used
* [Bootstrap v5.3](https://getbootstrap.com/docs/5.3/getting-started/introduction/) was used to assist with the responsiveness of the site and the styling of certain elements.
* [Google Fonts](https://fonts.google.com/) was used to import the 'Poppins' font into the style.css file which is used throughout the entire website.
* [Balsamiq](https://balsamiq.com/) was used to create the wireframes for the site.
* [GIMP](https://www.gimp.org/) was used to edit text onto the hero image, as I was able to download and import the Poppins font to ensure an element of consistency.

## Testing
### Testing User Stories
* As a first time visitor, I want to be able to easily navigate between the site pages.
    * The nav bar is located at the top of each page of the site for easy navigation. It is simplistic in design and straightforward to use.

## Debugging
### Navbar
I noticed that the Navbar was extended slightly wider than the rest of the container. I had a div with the class 'row' and a div with the class 'col navbar' within that. I realised I had to add an additional div inside the column div with the class Navbar, and take the Navbar class out of the column div, and this fixed the issue.

### Get in Touch section
When viewing on mobile, the 'Get in Touch' section was too close to the previous section of 'Opening Hours', when there should have been a gap inbetween. I realised that I was missing a paragraph tag between the divs so I added this in to fix it.