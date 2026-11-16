# INFR3120 Assignment 2 - My Portfolio

This is my personal portfolio website for INFR3120 Assignment 2. I made it using Express Generator and EJS. It has some info about me, a few projects I've worked on and a contact page. I wanted to keep the design pretty simple but still make it look like me, so I went with plum, pink and sage green.

Website: https://infr3120-assignment-02-ivqq.onrender.com/

GitHub: https://github.com/idzi11/INFR3120-Assignment-02

## What I used

- Node.js / Express Generator
- EJS, HTML and CSS
- Bootstrap and Font Awesome
- GitHub for my commits
- Render to put the site online

## Pages

- **Home** - a quick welcome and introduction
- **About Me** - more about me, with my picture and intro video
- **Projects** - 4 projects I've worked on, including the purchasing and accounts payable project, Skyfox Games SEO analysis, 1960s fashion website and family tree project
- **Contact Me** - name, email, cell number, comments and two dropdowns for preferred contact method and how they heard about me

The contact form is just for the front end right now, it doesn't actually send any messages.

## Files

`app.js` is where the Express app is set up. My routes are in `routes/index.js` and the pages are in `views` as EJS files. I also made partials for the header, nav and footer so I didn't have to repeat them on every page. The CSS and images/video are in the `public` folder.

## How to run it

Open the project folder in VS Code and run:

npm install
npm start

Then go to `http://localhost:3000`.

## Styling

I used my CSS from Assignment 1 as a reference for the centered boxes, spacing and project cards, then changed the colours for this version. I also used Bootstrap for the navbar and form and Font Awesome for the icons. I added some gradients and borders to the main sections.

## References

These are the sources I used for class work or to double check syntax for a couple things I added:

- INFR3120 lecture examples - Express, EJS and the general project setup
- My Assignment 1 CSS files (`laptop.css`, `tablet.css`, `mobile.css`) - reference for some of my styling
- MDN, `!important` in CSS: https://developer.mozilla.org/en-US/docs/Web/CSS/important
- MDN, HTML `<select>` element (dropdowns): https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/select
- Bootstrap 5.3, select forms: https://getbootstrap.com/docs/5.3/forms/select/