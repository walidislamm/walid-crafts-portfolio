WALID CRAFTS — PORTFOLIO

HOW TO ADD A THUMBNAIL PROJECT
1. Put your image inside the "projects" folder.
2. Open "projects.js".
3. Add a project object like this:

{
  image: "projects/my-thumbnail.jpg",
  title: "My YouTube Thumbnail",
  category: "YouTube Thumbnail",
  description: "Concept + design for a creator."
},

4. Save and redeploy the folder to Vercel.

SUPPORTED IMAGE TYPES:
.jpg / .jpeg / .png / .webp

IMPORTANT:
Static Vercel websites cannot automatically read the contents of a folder for security reasons.
This setup makes adding projects extremely simple while keeping the site fast and fully static.
