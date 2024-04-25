# QuickHire

QuickHire is like an online marketplace where people can offer their skills and services for others to hire or buy. Building an app or a website or even helping a person in developing something for your needs, QuickHire is the ideal platform for everyone.


* *Date Created*: 29 Jan 2024
* *Last Modification Date*: Apr 9, 2024
* *Frontend Deployed URL*: <https://quick-hire.netlify.app/>
* *Backend Deployed URL*: <https://quickhire-backend-1.onrender.com/>

Note: Please give 50 seconds to 2 minutes to UI for loading data. As backend is hosted on Render as free tier, and it will take sometime to start.

## Authors

- [Hiteshkumar Gupta](ht643276@dal.ca) - _(Frontend, Backend Developer)_
- [Rahul Hambarde](rahul.hambarde@dal.ca) - _(Frontend, Backend Developer)_
- [Parth Pinakin Modi](pr571545@dal.ca) - _(Frontend, Backend Developer)_
- [Angel Christian](an321060@dal.ca) - _(Frontend, Backend Developer)_
- [Tijilkumar Parmar](tj950701@dal.ca) - _(Frontend, Backend Developer)_
- [Yashkumar Khorja](ys944579@dal.ca) - _(Frontend, Backend Developer)_

# Table of Contents

- [Features](#features)
- [Project Structure](#project-structure)
  - [Frontend](#frontend)
- [Getting Started - Frontend](#getting-started---frontend)
  - [Sources Used](#sources-used---frontend)
- [Acknowledgments](#acknowledgments)
- [References](#references)


## Features

1. **Product Wishlist Page**
2. **Search Result Page**
   - Services List
   - Sort options
3. **Individual Service Page**
   - Service Details
   - Add to Wishlist
   - Send Message
4. **Feedback and Rating System**
   - Both ways
5. **User Management**
   - Login Page
   - Sign up page
   - User Profile Page
     - Reviews as well
6. **Payment Gateway for Service**
   - Payment Processing on the individual service screen
7. **Become A Seller Setup**
   - Multiple pages, similar to Fiverr
8. **Service Creation Page for Seller**
9. **Wishlist for the User, My Services for the Seller**
    - View
    - Edit
    - Disable
10. **Subcategory Service Page**
    - When clicked on a broader category
11. **Orders Page**

## SEO, robots.txt and sitemap.xml
- QuickHire's SEO improve for search engine visibility.
- Included a robots.txt file to control search engine bot access to the site.
- Added a sitemap.xml file to aid search engine crawling and indexing.


## Project Structure
### Frontend
In our frontend implementation, we have adopted a feature-based organization structure:

- **Features Folder**: Contains subfolders for each feature of the application.
  - Within each feature folder:
    - **Components**: Individual components related to that feature.
    - **CSS Files**: Each component has its own CSS file, allowing for easier management of styles.

## Getting Started - Frontend
### Prerequisites

To have a local copy of this lab up and running on your local machine, you will first need to install the following libraries and tools:

```
git
node: v14.21.3
npm: v6.14.18
react: ^17.0.1
```

To have a local copy of this assingnment up and running on your local machine, you will first need to install the following software:

Download Install node from node website
```
Website: https://nodejs.org/en/download
```

### Installing

A step by step series of examples that tell you how to get a development env running

Clone repository
```
git clone https://github.com/hmgtech/quickhire.git
```

Change directory to app
```
cd csci_5709_grp-04
cd Frontend
cd quickhire
```
Install packages
```
npm i
```
Create .env file add following credentials
```
REACT_APP_BACKEND_URL=https://quickhire-backend-1.onrender.com/api/v1/
REACT_APP_FIREBASE_API = AIzaSyAeyFuIDm34sjFU0_yGgMTJmpyJTCmoE5k
```
Run Project
```
npm start
```
Navigate to `http://localhost:3000/`. The application will automatically reload if you change any of the source files.

## Deployment

To deploy on ubuntu server, follow this steps:
Clone repository
```
git clone https://github.com/hmgtech/quickhire.git
```

Change directory to app
```
cd csci_5709_grp-04
cd Frontend
cd quickhire
```
Install packages
```
npm i
```
Create .env file add following credentia;s
```
REACT_APP_BACKEND_URL=https://quickhire-backend-1.onrender.com/api/v1/
REACT_APP_FIREBASE_API = firebase-api-key
```
Build Project
```
npm run build
```
This will regenerate build folder which will contains index.html.

Point `nginx` server to this location.

Your server will be up and running.

## Built With

* [React](http://www.dropwizard.io/1.0.2/docs/) - The web library used
* [Material UI](https://v4.mui.com/getting-started/installation/) - Styling library
* [FlatIcon](https://www.flaticon.com/) - For icons
* [Stripe](https://stripe.com/) - Online payment processing platform


## References
Images used for the cards in the projects (they are cited in project readme file as well):
```
1. Creative IT Institute. [Hair Treatment Course Image]. [Online]. Available. https://www.creativeitinstitute.com/images/course/course_1663052056.jpg [Accessed On: Feb 6, 2024]

2. Dribbble. Hair Treatment App. [Online]. Available. https://dribbble.com/shots/19606563-Hair-Treatment-App [Accessed On: Feb 6, 2024]

3. Dribbble. Infinite Software. [Online]. Available. https://dribbble.com/shots/3812899-Infinite-Software/attachments/10034607?mode=media [Accessed On: Feb 6, 2024]

4. Dribbble. Skype Universal Windows App. [Online]. Available. https://dribbble.com/shots/2652326-Skype-Universal-Windows-App/attachments/9414061?mode=media [Accessed On: Feb 6, 2024]

5. Fotor. Profile Picture Ideas. [Online]. Available. https://www.fotor.com/blog/profile-picture-ideas/ [Accessed On: Feb 6, 2024]

6. Fiverr. "Fiverr - Freelance Services Marketplace", 2024. [Online]. Available: https://www.fiverr.com/ [Accessed on: February 6, 2024]

7. Upwork. "Upwork - The World's Work Marketplace, 2024" [Online]. Available: https://www.upwork.com/ [Accessed on: February 6, 2024]

8. Material UI. "Overview." [Online]. Available: [https://mui.com/material-ui/getting-started/](https://mui.com/material-ui/getting-started/) Accessed February 21, 2024.

9. “Diary free icon,” Flaticon. [Online]. Available: https://www.flaticon.com/free-icon/diary_10748360?term=writing&page=1&position=90&origin=search&related_id=10748360. [Accessed On: Feb 27, 2024].

10. “Code free icon,” Flaticon. [Online]. Available: https://www.flaticon.com/free-icon/code_1903572?term=programming&related_id=1903572. [Accessed On: Feb 27, 2024].

11. “Diary free icon,” Flaticon. [Online]. Available: https://www.flaticon.com/free-icon/diary_10748500?related_id=10748500. [Accessed On: Feb 27, 2024].

12. “Photo free icon,” Flaticon. [Online]. Available: https://www.flaticon.com/free-icon/photo_2990729?term=photography&related_id=2990729. [Accessed On: Feb 27, 2024].

13. “Bullhorn free icon,” Flaticon. [Online]. Available: https://www.flaticon.com/free-icon/bullhorn_1998087?term=digital+marketing&related_id=1998087. [Accessed On: Feb 27, 2024].

14. “Shopping Online free icon,” Flaticon. [Online]. Available: https://www.flaticon.com/free-icon/shopping-online_1260235?term=digital+marketing&page=1&position=13&origin=search&related_id=1260235. [Accessed On: Feb 27, 2024].

15. Flatworldsolutions.com. [Online]. Available: https://cdn.flatworldsolutions.com/featured-images/top-10-online-video-editing-tools.jpg. [Accessed On: Feb 27, 2024].

16. Com.ph. [Online]. Available: https://www.truelogic.com.ph/wp-content/uploads/2021/09/dynamic_website.png. [Accessed On: Feb 27, 2024].

17. Ctfassets.net. [Online]. Available: https://images.ctfassets.net/ooa29xqb8tix/22yB0fxGdusPYvjeHt0tIc/5e8425645473fbfc465de26fff504c89/Metadata_the_Figma_Handbook.jpg. [Accessed On: Feb 27, 2024].

18. Berkeley.edu. [Online]. Available: https://multimedia.journalism.berkeley.edu/wp-content/uploads/stand_up_vo-main.jpg. [Accessed On: Feb 27, 2024].

19. Medium.com. [Online]. Available: https://miro.medium.com/v2/resize:fit:1400/1*MirlZnbuS9Cs9bVxxSPbjg.jpeg. [Accessed On: Feb 27, 2024].

20. Seo-hacker.com. [Online]. Available: https://seo-hacker.com/wp-content/uploads/2019/07/Cover-Photo-New-Website-SEO-A-Comprehensive-Guide-1024x768.jpg. [Accessed On: Feb 27, 2024].

21. Buffer.com. [Online]. Available: https://buffer.com/cdn-cgi/image/w=1000,fit=contain,q=90,f=auto/library/content/images/size/w1200/2022/10/thought-catalog-505eectW54k-unsplash.jpg. [Accessed On: Feb 27, 2024].
```

## Acknowledgments

- Design is inspired by [Fiverr](https://www.fiverr.com/) and [Upwork](https://www.upwork.com/).
- Created React application using template [create-react-app](https://create-react-app.dev/docs/getting-started)
- Used [Material-UI](https://v4.mui.com/getting-started/installation/) components and icons
- Used [react-multi-carousel](https://www.npmjs.com/package/react-multi-carousel)'s to create smooth carousel for displaying Popular Services component 
- Used [react-parallax](https://www.npmjs.com/package/react-parallax) for animation of Hero section for Landing page
- Used [typewriter-effect](https://www.npmjs.com/package/typewriter-effect) to animate text
 - [Render](https://render.com/) - For Backend hosting
 - Hats off to the Medium.com and Stackoverflow.com community for providing useful tutorials and solutions