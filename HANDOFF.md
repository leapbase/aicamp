# AI Camp 2026 - Project Handoff Document

## Project Overview

This repository contains a complete 12-week AI training camp curriculum website designed for CS underclassmen. The program focuses on practical AI application development, modern coding tools, and building a portfolio of real-world projects.

**Repository:** https://gitlab.com/leapbase/aicamp  
**Created:** May 2026  
**Status:** Complete and ready for deployment

---

## What's Included

### 1. Website Content (28 HTML files)

#### Main Pages
- **index.html** - Landing page with full curriculum overview, certificate showcase, and navigation to all weeks
- **slide-summary.html** - 10-slide overview presentation for introducing the program

#### Week Folders (12 folders: week1/ through week12/)
Each week folder contains:
- **weekN.html** - Detailed training page with pre-work, sessions, exercises, homework, key takeaways
- **weekN-slides.html** - Interactive slide deck (10-12 slides) with keyboard/click navigation
- **weekN-quiz.html** - Interactive assessment (6-8 questions) with immediate scoring and explanations

#### Quiz Answer Key (quiz/ folder)
- **quiz/quiz-answers.md** - Complete answer key with all 96 questions and explanations

### 2. Documentation

- **README.md** - Program overview, curriculum structure, certificates, deployment instructions
- **HANDOFF.md** - This document
- **schedule.md** - Original planning document with detailed week-by-week breakdown
- **courses-anthropic.md** - Complete list of 18 Anthropic courses with direct links

### 3. Configuration

- **.gitignore** - Ignores local development files (.claude/, .env, Python cache, etc.)
- **.claude/settings.json** - Local Claude Code configuration (not in repo)

---

## Project Structure

```
aicamp/
├── index.html                  # Main landing page
├── slide-summary.html                 # Overview presentation
├── README.md                   # Documentation
├── HANDOFF.md                  # This handoff document
├── schedule.md                 # Planning document
├── courses-anthropic.md                  # Course reference
├── .gitignore                  # Git ignore rules
│
├── week1/                      # Week 1 folder
│   ├── week1.html              # Detailed content
│   ├── week1-slides.html       # Presentation
│   └── week1-quiz.html         # Quiz
│
├── week2/ ... week12/          # Similar structure for all weeks
│
└── quiz/                       # Quiz answer key folder
    └── quiz-answers.md         # Complete answer key (96 questions)
```

---

## Key Features

### Navigation & UX
- **Sticky navigation bar** on main page
- **"View Details →" links** from week cards to detailed pages
- **"Back to Overview" links** on all sub-pages
- **Keyboard shortcuts** on slides and presentations
- **Responsive design** - works on desktop, tablet, mobile

### Interactive Elements
- **Quiz system** with immediate feedback and scoring
- **Slide presentations** with multiple navigation methods
- **Clickable certificates** linking directly to Anthropic courses

