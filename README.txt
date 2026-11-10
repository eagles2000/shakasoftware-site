ShakaSoftware.com redesign (static site)

What's in this folder
  index.html    The whole website (styles and scripts are inside it)
  img/          Logo, hero photo, and app screenshots
  vercel.json   Sends old links like /apps to the new Workshop section

How to put it live (same way as askaihawaii.com)
  1. On github.com, create a new repository named shakasoftware-site.
  2. Click "uploading an existing file" and drag in index.html, vercel.json, and the img folder. Commit.
  3. On vercel.com: Add New > Project > import shakasoftware-site > Deploy (no settings to change).
  4. In the new project: Settings > Domains > add shakasoftware.com and www.shakasoftware.com.
     Vercel will move the domain from the old project to this one.
  5. When the new site looks right, you can delete or pause the old Vercel project.

Contact form
  The form opens the visitor's email app with their message filled in, addressed to
  shakasoftware1@gmail.com. No server or monthly cost needed.
