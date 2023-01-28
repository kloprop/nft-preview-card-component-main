# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Links](#links)
- [My process](#my-process)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

It takes me some time to figure out how to add a hover effect to the image, so the background color is changed and to show the eye at the same time as I had never added hover effect to image before.

I was also stuggled about how I can add the svg icon to the markup cuz I know that there are svg tags available, but I cant find the id as well as the use tag of those svg icons, so I just add them as an image. It probably not a good practice, so I would look at others' code after submission.

I also not sure whether it is a good practice to put every images into a container for styling the images.

And I mostly use flex for aligning items, I am also not sure whether there are better way to do so.

### Links

- Solution URL: [Add solution URL here](https://github.com/kloprop/nft-preview-card-component-main.git)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

### What I learned

Changing background color of the image when hover

```css
.card__header:hover::after {
  position: absolute;
  content: "";
  display: block;
  top: 0;
  left: 0;
  height: 100%;
  width: 100%;
  background: hsl(178, 100%, 50%);
  opacity: 0.5;
  border-radius: 5px;
}

Applying flex to multiple elements


### Useful resources

- [Overlay background ](https://www.w3schools.com/howto/howto_css_overlay.asp) - This provides me the way to do overlay.


## Author

- Website - [Shisah] https://www.hknewsgroups.com/  Just to share: This is a website built after I learned HTML and CSS so it is rough and simple. It is a website showing news media in Hong Kong , unfortunately it is written as chinese but I would update it after I mastered the skill.
- Frontend Mentor - [@kloprop](https://www.frontendmentor.io/profile/kloprop)





```
