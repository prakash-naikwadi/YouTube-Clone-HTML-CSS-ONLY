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
    - **sceenshot  **  
        ![Screenshot](/screenshots/screenshot.png?raw=true "View Of Page")
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
            
                    }
        ```

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

**Note: Delete this note and the content within this section and replace it with your own plans for continued development.**

### Useful resources

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.**

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**
