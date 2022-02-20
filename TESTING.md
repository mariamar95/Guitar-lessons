# **Testing**

## Code Validators
[HTML Validator](https://validator.w3.org/): No errors found

- Home Page ![](./readme-testing/Validator/home-validator.png)
- About Me ![](./readme-testing/Validator/about-validator.png)
- Lessons ![](./readme-testing/Validator/lessons-validator.png)
- Contact ![](./readme-testing/Validator/contact-validator.png)
- FAQ ![](./readme-testing/Validator/faq-validator.png)
<br>

[CSS Validator](): No errors found 
![](./readme-testing/Validator/css.png)


# **Performace**

## I have used **Lighthouse**

- ## Home Page 
![](./readme-testing/LightHouse/home.png) 
- ## About 
![](./readme-testing/LightHouse/aboutme.png)
- ## Lessons
![](./readme-testing/LightHouse/lessons.png)
- ## Contact 
![](./readme-testing/LightHouse/contact.png)
- ## FAQ
![](./readme-testing/LightHouse/FAQ.png) 

# **Responsiveness**
- I have tested the website's responsiveness using [Chrome DevTools](https://developer.chrome.com/docs/devtools/)
- I have also tested the website using the following devices:
  - MacBook Pro 15' (Laptop)
  - Xiaomi Readmi Note 10 (Mobile Phone)
  - Sony Experia (Mobile Phone)
  - Lenovo TAB-M10 (Tablet)
  - Dell Latitude 5410 (Laptop)

## **Browser Compatibility**
I have tested the website on Chrome, Edge and Safari. The website works well on all browsers tested. <br>
**Notes:** The Social Media Icons on the Contact page appear smaller on Safari.

## **Bugs** 
- **Hero Image Text:** The text pleaced on the hero image was hard to read. I've tried creating an opaque overlay to fix this issue. The overlay didn't work well on all screens. That's when I decided to use Photoshop to make the photo darker and also improve the quality of the photo trying to reduce the noise.

- **Hero Text on Mobiles:** The hero text on mobiles was too big and was pushing the book button outside the hero image. I fixed this issue by changing the font size on small screens. 

- **Footer on Contact & FAQ:** As the Contact and FAQ pages do not contain a hero image, the content of these pages on some screen sizes was not enough to push the footer to the bottom of the page. This issue was fixed by creating a main section and setting a minimum-height for the main section. Find more [here](https://www.youtube.com/watch?v=US_3XvufMLU&ab_channel=CodingJourney*/).

- **Horizontal Scroll Bar:** There was a horizontal scroll bar appearing on the website, which was unintentional. This issue was fixed by using 'overflow-x: hidden' on the body section of the website and removing bootstrap's gutters.

[Go to README file](README.md)