The first test consists in making a grid of cities where Be Mate operates. In the file `screenshot.png` you will find the big screen result. This is, 9 cities distributed in a grid with 3 columns and 3 rows. The file `mobile.png` shows the small screen view, where only the 3 first items are shown. There is a middle state, with the cities distributed in 2 columns.

The font used in the design is Lato, you can find it at google fonts. All images needed are inside the assets folder.

Mobile:
  - Max width 480px
  - One column.
  - Three elements visible, the rest remain hidden.
  - There is a button that reveals all the hidden items when the user clicks on it.
  - Aspect ratio of images: 400x234

Tablet:
  - Max width 800px
  - Two columns and 8 elements visible
  - Aspect ratio of images: 480x280

Desktop:
  - Three columns and all elements visible
  - Aspect ratio of images: 640x374

What we expect:
  - Consider greenfield browsers (modern browsers only).
  - Don't use any third party library to complete this exercise.
  - Use sass (scss flavor please) to make the style layer.
  - If you need any javascript, use it vanilla. No need to jquery or whatever other library.
  - Bonus point: Fallback styles for IE9.

What do you need to deliver:
  - a zip file including all the html, compiled css and scss files do you need to complete the challenge. The html should be ready to work when opened in a browser.
