# InDevelopmentLandingPage
A simple static landing page for our website while we work out our business plan and develop our site

## Goals
Hosting a site on a website-builder platform can get expensive, especially since I don't have time to run a consistent business during the school semester. So, I'm building and hosting this single static page to redirect people who find my site to my LinkedIn, YouTube, and Github accounts. That way, I can stay connected to my business's website while the business plan and full website are under development.

## Development
Use the live server extension to start serving the src directory to the browser. Then use "npm run dev" to start watching the src directory for changes to the site files for tailwind changes.

~~~
npm run dev
~~~

Since we connected this repository to CloudFlare, changes committed to the main branch are automatically published to the hosted site. So, to make changes, modify the site in a development branch, create and merge a pull request, and wait for CloudFlare to make the changes.

## Site Look
Use node.js, tailwindcss, and CloudFlare Pages as tech stack to build page

(It turns out CloudFlare offered a simpler and cheaper solution for free hosting)

Include PDF document of future site plan, logo images, and subscribe button. Also include links to your other social media. Finally, include some text to address the audience.

## To-Do
- Create repository
- define goals in readme
- create static page plan in readme
- install node
- install tailwind
- create html page
- place components in html
- setup tailwind development
- style with tailwind
- ensure mobile works
- get feedback
- ~~host on AWS~~
- Create CloudFlare Pages for site
- Transfer domain name to cloudflare
- Connect page to github
- Connect page to domain
- Test domain name, wait 24 hours for full propagation
- LinkedIn Project
- LinkedIn post