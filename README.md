![Boutique Bibi](/media/bibi-logo-black.png)

# Boutique Bibi

[View the live project here](https://jade-quinn.github.io/lulu-loves/)

Boutique Bibi has been
 
## UX

### The Strategy Plane

**Why are we so special?**

Lulu Loves products are 100% vegan, cruelty-free, paraben free and handmade. 
We are focused on offering pamper products to tweens and teens, aged 11-19. 
The LL community centres around the promotion of positive mental health and resilience in teens through acts of self-care. 
Both our online platform and notes that accompany our products, 
teach teens easily digestible techniques relating to mental health and wellness. 
So, whether it's a mini meditation, breathing exercise or the latest ASMR video, 
we want you to kick back and take 5. Self-care isn't selfish!

**Who else is building this?**

[Lush Cosmetics](https://uk.lush.com/) offer a similar service. They are also a handmade beauty business, focused on ethical and sustainable products and offer a large choice of bath bomb designs. 
They do a good job of communicating the company's values on their homepage, along with beautifully tactile photography to showcase their products. 
However, based on some products they stock, anti-ageing creams etc. it is possible to surmise that their demographic begins slightly older and spans a greater range than the LL user. 
LL's brand and online presence should be tailored more specifically to the target demographic. 

![Lush Homepage](./documentation/lush-home-page.jpg)

The Lush cosmetics menu offers over 80 items in its drop-down menu which could be overwhelming and cause decision fatigue in tweens and teens. 

![Lush Menu](./documentation/lush-menu.jpg)

An [article published on rte.ie](https://www.rte.ie/news/business/2020/1023/1173492-google-search-for-shop-local-ireland-up-540/) in October 2020, 
reported that search terms such as "shop local Ireland" saw an increase of 540%. 
As Lush is a UK based brand it would be beneficial for LL to communicate clearly to guardians and teens that it is an Irish brand.

**What are the tech and design considerations?**

The LL demographic are tech savvy. [The Irish Times reports](https://www.irishtimes.com/business/technology/children-spend-equivalent-of-61-days-a-year-online-study-1.4012928)
that 15% of 12-year-olds spend the equivalent of 61 days a year online. 
Based on a 2019 [survey](https://www.cso.ie/en/releasesandpublications/ep/p-isshh/informationsocietystatistics-households2019/frequencyofinternetusage/) from the Central Statistics Office, 
an estimated 88% of individuals in Ireland access the internet through a mobile device. 
With this in mind, there should be a mobile first approach to design and functionality.
This product is for general consumers. As this is a B2C product, it should focus heavily on branding and emotive product images.

**Project roadmap**

To determine the business objectives and user needs for this release I have created the table below. 
Each opportunity/problem is rated on a scale of 1 - 5 in two dimensions; Importance and Feasibility.

Opportunity/Problem | Importance | Feasibility
------------ | ------------- | -------------
Create an online presence | 5 | 5
Increase social media followers | 1 | 2
Sell products online | 5 | 1
Customisable gift boxes | 1 | 1
Start the LL blog | 4 | 4
Showcase a product | 5 | 4
Generate interest in the brand and build a relationship with users | 5 | 5

![Lulu Loves Project Roadmap](./documentation/project-roadmap.jpg)

#### User Stories

**Goals of visitors aged 11 - 19**

- As a first time visitor, I want to easily understand the main purpose of the site and learn more about the products and LL community.
- As a first time visitor, I want to be able to navigate through the site easily.
- As a first time visitor, I want to sign-up to the newsletter to be notified about product releases.
- As a first time user, I want to visit the brands social media accounts.
- As a first time visitor, I want to read tips and tricks relating to the products, self-care and wellbeing.
- As a first time visitor, I want to look at videos of the products.
- As a first time visitor, I want to browse gift options to get a feel for the type of product offered.
- As a returning visitor, I want to purchase products from the site.
- As a returning visitor, I want to read further tips and comments from other users.
- As a returning visitor, I want to post a comment.
- As a returning visitor, I want to contact LL with a question.

**Goals of guardians**

- As a first time visitor, I want to quickly understand if this brand is safe, sustainable and trust-worthy.
- As a returning visitor, I want to buy a gift.
- As a returning visitor, I want to find information about delivery times.
- As a returning visitor, I want to contact LL with a question.

#### User persona of primary visitor

![Lulu Loves User Persona](./documentation/lulu-loves-user-persona.jpg)
![Lulu Loves User Goals and Frustrations](./documentation/lulu-loves-user-persona-goals-and-frustrations.jpg)

### The Scope Plane

#### Feature Scope

To establish the feature scope for this project I am using the agile methodology, I have made a list of all possible features and given each one a difficulty rating between 1 and 3.
Each release will allow for a maximum of 12 points. The table below will be used to determine which features to prioritise and which to schedule for a later release.

Feature | Rating
------------ | -------------
Announcement bar at the top of the home page to highlight relevant information e.g. newsletter promotion | 1
Logo that links to the home page so users can orientate themselves easily | 1
Clear, consistent navigation on each page | 1
Showcase products or imporant site content with a sliding banner | 2
Highlight aspects of the brand that are important to the user (e.g cruelty-free products, customer service) using short messages and icons | 1
Self Care Club blog, featuring articles on products as well as general tips relating to self care | 1
Online shop that will give users the option to set up an account or check out as guest and pay securely using Paypal, Stripe or Apple Pay | 3
Related products section for upselling and cross selling | 3
Calculated shipping | 3
Advertise gift box product release | 1
Newsletter sign-up | 2
Footer which includes links to social media accounts | 1
Contact form | 1
Custom mouse icon | 1

Given limited resources, the features that offer the most value at this stage are:
- Logo that links to the home page
- Clear, consistent navigation on each page
- Showcase products with a sliding banner
- Highlight aspects of the brand that are important to the user
- Advertise gift box product release
- Self Care Club blog
- Newsletter sign-up
- Footer
- Contact form
- Custom mouse icon

These features solve the problem of generating interest and anticipation around the shop launch and beginning the process of establising the brand with potential customers.

**The MVP (model view controller) pattern **

Seperation of concerns - Seperate data management and presentation. It is important to implent a DRY approach so I do not reapeat code and the site is eaily maintained. Deviding the systme into compnanats and sub-componants down to single componants

1. Model - python/javascript
2. View - html css
3. Controller - get put delete

### The Structure Plane

As the site will not have a lot of content to begin with a linear narrative will work best

![Lulu Loves Information Architecture](./documentation/lulu-loves-information-architecture.png)

### The Skeleton Plane

The wireframes were created using Balsamiq. They can be viewed at the following links

[Homepage](https://github.com/Jade-Quinn/lulu-loves/blob/master/documentation/home-page-wire-frame.png)

### The Surface Plane

**Colour Scheme**

The main colours used are lilac #c7aacd, yellow #f5e336, blue #a7c6ea and orange #ef7a4e
The colour pallet is bright and playful but used sparingly across the site to keep it looking clean.


**Typography**

The font used on the site is Poppins with Sans Serif as the fallback font in case Poppins doesnt load.
It is a clean and bold font but it is also slightly informal and fun to tie in with the overall brand aesthetic.

**Imagery**

Imagery is bright and striking. It is a combination of custom made graphics and people enjoying the brands products.
A custom mouse and hover icon offers an element of surprise.


## Features
 
### Existing Features

- Announcement bar - highlight to users relevant information e.g. newsletter promotion or sale. This appears on the homepage only so as not to annoy the user with repetitive information.
- Image carousel - communicates to the user what the site is about
- Logo link to home page - allows users to orientate themselves quickly
- Linear navigation - allows users to easily navigate all pages
- Product page - showcase to the user products on offer
- Custom compnay value icons - highlight to users the values of the brand (e.g cruelty-free products)
- Self Care Club blog - encourages users to return to the site
- Advertise gift box product release - generate anticipation with site users
- Newsletter sign-up - encourages users to return to the site
- Custom icons and cursor - to surprise users and make the site more memorable
- Social icons in footer - allows users to further engage witht he brand and builds trust
- Contact form - allows users to easily get in contact by filling out the form

### Features Left to Implement
- In the future the site will implement a shop to allow users to purchase products

## Technologies Used

### Languages Used

-   [HTML5](https://en.wikipedia.org/wiki/HTML5)
-   [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)

### Frameworks, Libraries & Programs Used

1. [Bootstrap 5:](https://getbootstrap.com/docs/5.0/getting-started/introduction/)
    - Bootstrap was used to assist with the responsiveness and styling of the website.
1. [Google Fonts:](https://fonts.google.com/)
    - Google fonts were used to import the 'Poppins' font into the style.css.
1. [jQuery:](https://jquery.com/)
    - jQuery came with Bootstrap to make the navbar responsive but was also used for the smooth scroll function in JavaScript.
1. [Git](https://git-scm.com/)
    - Git was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.
1. [GitHub:](https://github.com/)
    - GitHub is used to store the projects code after being pushed from Git.
1. [Illustrator:](https://www.adobe.com/ie/products/illustrator.html)
    - Illustrator was used to create the logo and branding assets.
1. [Photoshop:](https://www.adobe.com/ie/products/photoshop.html)
    - Photoshop was used to create supporting documents, and to resize images for the site.
1. [Balsamiq:](https://balsamiq.com/)
    - Balsamiq was used to create the wireframes at the 'Skelton Plane phase.


## Testing

- The W3C Markup Validator and W3C CSS Validator Services were used to validate every page of the project to ensure there were no syntax errors.
- I used lighthouse in chrome developer tools to test perfromance and accessability. Screen shots of testing can be found in the testing folder within documentation

Sadly I ran out of time to properly document my tests in this readme

## Deployment

### GitHub Pages

The project was deployed to GitHub Pages using the following steps...

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/)
2. At the top of the Repository (not top of page), locate the "Settings" Button on the menu.
    - Alternatively Click [Here](https://raw.githubusercontent.com/) for a GIF demonstrating the process starting from Step 2.
3. Scroll down the Settings page until you locate the "GitHub Pages" Section.
4. Under "Source", click the dropdown called "None" and select "Master Branch".
5. The page will automatically refresh.
6. Scroll back down through the page to locate the now published site [link](https://github.com) in the "GitHub Pages" section.

### Forking the GitHub Repository

By forking the GitHub Repository we make a copy of the original repository on our GitHub account to view and/or make changes without affecting the original repository by using the following steps...

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/)
2. At the top of the Repository (not top of page) just above the "Settings" Button on the menu, locate the "Fork" Button.
3. You should now have a copy of the original repository in your GitHub account.

### Making a Local Clone

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/)
2. Under the repository name, click "Clone or download".
3. To clone the repository using HTTPS, under "Clone with HTTPS", copy the link.
4. Open Git Bash
5. Change the current working directory to the location where you want the cloned directory to be made.
6. Type `git clone`, and then paste the URL you copied in Step 3.

```
$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
```

7. Press Enter. Your local clone will be created.

```
$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
> Cloning into `CI-Clone`...
> remote: Counting objects: 10, done.
> remote: Compressing objects: 100% (8/8), done.
> remove: Total 10 (delta 1), reused 10 (delta 1)
> Unpacking objects: 100% (10/10), done.
```

Click [Here](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository#cloning-a-repository-to-github-desktop) to retrieve pictures for some of the buttons and more detailed explanations of the above process.

## Credits

### Content
- The method for creating the project road map in README.md came from Code Institute's lesson: 'It's All About The User Experience??> The Strategy Plane??> Strategy Trade-offs'
- Research for content and layout of the user persona in README.md came from Pinterest. Refrences can be found [here](https://pin.it/5B3Gjdc)
- The method for creating the feature scope table in README.md came from Code Institute's lesson: 'It's All About The User Experience??> The Scope Plane??> Scope Challenge'
- I have documented all code used in my html and css files

### Media
- The photos in the user persona in README.md are from Pexels.com [Photo of girl 1](https://www.pexels.com/photo/photo-of-girl-smiling-while-holding-black-smartphone-4145034/) [Photo of girl 2](https://www.pexels.com/photo/fashion-man-people-woman-4144974/)
- Banner photos used on the site are from Pexels.com
- Articles from blog are from headspace.com 

### Acknowledgements

- My mentor Aaron Sinnott, for helpful guidance.

- I received inspiration for this project from my sister Sadie, who gave me great insights when developing the user persona for the Lulu Loves brand. 
Sadie also chose the name and did some initial logo sketches which I later developed into the Lulu Loves mascot, Sunny.

![Sadies original logo sketch](./documentation/sadie-sketch.jpg)
