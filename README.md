[link to the lesson here](https://www.codecademy.com/courses/learn-css-variables-and-functions/lessons/learn-css-functions/exercises/css-background-image)

# CSS FUNCTIONS

## Setting a Background Image

> The first CSS function we are going to learn about is the url() function. This function is used to link to external resources and load them into the stylesheet. These resources can be images, fonts, other stylesheets, and more. The url() function takes a single argument: the location of the resource in string format. The location of the linked resource can be provided as absolute or relative paths.

> If we were to want to set an image that has a relative path of images/bg-image.jpg as a background, we would need to load the path to that image as the argument for the url() function as a string.

```js
.main-banner {
  background: url('images/bg-image.jpg');
  background-repeat: no-repeat;
  background-position: right;
}
```

> Above we set the background of our .main-banner selector ruleset to be images/bg-image.jpg. The background was set to not repeat and be placed on the right side of the banner. Notice how a relative path was used as the argument.

> Background images set using the url() function may not always fill the background in the specific way we want. For instance, if the background image is smaller than the container area, the image will repeat in a tile pattern by default. There are various properties that allow us to set the background image in the manner we want, such as background-repeat, background-size, and background-position, to name a few.

memory jog
/c/Users/glads/Documents/PROJECTS_AT_CODECADEMY/CSS-Functions-Setting-a-Background-Image
