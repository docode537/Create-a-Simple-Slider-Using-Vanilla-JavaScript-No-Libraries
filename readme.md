# Vanilla JavaScript Infinite Loop Slider

A simple, lightweight, and customizable infinite loop slider built with vanilla JavaScript. It includes navigation dots, auto-slide functionality, and smooth transitions.

## 🚀 Branches

This project has two branches:

1. **slider-part-1**: A basic infinite loop slider without smooth transition from the last to the first slide (or vice versa).
2. **slider-part-2**: An enhanced version with smooth transition when looping from the last slide back to the first (or vice versa).

## Features
- **Infinite Loop:** Seamlessly loops through slides without interruption.
- **Auto-Slide:** Slides move automatically after a specified interval.
- **Navigation Dots:** Allows users to navigate to a specific slide.
- **Lightweight:** No external libraries required.
- **Customizable:** Easily modify timing, transitions, and styles.

## Demo
![slider demo](image.png)

## Installation
1. Download or clone the repository.
   ```sh
   git clone https://github.com/docode537/Create-a-Simple-Slider-Using-Vanilla-JavaScript-No-Libraries-.git
   ```
2. Open `index.html` in your browser.

## Usage
### HTML Structure
Ensure you have the following structure in your HTML file:
```html
<div class="slider-container">
    <div class="slider">
        <div class="slide">Slide 1</div>
        <div class="slide">Slide 2</div>
        <div class="slide">Slide 3</div>
    </div>
    <div class="dots"></div>
</div>
```

### CSS Styling
Customize the styles to match your design needs.

### JavaScript
```html
<script>//slider code</script>
```
Ensure the script initializes after the DOM is loaded:
```js
document.addEventListener("DOMContentLoaded", function () {
    initSlider();
});
```

## Customization
You can modify the following options in `js code`:
- Change the auto-slide interval.
- Modify the transition effect.

## Future Enhancements
- Add touch/swipe support for mobile devices.
- Pause auto-slide on hover.
- Add arrow navigation.
## 🎥 Video Tutorial
Watch the tutorial video: [Link](#).
## Blog Post Tutorial
🐦 blog post: [Blog Post](https://docode.co.in/post/simple-infinite-loop-slider-using-vanilla-javascript)  
## 📩 Connect With Me
🌐 Website: [DoCode](https://docode.co.in/)
📧 Email: docode537@gmail.com 

