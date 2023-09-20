---
title: 'Learn how to re-use HTML snippets with Includes'
excerpt: 'Includes are HTML snippets that can be reused throughout a website. They are stored in the "includes" directory and can include components like navigations, footers, and hero sections.'
coverImage: '/assets/images/posts/cover3.webp'
date: '2023-03-18T05:35:07.322Z'
dateFormatted: March 18th 2023
authorName: Carl Peterson
authorPicture: '/assets/images/authors/carl.jpg'
ogImageUrl: '/assets/images/posts/cover3.webp'
---

Ahoy there, fellow developers! Today, we embark on a delightful journey into the enchanting realm of Includes in Static. Prepare to be amazed as we uncover the secrets of code reusability and witness the power of HTML snippets that can be reused throughout your website.

## Setting Sail: What are Includes?

Includes, my dear friends, are like magical snippets of HTML that can be reused across your entire website. They reside in the mystical "includes" directory, ready to be summoned whenever you need them. These snippets can be anything your heart desires - navigations, footers, hero sections, and more. With includes, you can wave goodbye to repetitive code and embrace the wonders of efficiency and simplicity.

## Unveiling the Magic: How to Use Includes

Using includes is as easy as pie! Just imagine yourself as a sorcerer, summoning the powers of code reuse. To include an HTML snippet in a page, simply enclose it within the <include></include> tags. Voila! The snippet will be seamlessly integrated into your page, spreading its charm and saving you precious time.

## A Tale of Reusability: The Adventures of a Message Snippet

Let me regale you with a tale of a humble message snippet, a snippet that could be reused across any page. Imagine a snippet nestled in the includes/message.html file, whispering its wisdom to all who encounter it:

```html
<p>This is just a simple message snippet that can be re-used inside of any page</p>
```

Now, picture yourself in a page, yearning to include this snippet. Fear not, for it is a breeze! Just use the <include src="message.html"></include> incantation within your page, and behold the magic unfold.

## The Grand Finale: A Symphony of Code and Creativity

As the final act of this enchanting journey, let us witness the culmination of our efforts. When your page is rendered, the HTML gods will weave their spell, and the output shall be a masterpiece. The snippet, once a mere fragment, will now be harmoniously integrated into the page, spreading its message far and wide.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>{title}</title>
    <style>[x-cloak]{ display:none; }</style>
    {tailwindcss}
</head>
<body>
    <p>This is just a simple message snippet that can be re-used inside of any page</p>
    <script src="/assets/js/main.js"></script>
</body>
</html>
```

# Conclusion: Embrace the Magic of Includes

And so, dear developers, we reach the end of our whimsical journey into the world of includes in Static. We have witnessed the power of code reusability, the joy of efficient development, and the wonders of simplicity. Embrace the magic of includes, and let your code soar to new heights of elegance and efficiency.