# Class 12 Reading Notes: Chart.js, Canvas

## JavaScript Canvas

- width and height: You can control the video size either with these attributes or with CSS. In both cases, videos maintain their native width-height ratio — known as the aspect ratio. If the aspect ratio is not maintained by the sizes you set, the video will grow to fill the space horizontally, and the unfilled space will just be given a solid background color by default.

- autoplay: Makes the audio or video start playing right away, while the rest of the page is loading. You are advised not to use autoplaying video (or audio) on your sites, because users can find it really annoying.

- loop: Makes the video (or audio) start playing again whenever it finishes. This can also be annoying, so only use if really necessary.

- muted: Causes the media to play with the sound turned off by default.

## Chart.js Documentation

- Resolution switching: The problem whereby you want to serve smaller image files to narrow-screen devices, as they don't need huge images like desktop displays do — and to serve different resolution images to high density/low density screens. You can solve this problem using vector graphics (SVG images) and the srcset with sizes attributes.

- Art direction: The problem whereby you want to serve cropped images for different layouts — for example a landscape image showing a full scene for a desktop layout, and a portrait image showing the main subject zoomed in for a mobile layout. You can solve this problem using the <picture> element.

## Easily Create Stunning Animated Charts with Chart.js

- The user is visually impaired, and is using a screen reader to read the web out to them. In fact, having alt text available to describe images is useful to most users.

- The spelling of the file or path name might be wrong.

- The browser doesn't support the image type. Some people still use text-only browsers, such as Lynx, which displays the alt text of images.

## Drawing Shapes With Canvas

- Users have turned off images to reduce data transfer volume and distractions. This is especially common on mobile phones, and in countries where bandwidth is limited or expensive.

- Decoration. You should use CSS background images for decorative images, but if you must use HTML, add a blank alt="". If the image isn't part of the content, a screen reader shouldn't waste time reading it.

- Content. If your image provides significant information, provide the same information in a brief alt text – or even better, in the main text which everybody can see. Don't write redundant alt text. How annoying would it be for a sighted user if all paragraphs were written twice in the main content? If the image is described adequately by the main text body, you can just use alt="".

## Drawing Text - Canvas API

- Text. You should not put your text into images. If your main heading needs a drop shadow, for example, use CSS for that rather than putting the text into an image. However, If you really can't avoid doing this, you should supply the text inside the alt attribute.

- Essentially, the key is to deliver a usable experience, even when the images can't be seen. This ensures all users are not missing any of the content. Try turning off images in your browser and see how things look. You'll soon realize how helpful alt text is if the image cannot be seen.
 
### Things I want to know more about

- From object to iframe — other embedding technologies (YouTube , Google Maps

- iframes in detail 

#### Link to my github portfolio [https://github.com/jenniferlidotson](https://github.com/jenniferlidotson)
