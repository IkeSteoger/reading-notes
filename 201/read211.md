# 201 Reading 11

## Audio, Video, Images

### Video & Audio Content

Video & audio used to use features like Flash & Silverlight. Both of which had security & accessibility issues and thus are obsolete in favor of HTML `<video>` and `<audio>` and the availability of JavaScript API to control them. (Mozilla.org)

The `src` in a `video` element works the same as an `img` element, it contains a path to the video you want to embed. The `controls` command will include the browsers own control interface or you can build your own using the JS API. You must include a way to start & stop the media, as well as adjust the volume.

Audio & Video are friends - best friends in fact. They go everywhere together & work almost the same - except one is just an audio clip and the other is video with audio.

### Complete Guide to Grid

Grid layout differs from Flexbox in that Flex has one-directional flow, and Grid can be more fluid in directional movement.

Grid Contrainer: The element on which `display: grid` is applied.

Grid Item: The child of the grid container - direct child!

Grid Line: Diving lines that make up the structure of the grid. Vertical or Horizontal.

Grid Cell: The space between two adjacent row & two adjacent column grid lines.

Grid Track: The space between two adjacent grid lines.

(css-tricks.com)

### Responsive Images

Accessibility! Your website might not work properly in different screen sizes if you don't account for them.

`srcset`: defines the set of images we point the browser to our pictures to choose between, and what size each image is. `srcset="name.jpg 480w, name2.jpg 800w`

`sizes`: defines a set of conditions/screen widths and indicates what image size would be best to choose from the `srcset`. `sizes="(max-width: 600px) 480px, 800px"` this sets the picture to the 480px size when using 600px or below width device and the rest of the sizes use 800px.

Using `srcset` instead of CSS or JavaScript because the images are already pre-loaded before the CSS & JavaScript. This way you don't load multiple sizes of a single image on the screen or have to squish/stretch your photos.

## Things I want to know about

Is the grid actually better than Flexbox? Perhaps situationally? Need to use it to find out!
