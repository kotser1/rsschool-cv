# Sergei Kotelnikov
**Address:** Moscow, Russia.
***

## Contacts:

* Email: [newelvin@gmail.com](mailto:newelvin@gmail.com)
* Telegram: [@kotser](https://t.me/kotser)
* Skype: kotser

## About me:
I'm a beginner frontend developer.

## Skills:
* HTML5
* CSS, SASS
* BEM methodology
* GIT, GitHub
* Gulp
* Photoshop, Figma
* JavaScript basics

## Code example:
``` JavaScript
const popupOrder = document.querySelector('.modal-order');
const openOrderButton = document.querySelectorAll('.button-buy');
const closeOrderPopupButton = popupOrder.querySelector('.modal-close');

let buyButton = function (evt) {
  evt.preventDefault();
  popupOrder.classList.add('modal-show');
};

for (let i = 0; i < openOrderButton.length; i++) {
  openOrderButton[i].onclick = buyButton;
}

closeOrderPopupButton.addEventListener('click', function () {
  popupOrder.classList.remove('modal-show');
})

document.addEventListener('keydown', function (evt) {
  if (evt.keyCode === 27) {
    popupOrder.classList.remove('modal-show');
  }
});
```
***
## Experience:
**HTML-Academy** - HTML&CSS course

## Education:
Moscow State University of Instrument Engineering and Computer Sciences - Human resources management. (2001 - 2006)

## Languages:
* Russian - Native
* English - A2