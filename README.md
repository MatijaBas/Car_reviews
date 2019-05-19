# README.md

## Car Reviews Website

This Website has a focus on the latest reviews about luxury sports cars. The website is for a user that is potentially thinking about getting the new car,
but also for all car lowers. If you are interested in buying a new car and you are not sure which one to buy, this is the right place for you.
Everything that you need to know about cars, you will find on my Website.

My project has its opening page where you can see Opening video and the latest three reviews that I did. I divided reviews into 3 categories;
Petrol, Hybrid and fully Electric car. In each category, you can find the last two reviewed cars. The following menu item allows users to see all reviewed
cars in one place. I added a gallery with a few lovely pictures of reviewed cars and the one that I have a plan to do in a close future.
If you have any suggestions and you would like to see any car reviewed, or you just have any other questions, you will find the contact on the last menu item.

## UX

The website is for individuals interested in cars, sports cars and luxury sports cars, who want to know more about it.
This website allows individuals to see pictures and read interesting articles from the latest tests. If individuals are thinking about buying 
electric, petrol, hybrid or any car and they are not 100% sure which one is perfect for them, this website will help with it.
After reading reviews it's gonna be easier to make the decision.

- As a new user, I want to see a description of a car so that I can know more about it
- As a new user, I would like to read about new cars if I decide to buy it
- As a possible new car buyer, I would like to read about the car before I go for a test drive
- As a car lower I would like to see reviews from an experienced person and also give my suggestions
- As a user, I just want to see car pictures, read reviews and dream about beautiful cars
- As a user, I can research about cars and see which one suits me best; petrol, hybrid or electric car.
 
### Mockups
- Please find paper and pen mockup for the first design [Here](Mockups/first-design.pdf)
- Please find paper and pen mockup for the original first design,all cars [Here](Mockups/first-design2.pdf) 

## Features

### Existing Features

#### index.html
- Eye catching front page
    - Lovely video of sport car to welcome user on webpage 
- Latest reviews 
    - about one petrol, one hybrid and one electric car together with pictures of them

#### petrol.html
- Petrol cars reviews
    - Lovely header image with two petrol cars reviews
    
#### hybrid.html
- Hybrid cars reviews
    - Lovely header image with two hybrid cars reviews

#### electric.html
- Electric cars reviews
     - Lovely header image with two electric cars reviews
     
#### allcars.html
- Reviews about all cars
     - Allows users to find all reviewed cars and read about it

#### gallery.html
- Photo gallery
     - Allows users to view photos of all reviewed cars and the one that comming in near future
     
#### contact.html 
- Contact form 
      - Contact form for user to sugest and ask
     
### Features to be Implemented in the Future
- Javascript
    - To link up the contact form for it to work correctly once I have learnt it
    - To have an alert that says "thank you for submitting your form"
    - To add a videos of cars in the gallery.html page

### Features Left to Implement
- None

## Tech Used
- HTML
    - This was used to create the markupl
- CSS
    - car_reviews/assets/css/styles.css
         - This was used to style the elements of the HTML code
- Bootstrap
    - https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css
         - This was used to help style the website
- Font Awesome
     - https://fonts.googleapis.com/css?family=Roboto:400,700
     - https://fonts.googleapis.com/css?family=Gugi
        - This was used to create a universal font for the website
- Vimeo
      - https://player.vimeo.com/api/player.js
          - This was used to create a video in background
- Validators
    - An HTML [validator](https://validator.w3.org/) was used to check the code
    - A CSS [checker](https://jigsaw.w3.org/css-validator/) was used to check the stylings

## Testing

#### Overall
I tested out some designs in a workspace, I ended up copying and pasting some code 
for my submitted project.[This repository can be found here](https://github.com/MatijaBas/project-testing)

#### index.html
- Reviews
    - Go to Home page
    - Click on read reviewe

#### petrol.html 
- Lamborghini Huracan Spyder
    - Go to categories and click on Petrol
    - Then click on See Pictures
    - Be sure that they will open another page
    
#### hybrid.html
- Bmw i8
    - Go to categories and click on Hybrid
    - Then click on See Pictures
    - Be sure that they will open another page

#### electric.html
- Tesla Model S
     - Go to categories and click on Electric
     - Then click on See Pictures
     - Be sure that they will open another page
     
#### allcars.html
- All reviews
   - Go to All Cars
   - Choose any reviewed car 
   - Click on See Pictures
   - Make sure that that the new page will be open Gallery
 
#### gallery.html
- Pictures
    - Go to Gallery page
    - Hover over pictures
    - Make sure each picture get zoom

#### contact.html
- Contact form
    -Try submitt form with all input fields filled out and the page should reload

#### Navigation and Footer
- Navigation
    - Open each menu item on each page respectively
    - Some friends test this for me
-Footer
    - Social Media Links
        - Click each link to make sure they open in another page due to the target="_blank"
        - Make sure each link correlates to the correct social media platform

#### Mobile Responsive 
- Each page was checked through the live preview by inspecting it in dev tools and choosing different screen sizes

### Bugs/Problems Encountered
- Home page background video
    - When I add a video in background, It wasn't muted and didn't repeat , and had controls over video.
    - To fix this I add some elements to video title but still showing control bar just for 1 sec.
- Footer didn't work properly on smaller devices
    - To fix this I ran the footer code through an HTML validator and corrected the problems
- My mentor pointed out that the code for my navigation bar was not formatted correctly with the Bootstrap divs and rows
    - To fix this I re watched some videos and took in what my mentor said to make my code my cleans and work more effectively

## Deployment
 I pushed my Cloud9 workspace to my Github repository named Car_reviews via command line to deploy my project.Every time when 
 something was edited i push it so be saved.To create my GitHub page i build it from the Master branch.
 Please find my [GitHub here](https://github.com/MatijaBas/Car_reviews)
 
## Credits

### Content

#### index.html
- The video used in index.html header was obtained and uploaded by me from [Vimeo](https://vimeo.com/334302997)
- The information used in index.html main content was copy and pasted from [Top Gear Reviews](https://www.topgear.com/car-reviews/lamborghini/huracan-spyder)

#### petrol.html
- The information used in petrol.html were obtained from [Top Gear Reviews](https://www.topgear.com/car-reviews)

#### hybrid.html
- The information used in petrol.html were obtained from [Top Gear Reviews](https://www.topgear.com/car-reviews)

#### electric.html
- The information used in petrol.html were obtained from [Top Gear Reviews](https://www.topgear.com/car-reviews)

#### allcars.html
- The information used in petrol.html were obtained from [Top Gear Reviews](https://www.topgear.com/car-reviews)

#### gallery.html
- The photos used in gallery.html were obtained from [Top Gear](https://www.topgear.com/) and [Google](https://www.google.com/search?q=sport+hybrid+cars&rlz=1C1JZAP_hrIE837IE837&source=lnms&tbm=isch&sa=X&ved=0ahUKEwi16Mriu6jiAhXyVBUIHaZZBfMQ_AUIDigB&biw=1920&bih=937)

### Acknowledgements
- To build this webpage i received inspiration from my second love, Sport Cars
- Thank to nice people on SLACK that help me when I stuck and needed assistance
- Big thank to my mentor Antonija Simic. She was allways there for me and show me so many things how to build modern webpage.She's great.
- And at the end thank to my wife Sanja , who gave me so much free time so I can work on my project  