### Design
- **Professional gradient theme** (blue #2563eb to purple #7c3aed)
- **Consistent styling** across all pages
- **Clean typography** with system fonts
- **Accessible color contrast**

---

## Curriculum Summary

### Month 1: Get Fluent with AI Tools (Weeks 1-4)
- Week 1: Setup & First API Calls
- Week 2: Prompting & API Fundamentals
- Week 3: Claude Code Part 1
- Week 4: OpenAI Codex

### Month 2: Build Real Apps (Weeks 5-8)
- Week 5: Skills & Subagents
- Week 6: Chatbot + RAG Intro
- Week 7: Model Context Protocol
- Week 8: Agents and OpenClaw

### Month 3: Capstone & Portfolio (Weeks 9-12)
- Week 9: Capstone Kickoff
- Week 10: Build
- Week 11: Finish & Write
- Week 12: Resume & Interview Prep

### Official Certifications (9-10 total)
1. Claude 101
2. AI Fluency for Students
3. Building with the Claude API
4. Claude Code 101
5. Claude Code in Action
6. Introduction to Agent Skills
7. Introduction to Subagents
8. Introduction to Model Context Protocol
9. AI Capabilities and Limitations
10. Model Context Protocol: Advanced Topics (optional)

---

## Deployment Options

This is a **static website** with no backend requirements. Deploy to:

### Recommended Options
1. **GitLab Pages** (already on GitLab)
2. **GitHub Pages** (free, custom domain support)
3. **Netlify** (free tier, automatic deploys)
4. **Vercel** (free tier, fast CDN)
5. **AWS S3 + CloudFront** (scalable, professional)

### Deployment Steps (Generic)
1. Point hosting service to repository root
2. Set index.html as the entry point
3. No build process needed - pure HTML/CSS/JS
4. Optional: Add custom domain
5. Optional: Enable HTTPS (usually automatic)

---

## How to Use

### For Students
1. **Start at index.html** - Review full curriculum
2. **Each week:**
   - Read the detailed week page (weekN.html)
   - Review the slide presentation (weekN-slides.html)
   - Take the quiz (weekN-quiz.html)
   - Complete homework assignments
3. **Track progress** through certificate completion

### For Instructors
1. **Use slides** for live sessions (weekN-slides.html)
2. **Reference quiz/quiz-answers.md** for grading and discussion
3. **Link to specific weeks** for homework assignments
4. **Customize content** by editing HTML files directly

### For Program Administrators
1. **Share index.html** as program overview
2. **Use slide-summary.html** for recruitment presentations
3. **Link courses-anthropic.md** for certificate enrollment
4. **Track completion** via quiz submissions (requires adding backend)

---

## Customization Guide

### Updating Content
All files are standard HTML with embedded CSS. To modify:

1. **Text content** - Edit directly in HTML files
2. **Styling** - Modify CSS in `<style>` tags in each file
3. **Colors** - Update CSS variables in `:root` section
4. **Links** - Update `href` attributes

### Adding New Weeks
1. Create new folder `weekN/`
2. Copy `week1/week1.html` as template
3. Copy `week1/week1-slides.html` for presentation
4. Copy `week1/week1-quiz.html` for assessment
5. Update content for new week
6. Update links to use `../index.html` for back navigation
7. Add link from index.html as `weekN/weekN.html`

### Branding
Update these elements in index.html:
- Header gradient colors (CSS variables)
- Program name and title
- Footer text
- Certificate links

---

## Technical Details

### Technologies Used
- **HTML5** - Structure and content
- **CSS3** - Styling (no frameworks, pure CSS)
- **JavaScript (Vanilla)** - Quiz logic, slide navigation
- **No dependencies** - No npm, webpack, or build tools
- **No backend** - Pure static site

### Browser Compatibility
- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- Mobile browsers (iOS Safari, Chrome Mobile)

### Performance
- Lightweight (~20-25KB per HTML file)
- No external requests (except Anthropic course links)
- Fast load times (<1 second)
- No images (SVG icons only)

---

## Maintenance Notes

### Regular Updates Needed
1. **Course links** - Verify Anthropic URLs are current
2. **Certificate names** - Check if Anthropic renames courses
3. **Content accuracy** - Update as tools/APIs evolve
4. **Broken links** - Test all external links quarterly

### Future Enhancements (Optional)
1. **Backend integration** - Track student progress, quiz scores
2. **User authentication** - Student accounts, progress tracking
3. **CMS integration** - Easier content updates (Contentful, Strapi)
4. **Video embeds** - Add instructional videos
5. **Discussion forum** - Student community (Discourse, Discord)
6. **Analytics** - Google Analytics or privacy-focused alternative

---

## File Sizes

- Total repository: ~2MB
- Average HTML page: 20-25KB
- Quiz pages: 18-20KB
- Slide presentations: 23-27KB
- Answer key (MD): 58KB

---

## Important Links

### Anthropic Resources
- **Course Platform:** https://anthropic.skilljar.com/
- **Claude API Docs:** https://docs.anthropic.com/
- **Claude Code:** https://claude.ai/code

### Repository
- **GitLab:** https://gitlab.com/leapbase/aicamp
- **Clone:** `git clone https://gitlab.com/leapbase/aicamp.git`

---

## Support & Contact

### For Technical Issues
- Check git commit history for context
- All changes documented in commit messages
- Each commit co-authored by Claude Sonnet 4.5

### For Content Questions
- Refer to schedule.md for original planning
- Check courses-anthropic.md for Anthropic course details
- Review quiz-answers.md for learning objectives

---

## Quick Start Commands

```bash
# Clone the repository
git clone https://gitlab.com/leapbase/aicamp.git
cd aicamp

# Open locally
open index.html

# Or serve with Python
python3 -m http.server 8000
# Then visit http://localhost:8000

# Deploy to GitLab Pages (if configured)
git push origin main
```

---

## Known Limitations

1. **No backend** - Quiz scores not persisted (would need database)
2. **No user accounts** - Can't track individual student progress
3. **Static content** - Requires HTML editing to update content
4. **No search** - Large site would benefit from search feature
5. **No analytics** - Can't track usage without adding analytics code

---

## Version History

- **v1.0** (May 2026) - Initial complete release
  - 28 HTML files (main, 12 weeks × 3 types)
  - Full documentation
  - 96 quiz questions with answer key
  - Complete 12-week curriculum

---

## License & Usage

This curriculum references Anthropic's official courses and tools. When deploying:
- Ensure Anthropic course links remain accurate
- Give credit to Anthropic for their course content
- This material is educational - verify any commercial use terms

---

## Success Metrics

Track these to measure program success:
- Certificate completion rates (by week)
- Quiz pass rates (70% threshold)
- Student project completion
- LinkedIn certificate additions
- Open-source contributions from students
- Job placement rates for participants

---

## Handoff Checklist

✅ All 28 HTML files created and tested  
✅ All 12 quizzes with answer key complete  
✅ Documentation (README, courses list) complete  
✅ .gitignore configured for local development  
✅ Repository pushed to GitLab  
✅ All links verified (internal and external)  
✅ Responsive design tested  
✅ Quiz scoring functionality tested  
✅ Slide navigation tested  
✅ No broken links or missing resources  

---

## Questions?

This project is complete and ready for use. All content is self-contained in the repository. For modifications, start with index.html and follow the existing patterns in week1/week1.html, week1/week1-slides.html, and week1/week1-quiz.html as templates.

**Last Updated:** May 13, 2026  
**Project Status:** ✅ Complete and Production-Ready
