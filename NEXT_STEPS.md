# Next Steps for CHGMF Website - Design 5 Implementation

## ✅ Completed
- Main index.html now redirects to design5/index.html
- Design5/index.html navigation links enabled
- Hero buttons now link to design5 pages

## 📋 Remaining Tasks

### 1. Create Design 5 Pages CSS
Create `/css/design5-pages.css` based on design1-pages.css with Design 5 styling:
- Classic charity color scheme (forest green #2D5016, gold #B8860B)
- Traditional centered layouts
- Merriweather/Lato font family
- Same page structures as Design 1

### 2. Create Design 5 Pages (copy from Design 1 and adapt):

#### About Page (`design5/about.html`)
- Page hero with "About Us" title
- What We Do section (3 cards)
- Our Story section
- Our Team section

#### Programs Page (`design5/programs.html`)
- Disaster Relief
- Service Learning Opportunities
- Health Facility Sponsorship
- Health Education Scholarship
- Community Development

#### Events Page (`design5/events.html`)
- Upcoming events grid
- Past events section

#### Ways to Give Page (`design5/ways-to-give.html`)
- One-time donation
- Monthly giving
- Volunteer opportunities
- Corporate partnerships

#### Testimonials Page (`design5/testimonials.html`)
- Testimonials grid with quotes and photos

#### Contact Page (`design5/contact.html`)
- Contact form
- Office information
- Map

### 3. Update Footer Links
Update footer navigation in all design5 pages to link correctly within design5 folder

### 4. Test & Deploy
- Test all links
- Verify responsive design
- Commit and push to GitHub
- GitHub Pages will automatically update

## Quick Command to Create All Pages
You can copy design1 pages to design5 and do find/replace:
1. Copy all HTML files from design1/ to design5/
2. Find: `../css/design1` Replace with: `../css/design5`
3. Find: `Design 1` Replace with: `Design 5 (Traditional Charity)`
4. Update all internal links to remove `design1/` prefix

Then create the CSS file and you're done!
