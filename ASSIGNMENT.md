# 📄 Feature Cards

Build a set of homepage feature cards and a call-to-action section with HTML and CSS, using
CSS Grid for the layout and a little Flexbox for alignment.

## 🎯 Overview

In this exercise, you will build a set of **homepage feature cards** using HTML and CSS.

Feature cards are small content blocks often used on homepages to preview important parts of
a website. They break information into smaller sections that are easier to scan and
understand. Below the cards is a **call-to-action section**: a highlighted area designed to
stand out and encourage the visitor to take the next step.

You'll begin with starter files and follow along as we build the feature cards section
together. Along the way, you will use CSS Grid to create a practical layout, use a small
amount of Flexbox to align icons and headings, and style a call-to-action section and button.

> [!IMPORTANT]
> **The companion videos for this exercise are in Canvas**, on the assignment page. They
> walk you through every step, so watch them there instead of working from this file
> alone.

## 🧠 What You Will Learn

By completing this exercise, you will practice how to:

- Build a repeated content structure (a card) and reuse it
- Arrange cards into columns with CSS Grid
- Line up an icon and a heading on the same row with Flexbox
- Create visual hierarchy with cards and a call-to-action section
- Style a link so it looks like a button, including a hover state
- Use a media query to stack the cards on smaller screens

By the end of the exercise, your page should include:

- an introduction section explaining feature cards
- a three-column set of feature cards
- an icon and heading on the same row inside each card
- a call-to-action section below the cards
- a styled button
- responsive adjustments for smaller screens

## 🎬 Watch the Videos in Canvas and Follow Along

The screencast videos are on this assignment's page in **Canvas**, not in this repo. Watch
them **in order** and follow along in Visual Studio Code. Pause whenever you need time to
finish a step — it is normal to pause, rewind, and rewatch parts of a coding demonstration.

Each video builds on the previous one, so please don't skip ahead.

| Video | What you will do |
| --- | --- |
| **Intro** | See what feature cards and call-to-action sections are, and what you'll build. |
| **Part 1 — HTML** | Build the HTML structure for the feature cards and the call-to-action section. |
| **Part 2 — Grid Layout and Card Styles** | Use CSS Grid to arrange the cards into columns and begin styling the cards themselves. |
| **Part 3 — Icons and Flexbox** | Line up the icons and headings using Flexbox. |
| **Part 4 — Call-to-Action Section** | Style the call-to-action section and button. |
| **Part 5 — Media Query** | Make the cards stack into a single column on smaller screens. |
| **Part 6 — On Your Own** | No video. Customize your page using the requirements [below](#-part-6--on-your-own). |

> [!IMPORTANT]
> **A few steps in this repo are different from the videos.** Follow the videos for the
> HTML and CSS, and follow this repo for getting your files and submitting:
>
> - **Getting the starter files:** don't download a ZIP. Create your own repo from this
>   template and open it with GitHub Desktop, as described in the
>   [README](README.md#-getting-started).
> - **Submitting:** don't zip your folder or upload a file. Publish your page to GitHub
>   Pages and submit a pull request URL in Canvas, as described in the
>   [README](README.md#-submitting-the-assignment).

> [!IMPORTANT]
> Open the entire project **folder** in VS Code, not a single file. Keep `index.html`,
> `reset.css`, and `cards.css` together in the root folder, and don't rename them.

## 📂 Starter Files

| File | Purpose |
| --- | --- |
| `index.html` | The page content. The header, intro section, and footer are done. You will add the class names and stylesheet links the cards and call-to-action section need. |
| `reset.css` | A reset stylesheet that removes browser default spacing and styling. You don't need to edit it. |
| `cards.css` | The page styles. The header, main area, intro section, and footer are styled. The feature card, call-to-action, and media query rules are empty for you to fill in. |

## ✏️ Part 6 — On Your Own

Your finished page should not remain an exact copy of the example. After following along,
customize your version by doing **at least three** of these:

- [ ] Change the text in all three cards
- [ ] Change the emoji icons
- [ ] Replace the emoji with [Font Awesome](https://fontawesome.com/) icons
- [ ] Change the call-to-action heading text
- [ ] Change the call-to-action paragraph text
- [ ] Change the button text
- [ ] Change at least two visual style choices — for example colors, spacing, border radius,
      shadows, hover effects, font sizes, or borders

> [!TIP]
> **Using this in your final project:** you're welcome to repurpose this code for your final
> project if it fits your site. If you do, customize it enough that the result clearly feels
> like your own work and not an exact copy of the exercise. Feature cards are **not**
> required on your homepage — only use them if they suit the site you're making.

## 🧮 Grading

| Criteria | Points |
| --- | --- |
| **HTML structure** — both stylesheets are linked; the cards section, each card, its title row, icon, and the call-to-action section and button use the class names from the videos | 2 |
| **Card grid and card styles** — `.card-grid` uses CSS Grid to show three columns with a gap; the cards are styled and consistent in height | 2 |
| **Icons and Flexbox** — `.card-title` uses Flexbox so each icon and heading sit on the same row, vertically centered | 1 |
| **Call-to-action section** — the section stands out from the rest of the page, and the link is styled as a button with a hover state | 2 |
| **Media query** — on small screens the cards stack into a single column | 1 |
| **On your own** — at least three customizations from Part 6 | 2 |
| **Total** | **10** |

## ✅ Before You Submit

Check the following:

- [ ] `index.html`, `reset.css`, and `cards.css` are all in the root folder of the repo
- [ ] `index.html` links to `reset.css` first, then `cards.css`
- [ ] The three cards display side by side in three columns on a wide screen
- [ ] Each card's icon and heading sit on the same row
- [ ] The call-to-action section stands out, and its button changes on hover
- [ ] When you make the browser window narrow, the cards stack into one column
- [ ] You made at least three customizations from Part 6
- [ ] You saved all your files
- [ ] The page is live on GitHub Pages and the URL is in your pull request

## 🛠️ Troubleshooting

If something is not working, check these common issues first:

- Did you save both `index.html` and `cards.css`?
- Are the `<link>` elements inside the `head`, with the file names spelled exactly right?
- Does every class name in your HTML match the selector in your CSS? `card-grid` in the HTML
  needs `.card-grid` (with the dot) in the CSS.
- Is `display: grid;` on the **parent** `.card-grid`, not on each `.card`?
- Is `display: flex;` on `.card-title`, the element that wraps the icon and the heading?
- Does your media query have a width value, like `@media (max-width: 480px)`?
- Are all your CSS rules closed with a `}`? One missing brace can break every rule after it.

**Having problems with the videos?**

- **Getting a warning about third-party cookies?** Try using Chrome. Safari's default
  security settings may prevent embedded Canvas videos from playing unless those settings
  are changed.
- **Getting an "Access Denied" error?** Refresh your browser. In many cases, the videos
  will load correctly after the page reloads.

## 📚 Resources

- [MDN — CSS grid layout](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/CSS_layout/Grids)
- [MDN — Flexbox](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/CSS_layout/Flexbox)
- [MDN — Media query fundamentals](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/CSS_layout/Media_queries)
- [MDN — `:hover`](https://developer.mozilla.org/en-US/docs/Web/CSS/:hover)
- [Font Awesome](https://fontawesome.com/) — optional icons to replace the emoji
- [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/#validate_by_input) —
  paste your CSS in to catch missing braces and typos

---

The AI policy and submission instructions are in the [README](README.md).
