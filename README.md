# KKA-Portfolio
I am hereby declare that all the information provided in the portfolio is true.
🚀 Krishna Kumar Amatya — Personal Portfolio

A modern, animated, fully responsive personal portfolio website built with pure HTML, CSS, and vanilla JavaScript. Features 3D effects, particle animations, custom cursor, and scroll-reveal interactions.


📸 Overview
This is a single-file portfolio (krishna_portfolio.html) that showcases my skills, experience, projects, publications, and achievements as a Full Stack Software Engineer.

✨ Features
Visual & Animations

Particle Network Background — WebGL-style canvas with animated nodes and connecting lines
3D Tilt Cards — Mouse-responsive 3D perspective tilt on the About and Contact cards
Custom Dual-Ring Cursor — Smooth lagging ring cursor with hover scale effect (desktop only)
Scroll-Reveal Animations — Elements animate into view as you scroll
Skill Progress Bars — Animated fill on scroll using IntersectionObserver
Counter Animation — Stats numbers count up when they enter the viewport
Mouse Glow Effect — Radial glow that follows the cursor inside project cards
Shimmer Line — Animated scroll indicator in the hero section

Design

Dark Cyberpunk Aesthetic — Deep navy/black background with teal (#00f5d4) accent
Noise Texture Overlay — Subtle grain for depth
Typography — Syne (display), DM Mono (labels/code), Outfit (body)
CSS Custom Properties — Fully themeable via :root variables
Gradient Top Border — Teal-to-purple gradient reveal on project card hover

Layout & Sections

Sticky Navigation — Glassmorphism nav with underline link animations
Hero — Full-viewport intro with name, role, and CTAs
Stats Bar — 4-column animated counter grid
About — Two-column layout with tech stack pills
Skills — 6-card grid with categorized progress bars
Experience — Vertical timeline with glowing dots
Projects — 2-column masonry grid with a featured full-width card
Publications — Research card with journal info and DOI link
Achievements — 2-column badge cards
Contact — Split layout with contact links and a CTA card
Footer — Minimal credit line

Responsiveness

Fully responsive across desktop, tablet, and mobile
Nav links hidden on mobile; cursor disabled on touch devices
Grid columns collapse to single column on small screens
Fluid font sizing using clamp()


🗂️ File Structure
krishna_portfolio.html    # Single self-contained portfolio file
README.md                 # This file
No build tools, no dependencies, no npm — just open the HTML file in any browser.

🛠️ Tech Stack
LayerTechnologyMarkupHTML5StylingCSS3 (Custom Properties, Grid, Flexbox, Animations)ScriptingVanilla JavaScript (ES6+)CanvasHTML5 Canvas APIFontsGoogle Fonts (Syne, DM Mono, Outfit)

🚀 Getting Started
Option 1 — Open directly
bash# Just open the file in your browser
open krishna_portfolio.html
Option 2 — Serve locally
bash# Using Python
python -m http.server 8000

# Using Node.js (npx)
npx serve .
Then visit http://localhost:8000.
Option 3 — Deploy to GitHub Pages

Create a new repository on GitHub
Upload krishna_portfolio.html and rename it index.html
Go to Settings → Pages → Source → main branch
Your site will be live at https://yourusername.github.io/repo-name


✏️ Customization
Update Personal Links
Search for these placeholders in the HTML and replace with your real URLs:
html<!-- LinkedIn -->
href="https://linkedin.com/in/krishna-amatya"

<!-- GitHub -->
href="https://github.com/krishna-amatya"

<!-- Project links -->
href="#"  →  href="https://your-project-url.com"
Change Color Theme
Edit the CSS variables at the top of the <style> block:
css:root {
  --bg: #050810;           /* Page background */
  --surface: #0c1120;      /* Surface color */
  --card: #111827;         /* Card background */
  --accent1: #00f5d4;      /* Primary accent (teal) */
  --accent2: #7c3aed;      /* Secondary accent (purple) */
  --accent3: #f59e0b;      /* Tertiary accent (amber) */
  --text: #e8eaf6;         /* Primary text */
  --muted: #64748b;        /* Secondary/muted text */
}
Update Skill Bar Percentages
Find the data-w attributes on skill bar fill elements:
html<div class="skill-bar-fill" data-w="85"></div>
<!-- Change 85 to your proficiency level (0–100) -->
Add/Remove Projects
Copy a .project-card block inside .projects-grid and update the content. For a full-width featured project, add the featured class:
html<div class="project-card featured"> ... </div>
Adjust Particle Density
In the JavaScript section, change the particle count formula:
javascriptconst count = Math.floor(W * H / 18000);
// Lower number = more particles, Higher = fewer

📁 Sections Reference
#SectionID00Navigationnav01Hero#hero—Stats Bar#stats02About#about03Skills#skills04Experience#experience05Projects#projects06Publications#publications07Achievements#achievements08Contact#contact

📬 Contact
ChannelDetailsEmailmandalkrish47@gmail.comPhone+91-9368192701LinkedInlinkedin.com/in/krishna-amatyaGitHubgithub.com/krishna-amatyaLocationRoorkee, Uttarakhand, India

🏆 Highlights

🥇 1st Prize — University Tech Fest Coding Competition 2024 (50+ participants)
⚡ HackIndia 2025 — National Hackathon participant, built working prototype in 24 hours
📄 Published — AI-Based Early Cancer Screening Using Multi-Modal Data, IJSET 2026
🎓 BTech CSE — Quantum University, Roorkee (CGPA: 7.39/10)


📄 License
This portfolio is personal and open for reference. Feel free to use the code structure and design as inspiration for your own portfolio — just update the content with your own details.

Built with pure HTML, CSS & JavaScript — no frameworks needed.