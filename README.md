# Slider JS

## Dead simple slideshow for only 4kb.

Slider JS it's a lightweight script that allows you to create and use an slider on your site.

Just download the script from the dist directory and use it.

- If you have a module bundler like webpack, then use the SliderJSModule version, and import it as you would do with any module.

- If you only need to link it in your HTML, then download the SliderJSBrowser version.

### How to use.

You only need to have a parent element in which the slider its going to be generated as a child, and the images.

```javascript
const parentElement = document.querySelector('#parentElement');

const images = [
  {
    src: 'Source of the image',
    alt: 'Alternative text for the image'
  },
  {
    src: 'Source of the image',
    alt: 'Alternative text for the image'
  }
];

const slider = new Slider(parentElement, images);
```

And thats it.

Initally it will have no css but do not worry, there is a SCSS file in the dist folder with all the styles that i used. Feel free to modify them as you want.
