# Frontend Mentor - Stats preview card component v2

![Design preview for the Stats preview card component coding challenge](./design/desktop-preview.jpg)

## Links

- [My Solution Page](https://www.frontendmentor.io/solutions/fem3statspreviewcardcomponentv21-the-mobile-first-solution-xI-gTwSLwB)

- [The Live Site](https://adonmez04.github.io/FEM-3-Stats-preview-card-component-v2/)

- [The Challenge Page: Stats preview card component](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62)

## Welcome! 👋

Welcome to my solution page. This is my second solution for this project. I don't want to focus on another project before my current project looks the same as the design file. I believe this is very useful for me. That's why I spend lots of time on my projects. Thus, I get experience in each solution and perspective. I recommend this style to everyone.

I checked some good solutions and I got a comment about my first solution. I applied them to my project. I can pass the project now because it looks the same as the design file.

However there is no end to this project, I can develop my code according to different styles. There is no end to coding even for this basic project. I need to improve lots of things and it's totally normal. I'll improve them one after another. For example, I can change my `iteration area` as `ul list`. It's a major mistake, I couldn't see this, so embarrassing:)

At least, I managed to change the background-color of the images. I don't see the same color as the design file on the solution pages. I think there is something wrong with this project.

## The Problems and Solutions

In this solution, I focused on changing the background color. I got a comment about this, I applied it to my code but nothing changed. I tried another style, and I solved the problem by chance. And I didn't need to use any pseudo-elements. It was a clear solution.

And I wrote my class names again according to BEM notation. I think I passed a milestone. I finally understand BEM.

```css
.section-card__img-area {
  background: #ab5cdb;
  /* I used the parent element to add the color in the right position. */
  /* I think this property works like a layer. */
  /* This value came from the figma file. There is another color in the style file that doesn't work. */
}

.section-card__img {
  background-image: url(./images/image-header-mobile.jpg);
  /* You should change the image for the desktop version. */

  background-size: cover;
  background-position: top;
  background-repeat: no-repeat;

  mix-blend-mode: multiply;

  opacity: 0.7411;
  /* This value came from the figma file. */

  width: 100%;
  height: 15rem;
}
```

```html
<div class="section-card__img-area">
  <div
    class="section-card__img"
    role="img"
    aria-label="A group of women in the work."
  ></div>
</div>
```

## Good Implementations

- [There is a good comment here.](https://www.frontendmentor.io/solutions/stats-preview-card-component-ac79OEYBh_)

## Acknowledgments

- Thanks Hassia Issah for the comment. [@Hassiai](https://www.frontendmentor.io/profile/Hassiai)

## Author

- My Frontend Mentor Profile Page - [@adonmez04](https://www.frontendmentor.io/profile/adonmez04)
- For those of you reading this, have a nice day!
