# CSS - Exercise - Responsive Web Design

Use fluid layouts, flexible images, and media queries to make a web page responsive.

---

## Exercise Brief

Take a basic web page, and make it responsive using CSS. Example⬇️

![Example](docs/RWD-v2.gif)

---

## Rationale

Understanding how to utilise fluid layouts, flexible images and media queries allow you to create Responsive web pages, that work on any sized device.

---

## Getting Started

1. `git clone` this repository into your main exercise folder.
- If you are not too sure how to do it, please follow this [video](https://www.loom.com/share/8a0d420720a94cb18021c2f418b19ae8?sid=b9435f7c-afd8-4031-88a3-44341f0e6b2f)
 to see how to git clone the repository into your device.
2. The code for this exercise should go into `/Submission/static/css/style.css`.

---

## Exercise Part A - Make the image flexible

1. Open `/Submission/index.html` in your browser, and open the [Device Toolbar](https://developers.google.com/web/tools/chrome-devtools/device-mode/) in your developer tools

   ![device toolbar](docs/device-toolbar.png)

2. Choose a mobile device from the dropdown. Notice how the image is too large for the screen and goes off the page?
3. Open `/Submission/static/css/style.css` in VS Code. Find the `/* Part A: Make the image responsive */` section in the file, and add your CSS to make the image flexible. You can reference [How TO - Responsive Images](https://www.w3schools.com/howto/howto_css_image_responsive.asp)
4. Check your image is flexible by changing the width of your browser, and ensuring the image resizes to fit inside the browser window

**Acceptance criteria**

- The image width never exceeds the browser width ![exercise](docs/RWD.gif)

## Exercise Part B - Tablet design

When the browser width gets larger, change the colour scheme of the web page.

- Use [Media Query example](https://codepen.io/zyc2339/pen/JjewjyW) on CodePen as a reference for this exercise.
- Keeping in mind the Mobile First design philosophy, we will add extra styles for larger screens by writing `min-width` media queries, and not repeating CSS.

When the browser width reaches `48rem`, change the colour scheme to match the following specification:

| selector                    | declaration                              |
| --------------------------- | ---------------------------------------- |
| `.background`               | `background: #fec7d7`                    |
| `.heading,`<br>`.paragraph` | `color: #0e172c`                         |
| `.button`                   | `color #fffffe`<br>`background: #0e172c` |


Add your code to the `Part B and C` section of the CSS file.

**Acceptance criteria**

- When the browser width reaches `48rem`, the colour scheme matches the specification for tablet
- Only `min-width` media queries are used
- There are no duplicated CSS declarations in the media queries

## Exercise Part C - Desktop design

When the browser width reaches `64rem`, change the colour scheme to match the following specification:

| selector      | declaration                              |
| ------------- | ---------------------------------------- |
| `.background` | `background: #16161a`                    |
| `.heading`    | `color: #fffffe`                         |
| `.paragraph`  | `color: #94a1b2`                         |
| `.button`     | `color #fffffe`<br>`background: #7f5af0` |

![Example](docs/RWD-v2.gif)

**Acceptance criteria**

- When the browser width reaches `64rem`, the colour scheme matches the specification for desktop
- Only `min-width` media queries are used
- There are no duplicated CSS declarations in the media queries

---

# Submit your Exercise

- [ ] Push your code with your folder back to this Github Repository
- [Tutorial Video for push your code](https://www.loom.com/share/e6fb52378eaf4636b62fc302f15b5aeb?sid=e6f68797-9dab-42b5-ae76-745316994fa6)

# Walkthrough Solution Video
[Video](https://www.loom.com/share/d65f40760a784193bbab71bb7fa95d20?sid=0ceb7c28-b117-487c-b453-e424a642176e)
