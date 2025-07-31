# Personalization Guide for Your Portfolio Website

## 🎯 Quick Start Checklist

### 1. Homepage Personalization (`src/pages/index.astro`)
Replace the placeholder text in the hero section:

```astro
<div class="text-3xl py-3 font-bold">[Your Title/Role Here]</div>
```
**Examples:**
- "Software Engineer"
- "Full Stack Developer"
- "Data Scientist"
- "Product Manager"
- "UX Designer"

```astro
[Your brief bio here - describe what you do, your passion, and what makes you unique. 
This should be 2-3 sentences that give visitors a quick overview of who you are and what you do.]
```
**Example:**
"I'm a passionate software engineer with 5+ years of experience building scalable web applications. I specialize in React, Node.js, and cloud technologies, and love creating solutions that make a real impact on users' lives."

### 2. Social Links
Update these URLs in `src/pages/index.astro`:
- `[Your LinkedIn URL]` → Your LinkedIn profile
- `[Your GitHub URL]` → Your GitHub profile

### 3. Featured Projects
Replace the project placeholders with your actual projects:

**For each project, provide:**
- **Title**: Project name
- **Description**: What it does, technologies used, key achievements
- **URL**: Link to live demo or GitHub repository
- **Image**: Replace `/post_img.webp` with your project screenshot

### 4. CV Page Personalization (`src/pages/cv.astro`)

#### Professional Summary
Replace the placeholder with 2-3 paragraphs about your career journey.

#### Education Section
Update the `TimeLineElement` components with your education:

```astro
<TimeLineElement
  title="[Your Degree]"
  subtitle="[Start Year] to [End Year] at [University Name], [City], [Country]"
/>
```

#### Experience Section
Update each `TimeLineElement` with your work experience:

```astro
<TimeLineElement
  title="[Job Title] at [Company Name]"
  subtitle="From [Start Date] to [End Date] at [Company], [City], [Country]"
>
  [Detailed description of your role, achievements, technologies used, and impact]
</TimeLineElement>
```

#### Certifications
Replace the placeholder links with your actual certifications:

```astro
<li>
  <a href="[Certification URL]" target="_blank">[Certification Name]</a>
</li>
```

#### Skills
Replace the placeholder skills with your actual technical skills:

```astro
<li>JavaScript</li>
<li>React</li>
<li>Node.js</li>
<li>Python</li>
<li>AWS</li>
<!-- Add all your skills here -->
```

## 📝 Data Collection Template

### Personal Information
- **Name**: Alexandru Coca ✅ (already set)
- **Title/Role**: [Fill in]
- **Location**: [City, Country]
- **Email**: [Your email]
- **LinkedIn**: [Your LinkedIn URL]
- **GitHub**: [Your GitHub URL]
- **Portfolio**: [Your portfolio URL if different]

### Professional Summary
Write 2-3 paragraphs about:
- Your career journey
- Key achievements
- What drives you professionally
- Your unique value proposition

### Education
For each degree/certification:
- Degree/Title
- Institution
- Years attended
- Location
- GPA (if relevant)
- Relevant coursework

### Work Experience
For each position:
- Job title
- Company name
- Duration (start - end date)
- Location
- Key responsibilities
- Achievements and impact
- Technologies used
- Projects worked on

### Skills
Organize by categories:
- **Programming Languages**: JavaScript, Python, Java, etc.
- **Frameworks & Libraries**: React, Node.js, Django, etc.
- **Databases**: PostgreSQL, MongoDB, Redis, etc.
- **Cloud & DevOps**: AWS, Docker, Kubernetes, etc.
- **Tools**: Git, VS Code, Figma, etc.
- **Soft Skills**: Leadership, Communication, Problem-solving, etc.

### Projects
For each featured project:
- Project name
- Brief description
- Technologies used
- Key features
- Live demo URL
- GitHub repository URL
- Screenshot/image

### Certifications
- Certification name
- Issuing organization
- Date obtained
- Credential URL (if available)

## 🚀 Next Steps

1. **Collect your data** using the template above
2. **Update the files** with your information
3. **Add project images** to the `public/` folder
4. **Test locally** with `pnpm dev`
5. **Deploy** by pushing to GitHub

## 💡 Tips for Great Content

- **Be specific**: Use numbers and metrics when possible
- **Show impact**: Focus on what you achieved, not just what you did
- **Keep it current**: Update regularly with new projects and experience
- **Be authentic**: Let your personality shine through
- **Proofread**: Ensure everything is error-free

## 📁 File Structure to Update

- `src/pages/index.astro` - Homepage content
- `src/pages/cv.astro` - CV/resume content
- `src/components/Header.astro` - Navigation (already updated)
- `src/config.ts` - Site metadata (already updated)
- `public/` - Add your project images here

Need help with any specific section? Just ask! 