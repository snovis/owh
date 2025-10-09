# OWH Website Project Memory

## Project Overview
This is a static website for Chris Roth's missionary work with Outreach for World Hope (OWH), a Christian non-profit organization serving remote mountain villages in Eastern Guatemala. The website helps people learn more about the mission trips and get involved.

## Project Purpose
- Provide information about OWH missionary trips to Guatemala
- Make it easy for people to get involved (sponsorship, donations, mission trips)
- Share stories of hope and transformation
- Demonstrate transparency and good stewardship

## Key Project Details

### Repository Structure
- **Location**: `~/dev/owh`
- **Main Files**:
  - `docs/index.html` - Current live homepage (previously owh_index.html)
  - `docs/index.html.bak` - Archived original homepage
  - `docs/img/` - Image assets (logo, QR codes)
  - `src/owh_homepage_revised.md` - Markdown source content
  - `README.md` - Project documentation with form and donation links

### Website Content Sections
1. **Header** - Logo, title, tagline
2. **About Our Mission** - Organization overview and vision
3. **Bible Verse** (1 John 3:17-18) - Sets compassionate tone
4. **The Need** - Describes challenges in Guatemala
5. **Bible Verse** (Matthew 25:40) - Service to the vulnerable
6. **Stories of Hope** - Testimonials with Miguel's before/after photos (Miguel, Mauricia, Darwin)
7. **Bible Verse** (James 1:27) - Pure religion is caring for orphans and widows
8. **Our Programs** - Six key programs (Child Sponsorship, Medical Care, Clean Water, Safe Stoves, Education, Agriculture) with program photos
9. **Bible Verse** (Galatians 6:9) - Perseverance in doing good
10. **The Lasting Impact** - Describing village gatherings and ripple effects of programs (with village photo)
11. **How You Can Help** - Three CTAs with buttons and QR codes
12. **Our Commitment to You** - Transparency section (91% to programs)
13. **Bible Verse** (Proverbs 22:9) - Blessings of generosity
14. **Thank You** - Closing gratitude
15. **Footer** - Copyright only

### Important Links & Resources
- **Google Form** (Sponsorship/Get Involved): https://docs.google.com/forms/d/e/1FAIpQLSei6Ld_95q41lMpgXjnfqjtNrKpswKMm-jZrsOCkYqnplZtOA/viewform?usp=sharing
- **Donation Page**: https://www.outreachforworldhope.org/donate
- **GitHub Repository**: https://github.com/snovis/owh.git

### Call-to-Action Buttons
1. **Sponsor a Child** ($34/month) → Links to Google Form
2. **Donate Now** → Links to https://www.outreachforworldhope.org/donate
3. **Learn More** (Mission Trips) → Links to Google Form

### Image Assets
- `img/OWH logo.avif` - Organization logo (200px max-width, in header)
- `img/Blue-OWH-Getinvolved.png` - QR code for sponsorship and mission trips
- `img/Green-bit.ly_owh-donate.png` - QR code for donations
- `img/miguel_before.avif` - Miguel before care: severe malnutrition (in Stories of Hope section)
- `img/miguel_after.avif` - Miguel after 6 weeks: healthy, walking (in Stories of Hope section)
- `img/OWH-Sponsor-Child.jpeg` - Child sponsorship program photo (in Child Sponsorship section)
- `img/OWH-Bucket-Mountain-Boy.jpeg` - Bucket water filter program photo (in Clean Water Initiative section)
- `img/OWH-Stove-Family.jpeg` - Safe stove program photo (in Safe Stove Program section)
- `img/OWH-Village.jpeg` - Village gathering photo (in Lasting Impact section)
- `img/OWH-Bucket-Blue-Boy.jpeg` - Additional water filter photo (not currently used)
- `img/OWH-Bucket-Family.jpeg` - Additional water filter photo (not currently used)
- `img/OWH-Stove-Alt.jpeg` - Alternative stove photo (not currently used)

### Design Elements
- **Color Scheme**: Purple gradient header (#667eea to #764ba2), color-coded sections
- **Typography**: System fonts, clean and modern
- **Layout**: Responsive, mobile-friendly (max-width: 900px)
- **Special Styling**:
  - Scripture quotes: Italic with left border, elegant epigraph style
  - Story quotes: White boxes with purple left border
  - Sections: Color-coded backgrounds (yellow/highlight, red/need, blue/programs, green/stories, light blue/help)
  - CTA boxes: White with shadow, prominent buttons
  - Program images: Centered, max 500px wide × 400px tall, rounded corners (8px), drop shadow, crop from top center
  - Before/after images: Side-by-side flexbox layout, color-coded labels (red=before, green=after), responsive to stack on mobile

### Key Statistics
- **Donation Efficiency**: 91% of donations go directly to program support
- **Organization Type**: 501(c)(3) non-profit
- **Child Sponsorship Cost**: $34/month
- **Water Filter Cost**: $20 (provides 100,000 gallons)
- **Vented Stove Cost**: $150

### Bible Verses Used
1. **1 John 3:17-18** - Between Mission and Need (compassion in deed)
2. **Matthew 25:40** - After Need (serving "the least of these")
3. **James 1:27** - After Stories of Hope (pure religion is caring for orphans)
4. **Galatians 6:9** - After Programs (perseverance in doing good)
5. **Proverbs 22:9** - Before Thank You (blessings of generosity)

### Development History
- Started with basic markdown content in `inbox/owh_homepage.md`
- Created improved version with enhanced structure, programs section, testimonials
- Converted to HTML with professional styling and responsive design
- Added QR codes for easy mobile access
- Integrated logo and Bible verses for spiritual emphasis
- Replaced original index.html with improved version
- **2025-10-05**: Added program photos to website
  - Added OWH-Sponsor-Child.jpeg to Child Sponsorship section
  - Added OWH-Bucket-Mountain-Boy.jpeg to Clean Water Initiative section
  - Added OWH-Stove-Family.jpeg to Safe Stove Program section
  - Created new "Lasting Impact" section with OWH-Village.jpeg showing community gatherings
  - Styled images with centered alignment, uniform sizing, rounded corners, and drop shadows
- **2025-10-09**: Added Miguel's before/after story (feature/beforeafter branch → main)
  - Added Miguel's powerful transformation story with medical background
  - Created before/after photo comparison showing dramatic 6-week transformation
  - Repositioned Stories of Hope section earlier in page (after The Need, before Our Programs)
  - Added James 1:27 scripture between Stories and Programs
  - Implemented responsive before/after image styling with color-coded labels
  - Demonstrates OWH's core mission to protect vulnerable children from preventable starvation

### Technical Notes
- Uses AVIF format for logo (modern, efficient)
- All external links open in new tabs (`target="_blank"`)
- QR codes sized at 200px max-width for optimal scanning
- Mobile-responsive breakpoints at 768px
- Clean semantic HTML5 structure

### Maintenance
- Git repository on GitHub (https://github.com/snovis/owh.git)
- All changes committed with descriptive messages
- Co-authored commits with Claude Code attribution

## Future Considerations
- May want to add actual contact information in footer
- Consider adding photo gallery from mission trips
- Potential for video testimonials
- Newsletter signup integration
- Social media integration (mentioned in original placeholder)

## User Context
- User is Scott Novis, helping friend Chris Roth with this project
- Chris leads missionary trips to Guatemala through OWH
- Kim Tewes is the head of OWH - her #1 mission is to protect the little ones
- Website purpose: Make it easier for people to learn about and get involved in the mission work
- User appreciates clean, professional design with spiritual emphasis
- User uses feature branch workflow to safely test changes before deploying to live site
