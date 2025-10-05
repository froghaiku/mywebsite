# Cover Letter Website Template

This template is designed to create personalized, company-specific cover letter websites that match your vacation page theme.

## 🎯 Quick Start: Creating a New Company Page

### Option 1: Copy the entire template folder

```bash
# From your website root directory
cp -r template/ airtable/
# or
cp -r template/ circle/
# or any company name
```

### Option 2: Just copy the HTML file

```bash
# Create the company directory
mkdir airtable
# Copy the template
cp template/index.html airtable/index.html
```

The page will be accessible at: `benschoeffler.com/airtable` (or whatever company name you use)

## ✏️ Customization Checklist

When creating a new company-specific page, search for `<!-- EDITABLE:` comments in the HTML and update these sections:

### 1. **Page Title** (in `<head>`)
- [ ] Update: `<title>Ben Schoeffler - Application for [ROLE NAME]</title>`

### 2. **Hero Section** (top of page)
- [ ] Greeting: `Hello [Hiring Manager Name]!`
- [ ] Hero statement: Customize the value proposition
- [ ] Role info: `Applying for: [POSITION TITLE] at [COMPANY NAME]`
- [ ] Video: Replace `YOUR_VIDEO_ID` with actual YouTube video ID

### 3. **"Why I'm the Perfect Fit" Cards** (5 cards total)
Each card has two columns:

**LEFT COLUMN (What You Need):**
- [ ] Paste the requirement from the job description
- [ ] Make it specific to what they're asking for

**RIGHT COLUMN (What I've Done):**
- [ ] Keep existing achievement OR replace with more relevant one from resume
- [ ] Adjust bullet points to match job requirements

**Template for each card:**
```html
<div class="fit-card">
    <div class="fit-grid">
        <div class="fit-requirement">
            <h3>What You Need</h3>
            <p><strong>[PASTE JOB REQUIREMENT TITLE]</strong></p>
            <p>[PASTE JOB REQUIREMENT DESCRIPTION]</p>
        </div>
        <div class="fit-achievement">
            <h3>What I've Done</h3>
            <p><strong>[YOUR MATCHING ACHIEVEMENT]</strong></p>
            <ul>
                <li>[Supporting detail 1]</li>
                <li>[Supporting detail 2]</li>
                <li>[Supporting detail 3]</li>
            </ul>
        </div>
    </div>
</div>
```

### 4. **Footer**
- [ ] Update: `Created with care for [COMPANY NAME]`

## 📋 Your Resume Highlights (Reference)

Use these achievements when customizing the "What I've Done" sections:

### AI & Automation
- Spearheaded AI integration that saved 400+ hours monthly
- Automatically resolved 2,000+ tickets per month
- Led complete AI implementation strategy

### Team Scaling & Leadership
- Scaled team by 300% (50+ people)
- Reduced response time from 72 hours to under 5 minutes
- Managed 400+ page knowledge base
- Increased customer happiness by 15%+

### Customer Success
- Resolved 14,000+ customer issues total
- 2,000+ tickets at Circle with high satisfaction
- Consistently top 5 performer out of 30+ agents
- Specialized in complex billing & deliverability

### Strategic Operations
- Support Operations Lead at $40M SaaS company
- Developed department strategy
- Launched Guru knowledge base
- Vetted BPO partnerships

### Technical Skills
- Built & sold website with thousands of daily visitors
- Developing iOS app with AI prompt engineering
- Zapier, Notion, copywriting, email marketing expert

### Unique Background
- 5 years coaching practice (anxiety & sports performance)
- Podcast with 500,000 downloads
- Deep empathy combined with technical skills

## 🎬 YouTube Video Setup

1. Upload your personalized video message to YouTube
2. Get the video ID from the URL:
   - URL: `https://www.youtube.com/watch?v=dQw4w9WgXcQ`
   - Video ID: `dQw4w9WgXcQ`
3. Replace `YOUR_VIDEO_ID` in the iframe src

**Video Best Practices:**
- Keep it 60-90 seconds
- Mention the company name and position
- Be authentic and enthusiastic
- Good lighting and clear audio
- Professional but personable

## 📱 Mobile Responsive

The template is fully mobile responsive and will automatically adjust for smaller screens:
- Comparison cards stack vertically on mobile
- Navigation collapses for easy viewing
- All sections remain readable and engaging

## 🎨 Styling Notes

The template uses your existing `/assets/css/main.css` file, so all styling is consistent with your vacation page:
- Same color scheme (accent color: #dd6245)
- Same fonts (Inter & Dancing Script)
- Same card shadows and hover effects
- Same responsive breakpoints

## 📁 Recommended Workflow

1. Copy the template folder with company name
2. Open the HTML file in your editor
3. Search for `<!-- EDITABLE:` and update each section
4. Paste job requirements from the job description
5. Match each requirement with your relevant achievements
6. Record and upload your personalized video
7. Update the video ID
8. Test the page locally
9. Deploy to your website

## 🔗 File Structure

```
MyWebsite/
├── template/           # Original template (don't edit)
│   ├── index.html
│   └── README.md
├── airtable/          # Example company page
│   └── index.html
├── circle/            # Example company page
│   └── index.html
├── assets/
│   └── css/
│       └── main.css   # Shared styles
└── vacation/          # Your vacation page (reference)
    └── index.html
```

## 💡 Tips

- **Keep the template clean**: Don't edit `/template/index.html` after initial setup. Always copy it first.
- **Customize strategically**: Focus on the 5 comparison cards—these are your strongest selling points.
- **Be specific**: Use numbers and concrete examples from your resume.
- **Match their language**: Use terms and phrases from the job description.
- **Update the video**: Record a new 60-second video for each serious application.
- **Test before sending**: Always check the page on mobile and desktop before sharing.

## ✅ Pre-Send Checklist

Before sending your personalized page to a hiring manager:

- [ ] All `[PLACEHOLDERS]` are replaced with actual content
- [ ] Video is uploaded and working
- [ ] Company name appears in multiple places
- [ ] Job requirements match actual job description
- [ ] Your achievements are relevant to each requirement
- [ ] Contact information is correct
- [ ] Page looks good on mobile
- [ ] All links work (especially LinkedIn)
- [ ] Footer has company name

---

**Questions or need help?** Just ping me and I can help customize a page for a specific application!
