ANASWARA KC PORTFOLIO WEBSITE

This is a simple static website. You can edit it without needing Next.js.

FILES
- index.html: all website text, sections, services, journey, contact links and project cards.
- styles.css: colours, fonts, layout and responsive design.
- script.js: small mobile navigation behaviour.
- assets/: add your profile photo and project screenshots here.

ADD YOUR PHOTO
1. Put your photo inside assets/ and name it profile.jpg
2. The website will automatically display it in the home section.

ADD PROJECT SCREENSHOTS
1. Put images in assets/projects/ or assets/posters/.
2. Open index.html and find the relevant project card in the My Work section.
3. Replace the <div class="work-placeholder">...</div> with:
   <div class="work-placeholder"><img src="assets/projects/your-image.jpg" alt="Short description"></div>
4. Save and upload the changed files to GitHub.

UPDATE YOUR CONTACT DETAILS
Open index.html and search for:
- YOUR_EMAIL@example.com
- +91 XXXXX XXXXX
- YOUR-LINKEDIN
- YOUR-INSTAGRAM
Replace these with your real details. Update both the visible text and the href value.

CHANGE TEXT
Open index.html and edit the text inside the relevant section. Keep the HTML tags in place.

DEPLOY WITH VERCEL
1. Upload the CONTENTS of this folder to the root of your new GitHub repository.
   Important: index.html must appear at the top level of the repository, not inside another folder.
2. In Vercel, choose Add New > Project and import this GitHub repository.
3. Framework Preset: Other. Build Command: leave empty. Output Directory: leave empty or set to . if required.
4. Deploy. Later GitHub commits automatically trigger a new deployment.

Before publishing, replace contact placeholders and add only genuine work samples. Hide confidential client information in screenshots.
