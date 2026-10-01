# Phantom Mask

Phantom Mask is a personal blog built as a single HTML page, styled after the dark, gothic personal websites of the early internet

It has a black background with a tiled dot pattern, a blood-red blackletter title, beveled buttons, a scrolling marquee and a visitor counter. Everything is written in plain HTML, CSS and JavaScript, with no frameworks, dependencies or build step.

## Features

- Home page with a list of posts and an About section
- Individual post pages with their own web addresses
- Sidebar navigation, "NEW!" tag on the latest post and a "last updated" date
- Responsive layout that works on desktop and mobile
- Reduced-motion support for the marquee and blinking text

## How it works

All of the blog's content is kept in two plain JavaScript objects at the top of the script. `SITE` holds the blog name, tagline, About text and links, and `POSTS` holds the posts. Colors and fonts are CSS variables at the top of the stylesheet. Changing the blog means editing text in those places, with no other code to touch.

## Autor

Sofia Yamane
