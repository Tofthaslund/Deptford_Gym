# Deptford Gym

![SCRRENSHOT DEPTFORD](https://user-images.githubusercontent.com/72796767/104643062-b4541780-56a3-11eb-9e4e-a96dca7ebd76.PNG)

---


## Description

This project is created to showcase a local owned gym in Deptford, London.
The goal with this website is to attract new customers, as the owners 
think there will be a surge in the market after the lockdowns are over, and
more people wnat to have a healtier lifestyle.
The website is created with HTML5 & CSS3, and made responsive with Bootstrap.

--- 

## UX

- As a user, I want to be able to see the location of the gym. (Top of each page)
- As a user, I want to be able to see a phone number to call the gym. (Top of each page)
- As a user, I want to see the the opening hours of the gym. (Top of each page)
- As a user, I want to see different pictures of people in the gym.
- As a user, I want to be able to sign up for a PT session and get an introduction at the gym.
--

### Wireframes
- Desktop:
- [Index](asset/wireframes/desktop/home-page.png)
- [Gallery](asset/wireframes/desktop/gallery-page.png)
- [Sign-Up](asset/wireframes/desktop/sign-up-page.png)
- Tablet:
- [Index](asset/wireframes/tablet/home-page.png)
- [Gallery](asset/wireframes/tablet/gallery-page.png)
- [Sign-Up](asset/wireframes/tablet/sign-up-page.png)
- Phone:
- [Index](asset/wireframes/mobile/home-page.png)
- [Gallery](asset/wireframes/mobile/gallery-page.png)
- [Sign-Up](asset/wireframes/mobile/sign-up-page.png)


---

### Technologies

- HTML5
- CSS3
- Bootstrap
- Font Awesome
- Google Fonts

[Back To The Top](#Deptford-Gym)

---
## Deployment

This project was deployed using GitHub Pages.

To deploy this page to GitHuB Pages from its GitHub repository, the following steps were taken:

1. Log into GitHub
2. From the list of repositiores on the screen, select **Tofthaslund/Deptford-Gym**.
3. From the menu items near the top of the page, select **Settings**.
4. Scroll down to the **Github Pages** section.
5. Under **Source**, click the dropdown menu labelled **None** and select **Master Branch**.
6. On selecting Master Branch the page is automatically refreshed, the website is now deployed.
7. Scroll back down to the **GitHub Pages** section to retrive the link to the deployed website.

### How to run this project locally?

To clone this project from GitHub:

1. Log into GitHub.
2. At the top search bar, search for **"Tofthaslund/Deptford-Gym"**.
3. You will land on the **Code** section of the repository.
4. Click on the **Code** dropdown menu, just above the README file.
5. Click on the clipboard next the the URL.
6. Paste that into our local IDE of choice 


---



Testing client stories from UX section of README.md 

1. As a new vistior to the website, I want to easily navigate the site, so I can find hat I need efficiently.

    - No matter what page the visitor lands on, they can easily find the navigation bar.
    -  The headline always leads back the home page (the starting place for most client stories)
    - The go back button that appears after a client has signed on to a pt session, sends the client back to the homepage.

2. As a new visitor of the website, I want to be able to see a gallery of the gym, to see if I like it before I join.

    - At the top of the website (the nav bar) the is a call to action button there leads the visitor on to the gallery page.
    - A clearly labelled Gallery page button is to be found on every website.

3. As a visitor, if i am curious about the gym and want to know more I have the option to do show.

    - At the top of every page there is a phone number for the gym, clients can call to more about it.
    - At the bottom of each page (footer) the are 3 links to the gyms external social media.

4. As a visitor I want to know the gyms location.

    - At the top of each page, the location of the gym is clearly stated.


5. As a user, I want to be able to sign up for a PT session and get an introduction at the gym.

    - at the top of each page there is a link for the Sign-up section of the website, there 
    will guide the visitor to a sign-up form for a PT session in the gymm.

  ---
    ## Testing of the functionality of the website

1. 
- Action: **Click on the Gallery tab.**
- Expected behaviour: **Browser goes to gallery page of website.**
- Pass/Fail: **Pass.**

2. 
- Action: **Click on the Sign-Up tab.**
- Expected behaviour: **Browser goes to Sign-up page.**
- Pass/Fail: **Pass**

3. 
- Action: **Click on the Facebook icon.**
- Expected behaviour: **Browser goes to Faceboog page in new tab.**
- Pass/Fail: **Pass**

4. 
- Action: **Click on the Instagram icon.**
- Expected behaviour: **Browser goes to Instagram page in new tab.**
- Pass/Fail: **Pass**

5. 
- Action: **Click on the Twitter Icon.**
- Expected behaviour: **Browser goes to Instagram page in new tab.**
- Pass/Fail: **Pass**

6. 
- Action: **Press _Let's Go_ button on the Sign-Up page without filling out the form**
- Expected behaviour: **_Please fill in this field_ pops up for the First Name tab**
- Pass/Fail: **Pass**

7. 
- Action: **Press _Let's Go_ button on the Sign-Up page with only first name filled out**
- Expected behaviour: **_Please fill in this field_ pops up for the Late Name tab**
- Pass/Fail: **Pass**

8. 
- Action: **Press _Let's Go_ button on the Sign-Up page with first name an last name filled out**
- Expected behaviour: **_Please fill in this field_ pops up for the Email tab**
- Pass/Fail: **Pass**

9. 
- Action: **Press _Let's Go_ button on the Sign-Up page with first name, last name, email filled out with wrong email form**
- Expected behaviour: **_Please enter a email address_ pops up for the Email tab**
- Pass/Fail: **Pass**

10. 
- Action: **Press _Let's Go_ button on the Sign-Up page with first name, last name, email filled out**
- Expected behaviour: **_Please fill in this field_ pops up for the Pick a Date tab**
- Pass/Fail: **Pass**

11. 
- Action: **The form is filed out correctly**
- Expected behaviour: **The browser takes you to a new page with the messeage _Thanks for signing up_**
- Pass/Fail: **Pass**

12. 
- Action: **Clicking the back button on _Thanks for signing up page.**
- Expected behaviour: **The browser takes you back to the home page**
- Pass/Fail: **Pass**

---

