# History Professional Teaching Portfolio

A responsive, single-page professional teaching portfolio for **History** by **BERIL OCHIENG**.

The portfolio focuses on **Evolution of Man** and presents:

- Teacher biography and teaching philosophy
- History syllabus information
- Schemes of work
- A lesson plan
- Teaching guide and lesson video
- Learner lesson notes
- A visual teaching aid
- Student performance information
- Records of work covered

## Live Website

Open `index.html` in a web browser, or host the project using GitHub Pages or any static web host.

## Portfolio Sections

The navigation is organized as follows:

1. **Cover Page** - Portfolio title and teacher details
2. **Home / Biography** - Professional profile and teaching philosophy
3. **Syllabus** - Learning outcomes, competencies, and values
4. **Schemes of Work** - Three-week teaching sequence
5. **Lesson Plan** - 40-minute lesson structure
6. **Lesson Video / Teaching Video** - Teaching guidance, textbook-style visual, and embedded YouTube lesson video
7. **Teaching Aid** - Printable evidence and adaptation sorting cards
8. **Teaching Notes / Lesson Notes** - Learner-friendly summary and questions
9. **Students' Performance** - Assessment evidence and Grade 10 record template
10. **Records of Work Covered** - Dated work and follow-up table

## Project Files

```text
.
|-- index.html
|-- beril-ochieng-profile.jpg
|-- evolution-teaching-guide.svg
`-- README.md
```

### File Descriptions

- `index.html` - Complete website, styling, navigation, and JavaScript
- `beril-ochieng-profile.jpg` - BERIL OCHIENG's profile photograph
- `evolution-teaching-guide.svg` - Textbook-style Evolution of Man teaching visual
- `README.md` - Project documentation

## Requirements

No build tools or package installation are required.

You only need:

- A modern web browser
- A text editor if you want to edit the portfolio
- Internet access when a lesson video link is added and used

## How to Run Locally

### Option 1: Open Directly

1. Download or clone this repository.
2. Open `index.html` in Google Chrome, Microsoft Edge, Firefox, or another modern browser.

### Option 2: Use a Local Server

Using VS Code:

1. Open the project folder in VS Code.
2. Install an extension such as **Live Server**.
3. Right-click `index.html`.
4. Select **Open with Live Server**.

Using Python, if it is installed:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

Using Node.js, if it is installed:

```bash
npx serve .
```

## Printing or Saving as PDF

1. Open `index.html` in a browser.
2. Press `Ctrl + P`.
3. Select **Save as PDF** or the preferred printer.
4. Use portrait or landscape layout according to the table content.

The portfolio includes print-specific CSS. Navigation, cover-only controls, and screen-only spacing are adjusted for printing.

## Features

- Modern indigo and slate glassmorphism navigation
- Sticky frosted navigation with a blurred, semi-transparent background
- Soft card shadows and rounded 16-pixel corners
- Responsive layout for desktops, tablets, and phones
- Horizontal navigation on smaller screens
- Accessible image descriptions
- Keyboard-visible focus styles
- Skip-to-content link
- Print-friendly layout
- Browser history support for portfolio page links
- Reduced-motion support
- Offline textbook-style teaching visual and printable sorting cards
- Embedded YouTube lesson video with a direct-link fallback
- Local SVG and JPG assets

## Customizing the Portfolio

All main content is in `index.html`.

To change the teacher details, profile, or school information, edit the text in the biography and cover sections.

To replace the profile photograph:

1. Add the new image to the project folder.
2. Update this line in `index.html`:

```html
<img class="profile-photo" src="beril-ochieng-profile.jpg" alt="Portrait photograph of BERIL OCHIENG">
```

Replace `beril-ochieng-profile.jpg` with the new file name and update the alt text.

The printable teaching aid is made from the four cards in the **Teaching Aid** section of `index.html`. Edit their headings and prompts there.

To replace the textbook-style visual in the **Lesson Video / Teaching Video** section:

```html
<img class="profile-photo" src="evolution-teaching-guide.svg" alt="Textbook-style diagram showing evidence, chronology, adaptation, and explanation">
```

The lesson video is embedded in the **Lesson Video / Teaching Video** section using a privacy-enhanced YouTube embed. To replace it, update the video ID in the iframe `src` and the direct YouTube URL in the fallback link.

The main modern colors are defined near the beginning of `index.html`:

```css
--bg-body: #f8fafc;
--bg-card: #ffffff;
--text-main: #1e293b;
--text-muted: #64748b;
--primary: #4f46e5;
--primary-hover: #4338ca;
--accent: #0ea5e9;
--nav-bg: rgba(255, 255, 255, 0.85);
--border-color: #e2e8f0;
--shadow-sm: 0 1px 3px rgba(15, 23, 42, 0.08);
--shadow-md: 0 10px 15px -3px rgba(15, 23, 42, 0.08);
--radius: 16px;
```

Update these values to change the website's visual theme.

## Deployment with GitHub Pages

1. Create or open the GitHub repository.
2. Upload `index.html`, `beril-ochieng-profile.jpg`, `evolution-teaching-guide.svg`, and `README.md`.
3. Open the repository **Settings**.
4. Select **Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Choose the main branch and the root folder.
7. Save the settings.
8. Wait for GitHub Pages to publish the site.

## Data and Privacy

Before publishing the portfolio publicly:

- Obtain permission before sharing student names or photographs.
- Remove admission numbers if they are not required.
- Replace real learner records with anonymized or approved data.
- Follow the school's data-protection and safeguarding procedures.
- Do not include sensitive personal or medical information.

The performance section is a template awaiting verified Grade 10 results. Add only accurate, approved information before external use.

## Recommended Before Submission

- Replace placeholder dates in the Records of Work Covered section.
- Confirm the class, term, school (Chepterit Girls), and curriculum edition.
- Verify all historical facts and dates against the approved class textbook.
- Confirm the learner marks and grades with the official school records.
- Replace or anonymize learner names and admission numbers where required.
- Test the portfolio on a phone and desktop computer.
- Test the embedded lesson video and direct YouTube link; provide an alternative for learners without internet access.
- Print one copy and check that tables and long text fit correctly.

## Browser and Accessibility Testing

Test the page in at least:

- Microsoft Edge
- Google Chrome
- Mobile browser view

Check that:

- All navigation links open the correct page
- Images have meaningful alternative text
- The lesson video and its direct YouTube fallback link work
- Text remains readable at 200% zoom
- The print layout does not cut off important content

## Technology

- HTML5
- CSS3
- JavaScript
- Responsive design
- SVG graphics
- Embedded YouTube lesson video

No database or server-side software is used.
