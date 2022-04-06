# Rent a chef
Rent a chef is an visual idea of discussions i had during the pandemic when i worked as an salesmanager within the techsector selling software to hotells and resturants.
During this hard period it was almost impossible to pitch our products becuase of the restrictions. Because of the situation new ideas was invented how to keep the buisness going and i had a few dialogs with buisness owners and we were talking about how to have an income from distans. The website is an idea of an online resturant where people can se how the chefs are working in the kitchen to create a full menu that contains a starter, main course and dessert.
![image](https://user-images.githubusercontent.com/100356636/161710456-fc2c64a5-bb91-43b2-a0fe-27f2641bb731.png)

**Navigation links**
- Available on all pages. The full responsive navigation bar includes links to the Home, Menu and Order page. The pages are identical in design and text, which makes it easier for the customer to navigate.
- Customer can easily navigate forth and back without having to press the backbutton.

![image](https://user-images.githubusercontent.com/100356636/161710835-01517400-99f7-4795-b1e9-111174d567e3.png)




**Footer**
- Footer contains 4 social media icons which can be opened in new tabs. This is a great way to communicate with information that is not displayed on the website. Customers would be able to se the next weeks menu, wich chefs that are working and different events to decide future menues.
-  At this point the social media plattforms have not been created yet. 
![image](https://user-images.githubusercontent.com/100356636/161710665-afec94a1-61af-4ceb-950e-c2759cde8863.png)



**Landing Page**

- Landing page contains an logo styled with the font style " Dancing Script ". Menues often has this type of style and gives a touch of resturant feeling. When you visit the landing page you will have information below the main picture what the site is about. Very clean an easy to read.



**Order page**
- When the customer finds the order page, you are greeted by an inspiring page with a lot of color and energy. The customer can also read the prices about the 3 different services offered. All services are created to easily arrange a dinner at home when you lack inspiration and time. The background image shows a professional chef working with details. This is to give an idea of being contacted by chefs with a lot of experience.

- Customer has to enter these following required informations:

        * First Name 
        * Last Name 
        * Email 
        * Choose dish ( drop-down list )

![image](https://user-images.githubusercontent.com/100356636/161611093-64373d70-589f-4bcf-94ae-9e0d063b8451.png)


**Existing Features**
- Responsive design.
- Repsonsive images at menu page.
- Contact form.

**Features Left to Implement**
- All chefs will have their own profile page.
- Customers will have access to store their videos in their account.
- Chatt features between other customers.
- Recipe forum.
- Sponsor competion with prices.
- Thirt party collaboration.
- Advertising.

## Technologies

* HTML
    * The structure of the Website was developed using HTML as the main language.
* CSS
    * The Website was styled using custom CSS in an external file.
* Visual Studio Code
    * The website was developed using Visual Studio Code IDE
* GitHub
    * Source code is hosted on GitHub and delpoyed using Git Pages.
* Git 
    * Used to commit and push code during the development opf the Website

## Testing 

**Functional testing**

- Navigation links

Testing was made to make sure that the links on all pages navigated to the correct pages as per design. This was done by clicking on the navigation links on each page.

- Contact form

Testing was made by filling the categories differently. If user is avoiding answer first or lastname an "required" message will pop up. When user is succesfull an error 405 message will be presented.


### Responsiveness

All pages were tested to ensure responsiveness on screen sizes from 320px and upwards as defined in [WCAG 2.1 Reflow criteria for responsive design](https://www.w3.org/WAI/WCAG21/Understanding/reflow.html) on Chrome.

Steps to test:

1. Open browser and navigate to [Rent a chef](https://peterlar.github.io/rent-a-chef/)
2. Open the developer tools (right click and inspect)
3. Set to responsive and decrease width to 320px
4. Set the zoom to 50%
5. Click and drag the responsive window to maximum width

Expected:

Website is responsive on all screen sizes and no images are pixelated or stretched.
No horizontal scroll is present.
No elements overlap.

Website was also opened on the following devices:

- Iphone SE
- Iphone XR
- Iphone 12 pro
- Pixel 5
- Samsung Galaxy 8
- Samsung Galaxy S20 Ultra
- Nest Hub Max

**Validator Testing**

- HTML
I had a couple of errors testing the site. I had alot of problems with gitpod not sending code to Github/8000 browser and it was not because of cache memory. When that 
was sorted out the erros was due to "stray sections" and not closed sections. I removed the stray sections and closed where it was needed.

- CSS
One error was found when passing through the official (Jigsaw) validator. The error states an "parsingerror" on the last column in the code that is empty. I went through the code several times and could not find the missing piece. 

**Unfixed Bugs**
- I struggled alot with Gitpod the last couple of days wich is the reason why this project is delayed. It was almost impossible to have the 8000 server browser having any update in wich i had to contact the support many times. When the support opened the workspace they had no issues at all. The last thing i tried was cleaning my browsers from everything and delete all other workspaces. I still recived the same error message. I hope for a better future with other projects.
![gitpod error](https://user-images.githubusercontent.com/100356636/161829647-fd05cc7a-c129-4e45-bf49-cac6e11f88ce.JPG)

# Deployment

### Deployment to Github Pages

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - Scroll down to "Github Pages"
  - You will find following message "Pages settings now has its own dedicated tab! Check it out here!"
  - Click "Check it out here"
  - A live link will be displayed in a green banner when published successfully. 

The live link can be found here https://peterlar.github.io/rent-a-chef/


**Accessibility**

[Wave Accessibility](https://wave.webaim.org/) tool was used throughout development and for final testing of the deployed website to check for any aid accessibility testing.### Accessibility

Landing page:

![wave](https://user-images.githubusercontent.com/100356636/161719921-b27d198c-f683-4b9c-83ce-ca56fe2cb9ea.JPG)

Menu page:

![menu page](https://user-images.githubusercontent.com/100356636/161720392-8e7343fd-ab43-4bd9-89a5-e76499f305a1.JPG)

Order page

![wave order page](https://user-images.githubusercontent.com/100356636/161720047-41f62281-49e8-4d3d-82b7-6dc2b3dbcc7e.JPG)

# Credits

**Media**
- The images that was used for this website all came from Words online service for images.

**Content**
- No content was used from other sources, however some code buildup was used from the " I Love Running " project.

**Tutor support**
- The tutor support was amazing helping with technical difficulties and errors. Also had some help with solving some layout issues.

**Slack community**
Had great chats and discussions with other fellow students solving some issues.

**Mentor** 
- I will also say thanks to my mentor Daisy who game me some great tools to use in the future and her feedback on some errors.
