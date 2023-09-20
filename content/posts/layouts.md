---
title: 'Learn how to use layouts to structure your pages'
excerpt: 'Static layouts are HTML templates that can be used to structure and style the pages of your website. They provide a consistent design and layout across multiple pages. They provide a consistent design and layout across multiple pages.'
coverImage: '/assets/images/posts/cover2.webp'
date: '2023-03-17T05:35:07.322Z'
dateFormatted: March 17th 2023
authorName: Sandra Baker
authorPicture: '/assets/images/authors/sandra.jpg'
ogImageUrl: '/assets/images/posts/cover2.webp'
---

let's embark on a journey to explore the wonders of includes and how they can revolutionize the way you structure your website.

Includes are like the unsung heroes of web development. They are HTML snippets that can be reused throughout your site, allowing you to create consistent layouts and styles across multiple pages. Imagine having a navigation bar, a footer, or a hero section that you want to use on every page of your website. Instead of copying and pasting the same code over and over again, includes come to the rescue.

To demonstrate the power of includes, let's take a look at an example. Suppose you have a file called message.html located in the includes directory. This file contains a simple message snippet that you want to reuse on multiple pages:

```html
<p>This is just a simple message snippet that can be re-used inside of any page</p>
```

Now, let's say you have a page where you want to include this message snippet. You can simply use the `<include></include>` tags and specify the source file, like so:

```html
<layout title="This is the title of the page" src="main.html">
    <include src="message.html"></include>
</layout>
```

When the page is rendered, the output will include the message snippet:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>This is the title of the page</title>
    <style>[x-cloak]{ display:none; }</style>
    {tailwindcss}
</head>
<body>
    <p>This is just a simple message snippet that can be re-used inside of any page</p>
    <script src="/assets/js/main.js"></script>
</body>
</html>
```

As you can see, the message snippet is seamlessly included in the page, providing a consistent element across your website.

But what about the `{tailwindcss}` you see in the code? Well, that's where the magic of the Static framework comes into play. Static allows you to inject Tailwind CSS into your website and render the minified version in the final build. This ensures that your website not only has consistent layouts but also benefits from the power of Tailwind CSS.

To learn more about Static and how to use includes, you can refer to the official documentation here.

In conclusion, includes are a game-changer when it comes to creating consistent layouts in your website. By reusing HTML snippets, you can save time, reduce code duplication, and maintain a cohesive design across your pages. So embrace the power of includes and let your website shine with consistent brilliance!

> Note: The code snippets and examples provided in this blog post are for illustrative purposes only. Please refer to the official documentation of Static for accurate implementation details.
