# Portfolio Website Specification: Sheriff Alidu

## 1. Purpose
Show recruiters and hiring managers, in under 10 seconds, that I build and
validate quantitative models and ship working tools that people use.

## 2. Target audience
- Primary: recruiters and hiring managers for quantitative, risk and data
  science roles in New York.
- Secondary: collaborators and mentees in Ghana's tech community.
- They will mostly view the site on a laptop, but often first on a phone
  from a LinkedIn link.

## 3. Personal positioning
Quantitative analyst who builds credit risk models and the tools that monitor them.

One-line headline for the Home section:
"I build and validate credit risk models, and the tools that keep them honest."

## 4. Required sections (single page, in this order)
1. **Navigation bar**: my name on the left; links to About, Projects, Contact on the right.
2. **Home**: name, headline, two buttons: "View projects" (jumps to Projects)
   and "GitHub" (opens my GitHub).
3. **About**: 3 to 4 sentences on background and what I do.
4. **Projects**: 3 project cards.
5. **Contact**: email, LinkedIn, GitHub.
6. **Footer**: "© 2026 Sheriff Alidu".

## 5. Content

### About
I am a Quantitative Analyst at EY in New York, in Quantitative Advisory
Services. I build and validate credit risk models for large U.S. bank
portfolios, covering CECL, CCAR stress testing and SR 11-7 model validation.
I hold an M.S. in Statistics from Western Michigan University and a B.A. in
Mathematics and Statistics from the University of Ghana. I also enjoy
teaching statistics to non-technical audiences.

### Projects (each card: title, 2-line description, tools used, link)

**1. Model Performance Monitoring Platform**
- Description: A platform that tracks PD, EAD and LGD model performance and
  drift for banking clients. Covers 10 models across three banks and replaced
  several hours of manual checks.
- Tools: Python, React
- Link: none (internal work). Show "Internal project" instead of a link.

**2. JetBlue / Spirit Merger: Competitive Effects Analysis**
- Description: An analysis of how the proposed merger would affect
  competition on overlapping airline routes.
- Tools: Python
- Link: https://github.com/sheriff18/JetBlue-Spirit-Merger-Analysis

**3. CECL Benchmarking AI Agent**
- Description: An AI agent that helps analysts benchmark CECL credit loss
  forecasts.
- Tools: Microsoft Copilot Studio
- Link: none. Show "Internal project" instead of a link.

### Contact
- Email: sheriffalidu1@gmail.com
- LinkedIn: https://linkedin.com/in/sheriff-alidu
- GitHub: https://github.com/sheriff18

## 6. Functional requirements
- Single page. Navigation links scroll to the matching section.
- All external links (GitHub, LinkedIn, project repos) open in a new tab.
- Email link opens the visitor's email app (mailto).
- No backend, no contact form, no login, no database.
- Plain HTML and CSS only. No frameworks, no JavaScript unless needed for the
  mobile menu.
- Files: index.html, style.css, README.md, SPEC.md.

## 7. Design / UX
- Colours: white background (#FFFFFF), black text (#111111), one red accent
  (#BE141E) for links, buttons and section underlines.
- Font: a clean sans-serif (system font is fine).
- Plenty of white space; no more than 3 font sizes.
- Project cards in a row of 3 on laptop; stacked one per row on phone.
- Must be readable on a phone screen (375px wide) without zooming or
  scrolling sideways.
- No placeholder text or stock images. If content is missing, leave it out.

## 8. Must-haves (MVP)
- Navigation bar that works
- Home, About, Projects, Contact sections with real content
- All links working
- Readable on a phone
- Deployed on GitHub Pages with a live URL

## 9. Nice-to-haves (backlog, after MVP)
- Profile photo
- Downloadable resume (PDF)
- Dark mode
- Subtle animations on scroll
- Custom domain
- Blog / writing section

## 10. Definition of Done
- [ ] All must-haves built with real content
- [ ] Navigation and every link tested
- [ ] Checked on phone width
- [ ] Code on GitHub with clear commit messages
- [ ] Live URL works
- [ ] This SPEC.md saved in the repository
- [ ] AI work log: what I asked, what the AI assumed, what I changed
- [ ] Short reflection on what I learned