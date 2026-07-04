# DHH
In the spirit of the 90's No Build philosophy advocated by David Heinemeier Hansson (aka DHH), I show how to make a webpage in the most simplest way without the cumbersome management and maintenance of frameworks, servers, or any other unnecessary dependencies leading to tech debt. There is a place and time for leveraging a JavaScript framework like Angular, React, etc., but this solution shows a very lightweight, elegant, and editable directly in whatever text editor is on hand.

## What “No Build” Means Here
A single HTML file (optionally with a tiny CSS file) that works in any browser.

No npm install, no bundlers, no transpilers, and no dev servers.

Content, layout, and styling live together in a small, understandable codebase anyone can open and edit.

This mirrors the early web, where publishing a page was as simple as writing HTML and uploading it to a server or dropping it into a folder.

## Why This Approach
Avoid tech debt: Fewer moving parts mean fewer things to upgrade, break, or migrate later.

Transparency: You can see everything the page does at a glance—no magic, no hidden build steps.

Longevity: A simple HTML file will still open in a browser many years from now, even if today’s frameworks are outdated.

For small sites, documentation pages, or personal projects, this level of simplicity is often not just sufficient—it’s ideal.

## Who This Is For
Designers and visual artists who want to publish a page without becoming full-time JavaScript engineers.

Writers and researchers who need a stable, low-friction way to share text, images, or notes.

Developers who want a reminder that not every project needs a build pipeline or a stack of dependencies.

If you can open a text editor and a browser, you already have everything you need.

## Basic Usage
Open index.html (or whatever main file you choose) in your text editor.

Edit the HTML: change text, add images, adjust links.

Save the file and open it directly in your browser, or upload it to any static hosting service (GitHub Pages, Netlify, a simple web server, etc.).

You can version control the file with Git, but you don’t have to add any build steps or CI complexity unless you truly need them.

## Optional Styling
If you want to refine visual design:

Add a <style> block directly in the HTML, or

Link a single style.css file with a few well-chosen rules.

Keep CSS minimal: typography, spacing, and colors are often enough to create a pleasant, readable page without turning it into a full design system.

## When a Framework Does Make Sense
There are many valid reasons to use Angular, React, or other tools:

Complex stateful interfaces, dashboards, or apps.

Real-time collaboration, heavy client-side logic, or large teams.

Codebases that genuinely benefit from component systems and build-time optimization.

This project doesn’t argue against frameworks; it argues against using them by default when a straightforward HTML page would do the job better.

## Extending the Idea
If you enjoy this approach, you can:

Build small documentation sites using only HTML and CSS.

Maintain project landing pages that never need a dependency upgrade.

Teach newcomers the fundamentals of the web before introducing tooling.

The goal is to keep publishing on the web accessible, durable, and understandable—just like it was in the early days of the internet.

## David Heinemeier Hansson (DHH)

### David Heinemeier Hansson (DHH) is a Danish programmer, writer, entrepreneur, and racing driver best known as the creator of the Ruby on Rails web framework and co-owner of the software company 37signals, makers of products like Basecamp and HEY.

### Early life and background
David Heinemeier Hansson was born on 15 October 1979 in Copenhagen, Denmark, and later studied business administration and computer science at Copenhagen Business School. He immigrated to the United States in 2005 and has since lived there with his wife Jamie and their three children.

### Ruby on Rails and software work
In 2003, Hansson created Ruby on Rails by extracting a web framework from the codebase of what became Basecamp, emphasizing programmer happiness and concise, expressive code. Ruby on Rails went on to power major applications and companies such as GitHub, Shopify, Airbnb, Square, Coinbase, and many others, helping to popularize Ruby for web development worldwide.

### 37signals, Basecamp, and HEY
Hansson is co-owner and chief technology officer of 37signals, the company behind Basecamp, HEY, and other web-based software products, which he runs together with Jason Fried. Since its beginnings in 1999, 37signals has been known for advocating a calm, “small is fine” approach to software businesses, focusing on sustainable work and simple, focused products.

### Writing and public voice
Together with Jason Fried, Hansson has co-authored several influential books, including “Rework,” “Remote: Office Not Required,” and “It Doesn’t Have to Be Crazy at Work,” which argue for unconventional approaches to work, management, and company culture. These books, including “Rework,” have reached bestseller lists such as the New York Times and have been translated widely, making their ideas about simple processes and calm companies accessible to a global audience.

### Racing and life outside code
Beyond software, Hansson has built a serious career as a racing driver, competing multiple times in the 24 Hours of Le Mans and other endurance series such as the FIA World Endurance Championship and IMSA. He has achieved notable results, including winning his class at Le Mans with Aston Martin in 2014 and standing on the overall podium with Rebellion Racing in 2017, balancing high-level motorsport with his work in technology and his family life.

### The “no build” and simplicity ethos
Hansson is also known for his outspoken views on software simplicity, arguing that much of the web has not fundamentally changed since the late 1990s and that many modern build tools add unnecessary complexity. His “no-build” stance rejects heavy frontend build pipelines in favor of straightforward, HTML-first, server-rendered applications, aligning with his broader belief that tools should serve clarity, speed, and developer happiness rather than fashion or hype.
