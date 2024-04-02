# Frontend Mentor - Blog preview card

## Table of contents
  - [Links](#links)
  - [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


### Links

- Solution URL: [Github]()
- Live Site URL: [Vercel]()

## My process

### Initialization
I began my project by initializing a Git repository, setting a solid foundation for version control and collaborative development.

### Building the Profile Card
With the repository set up, my next step was to design and build the profile card. I employed HTML5 for the structure, ensuring semantic clarity and accessibility. For styling, CSS3 was my choice, allowing me to create a visually appealing and responsive design.

### Desktop to Mobile Workflow
My development approach was desktop-first; I ensured that the layout and functionalities were fully optimized for larger screens. Once satisfied with the desktop version, I transitioned to refining the design for mobile devices, emphasizing responsiveness and a seamless user experience across various screen sizes.

### Built with

- HTML5
- CSS3
- Flexbox
- Desktop-first workflow

### What I learned



```html
<main>
    <div class="card-container">
      <div>
        <img class="article__illustration" src="assets/images/illustration-article.svg" alt="article img">
      </div>
      <div>
        <small>
          Learning
        </small>
        <p class="publication-date">
          Published 21 Dec 2023
        </p>
        <h2>
          HTML & CSS foundations
        </h2>
        <p class="pub-description">
          These languages are the backbone of every website, defining structure, content, and presentation.
        </p>
      </div>
      <div>
        <img class="avatar" src="assets/images/image-avatar.webp" alt="avatar">
        <small> Greg Hooper</small>
      </div>
    </div>
  </main>
```
```css
.container__card, small:nth-child(1){
    background-color: var(--yellow);
    color: var(--black);
    padding: 5px 10px;
    font-weight: 800;
    font-size: 16px;
    position: relative;
    border-radius: 5px;
    position: relative;
    top: 3rem;
    left: 1.5rem;
}
```


### Continued development

When it comes to continued development I'll be using the css code I used to center the main html tag using the following css:

```css
body{
    display: grid;
    height: 100vh;
    place-content: center;
}
```


### Useful resources

- [developer.mozilla](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Basic_Concepts_of_Flexbox) - This resource helped me determined if I was going to use the flexbox method for making the card with this project.
- [cssmatic](https://www.cssmatic.com/box-shadow) - This is an amazing resource which helped me quicken the process of writing the box-shadow css code needed for the card.


## Author

- Website - [Portfolio](https://www.ericaguayo.com)
- Frontend Mentor - [@EAguayodev](https://www.frontendmentor.io/profile/EAguayodev)
- Twitter - [@eric_emaildev](https://www.twitter.com/eric_emaildev)

## Acknowledgments

Special thanks to Frontend Mentor for inspiring me to take on the challenge of building the blod-preview-card. Their challenges have been instrumental in pushing my design and development skills further, providing me with a platform to innovate and craft unique solutions.

Special thanks to Andre Ferreira for giviing helpful advice to centering the card on a previous challenge I submitted.
