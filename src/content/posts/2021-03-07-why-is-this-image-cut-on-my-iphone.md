---
template: blog-post
title: Why is this Image Cut on My iPhone?
slug: /responsive
date: 2021-03-06 21:55
description: "responsive layout "
featuredImage: /assets/gettyimages-1061328872-e2ad8c47a8ed4e23a46999635be12315.jpg
---
![](/assets/atlanta-responsive-website-design-development-m16.png)

*What is Responsive Web Design*?

You maybe asking yourself what in the world is responsive web design? Well, look no further today I will help you figure out what it is, when and how to use it well. Responsive web design is an approach that deals with rendering web pages on a variety of devices with different screens and windows. Allowing the page to automatically adapt to a screen size whether it be a mobile phone, desktop, or a laptop. The page must respond to the user and the device the user is on. For example, a tablet might show content in 2-3 columns, while a phone might display content on only a single column. Screen sizes are always changing, so its important for your site to adapt to any size. Now that touchscreen is huge, many visitors will be using it, so its something to consider when designing your site. The practice of responsive web design consists of layouts, images, and but not only flexible grids.

*How Use Images:*

Images can be a great tool to catch a reader and make their interest rise in your website. This can be very tricky since images can be scaled too much causing a scroll bar to appear on the side of the image. You can add a very simple style rule that in most cases will work. Take a look at this following code and don’t hesitate in copying it and using it as an example.

Img {

max-width: 100%

}

Now this code will act to ensure that the image does not scale larger than its actual size. Precisely the *max-width* to *100%* will allow the image not to scale above actual size. In order to make your images fluid it is ideal to make them display at maximum size. Make sure no other width-based image styles override this rule. This can improve the quality of the image greatly. The *img* element is a very powerful element. Not only does it provide content, but it can download, decode, and render content. Now if you have a small image and you want to keep its image quality then you want to keep its aspect ratio. In order to do so you must set the *background-size* property to contain. This will tell the browser you want the image to scale to fit the content area but not lose its aspect ratio or in other terms get blurry. An example of this I will show below:

div {

width: 100%;

height: 300px;

background-image: url( 'image.jpg' );

background-size: contain;

}

Here we have the width and height set to what we want. We have the *background-image url* set and below that we can see our *background-size* set to *contain*. Try this out for yourself go ahead and copy and paste this code and you will see a difference when you are trying to fill an image in a small area. Implement these codes in your next project and watch your website pop and images to render properly in their appropriate size.



![](/assets/download.png)

*Flexible Layouts:*

Most layouts that are used in responsive web pages consist of flexible layouts. This means the practice of building the layout of a website with a flexible grid, that can be capable of resizing to any width. Now flexible layouts do not use measurement units, such as pixels or inches which we are used to seeing. This is since the viewport height and width are consistently changing from device to device. Website layouts need to adapt to this change since fixed values have too many constraints. Flexible layouts use relative length units, mostly percentages. These relative lengths are used to declare common properties such as *font-size, width, margin,* or *padding.* Within these layouts you have “media rules” which can help your page detect whether the user is using a phone, tablet, or desktop and apply the different styles accordingly. This is done by overriding CSS styles for different orientations and sizes. The *@media* rule is used in “media queries” to apply different styles for different media types/devices as I said before. Many things can be checked using media queries. Before I tell you let me explain what media queries are. They enable us to create a responsive experience where specific styles are applied to small screens, large screens, and all in between. Therefore, we can use media queries to check: width and height of the viewport, width and height of the device, whether the device is in landscape or portrait mode, and what resolution the user is on. All these combine to made a fluid, and flexible layout that can be displayed on any device.