# tinder-auto-swiper
In web and Off web tinder simple bot swiper

Tinder 2020 Auto right swiper bot made in JavaScript/JS/javascript/Javascript

How to use:
1. Go to Tinder.com.
2. Login.
3. Click F12 or CTRL+SHIFT+I
4. Copy tinderInWebAutoSwipe.js content.
5. Press Enter.

tinderInWebAutoSwipe.js content :

let index = 1;
let startSwiping = () => {
let swipeRight = document.querySelector('[aria-label="Like"]').click();
console.log("You have liked " + index++);
setTimeout(startSwiping, 1000);
};
let beginSwiping = setTimeout(startSwiping, 1000);
