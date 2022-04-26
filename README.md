# YouTube Clone Using HTML And CSS Only

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### Screenshot

![Screenshot](/screenshots/screenshot.png?raw=true "View Of Page")

### Links

- Solution URL: [Add solution URL here](https://github.com/prakash-naikwadi/YouTube-Clone-HTML-CSS-ONLY)
- Live Site URL: [Add live site URL here](https://prakash-naikwadi.github.io/YouTube-Clone-HTML-CSS-ONLY/)

## My process
- Started Learning CSS On Youtube.
- I follow a course and do exercises given for each topic, Also refer to MDN 
Reference for a clear understanding of some topics.
- Also for Flexbox And Grid played Flexboxfroggy And CSSGridGarden Games **Highly Recommended**.
- **All  Links are in [Useful resources](#useful-resources).**

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- CSS Position and Display Properties.

### What I learned
- I have learned all the basic concepts of HTML and CSS and I am now comfortable with CSS properties.
- Till there are a lot of things to learn in CSS and overall all Web Development, this project had give me the confidence of developing even complex websites.

- Following Are some **features** of this Clone that are very interesting to me.    
  **1. Adding TimeStamp On Thumbnail Of Video**    
    - **sceenshot**  
        ![Screenshot](/screenshots/thumbnail-screenshot.png?raw=true "View Of Page")  
        **code snippets**:
        ```html
        <div class="video-preview">
            <div class="video-thumbnail">
                <img src="thumbnails/thumbnail-1.webp" alt="thumbnail-1">
                <div class="video-length">14.20</div>
            </div>
            <div class="video-description">
                <div class="profile-icon">
                    <img src="channel-pictures/channel-1.jpeg" alt="channel-1">
                </div>
                <div class="video-description-info">
                    <div class="video-title">Talking Tech and AI with Google CEO Sundar Pichai! </div>
                    <div class="channel-name">Marques Brownlee </div>
                    <div class="views-count">3.4M views · 6 months ago</div>
                </div>
            </div>
        </div>
        ```
        ```css
            .video-length{
                position: absolute;
                background-color: black;
                color: white;
                font-size: 12px;
                font-weight: bold;
                border-radius: 2px;
                padding: 3px;
                bottom: 10px;
                right: 10px;
            }
            
            .video-thumbnail img{
                width: 100%;
            }
            
            .video-description{
                display: grid;
                grid-template-columns: 50px 1fr;
                margin-top: 8px;
            }
            
            .video-description .profile-icon img{
                width: 36px;
                border-radius: 50%;
            }
            
            .video-description-info{
                margin-left: 0px;
            }
            
            .video-description-info .video-title{
                font-weight: 500;
                font-size: 14px;
                margin-bottom: 10px;
            }
            .video-description-info .channel-name, .views-count{
                margin-top: 5px;
                font-size: 12px;
                color: grey;
            }
        ```

### Continued development

- Started Learning Responsive Web Design And Trying To Apply this on future projects.
- Flexbox, Grid, Display and Grid layout properties are very interesting and they need practice to mater so I am focusing on that when developing future projects.  

### Useful resources

- [HTML & CSS Full Course - Beginner to Pro (2022)](https://www.example.com) - This is the course I follow for this YouTube Clone, very beginner friendly.
- [CSS Tutorial In Hindi (With Notes) 🔥](https://www.example.com) - I watch this course for point wise explaination and notes. I first learn one topic from this video and then go to above course for better understanding topics and above course has very good exercises as well.
- [Flexbox Froggy Game](https://flexboxfroggy.com/) - Best Resourse for practicing Flexbox.
- [CSS Grid Garden Game](https://cssgridgarden.com/) - Best Resourse for practicing CSS Grid.
- [CSS Position Property](https://css-tricks.com/absolute-relative-fixed-positioining-how-do-they-differ/) - I also refer this for css position
- [MDN Resourse For CSS](https://developer.mozilla.org/en-US/docs/Web/CSS) - Best Resourse for CSS because they have given live demo of all properties and their values.  

## Author

- Website - [Prakash Naikwadi](https://www.linkedin.com/in/prakash-naikwadi-6b9a60182/)
- Twitter - [@PrakashNaikwad6](https://www.twitter.com/PrakashNaikwad6)  

## Acknowledgments

- 

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

