LAB 5 PORTFOLIO FILES

Keep index.html, projects.html, images/, and files/ together.
All images currently included are placeholders, so the pages work immediately.
Replace these files with your real images while keeping exactly the same filenames:
- images/profile.jpg — your portrait
- images/project-fixmyarea.png — FixMyArea screenshot
- images/project-medinear.png — MediNear screenshot
- images/project-ecommerce.png — Haroni Building e-commerce screenshot
- images/connect-banner.png — 600x200 banner; GitHub left, LinkedIn center, Email right
- images/favicon.png — 32x32 browser tab icon

Put your CV at files/cv.pdf for the existing download link to work.
The image-map clickable areas match the included connect-banner.png:
GitHub rectangle coords="20,40,180,160"
LinkedIn circle coords="300,100,70"
Email rectangle coords="420,40,580,160"
If you change the banner layout, update those coordinates in index.html too.

When finished:
git add index.html projects.html images/
git commit -m "Complete Lab 5: Images, image map, and favicon"
git push


LAB 6 — LISTS
This version builds on the uploaded Lab 5 commit and preserves its files and layout.
Lab 6 additions:
- index.html: nested unordered lists for grouped skills, an ordered learning roadmap, and a description list for tools.
- projects.html: an ordered “How I Built It” list and an unordered “Technologies Used” list for each project.

IMPORTANT:
The project-specific technology stacks were not specified in the Lab 5 files, so the Technologies Used lists contain reminders. Replace those reminder items with the technologies actually used in each project before submitting.

To commit the Lab 6 changes in your existing repository:
git add index.html projects.html README.txt
git commit -m "Complete Lab 6: HTML lists"
git push


Lab 6 technology-list update:
- Replaced the technology placeholders in projects.html with project stacks based on the available project repositories/source files.
- MediNear verified from its uploaded source ZIP: HTML, CSS, JavaScript; Node.js, Express.js, PostgreSQL via pg; bcrypt, jsonwebtoken, cors, dotenv; nodemon as a development dependency.
- FixMyArea and Haroni Building stack lists are based on the repository details previously reviewed. Review them against the current repository versions before final submission if those repositories have changed.
