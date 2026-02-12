# ADDITIONAL PAGES CREATION GUIDE

## This document contains templates and guidelines for creating the remaining pages

Due to file size constraints, here are the detailed specifications for creating about.html, services.html, and contact.html pages.

---

## ABOUT.HTML PAGE STRUCTURE

### Required Sections:
1. **Hero Section** - "About HygieneXperts"
2. **Company Story** - 1000+ words rewritten content about:
   - 8+ years of experience
   - Mission and vision
   - Values and commitment
   - Team expertise
3. **Our Values Section** with cards for:
   - Professionalism
   - Reliability
   - Eco-Friendly Practices
   - Customer Satisfaction
4. **Team Section** (if you have team photos)
5. **Certifications & Accreditations**
6. **Timeline** - Company milestones
7. **CTA Section**

### SEO Requirements for About Page:
- Title: "About HygieneXperts | Commercial Cleaning Sydney Experts Since 2017"
- Meta Description: "Learn about Sydney's premier commercial cleaning company. 8+ years experience, eco-friendly solutions, certified professionals across Greater Sydney Metro."
- H1: "About HygieneXperts - Sydney's Trusted Commercial Cleaning Sydney Partner"
- Min 1000 words of unique content
- Internal links to homepage and services

---

## SERVICES.HTML PAGE STRUCTURE

### Required Sections:

#### 1. Hero Section
- Title: "Professional Cleaning Services Sydney - Commercial & Residential"

#### 2. Service Details (250+ words each):

**Commercial Cleaning Sydney**
- Daily office cleaning
- Janitorial services
- Floor maintenance
- Restroom sanitization
- Window cleaning
- Carpet cleaning
- Pricing: $25-$45/hour
- Coverage: All Sydney Metro

**Office Cleaning Services Sydney**
- Workstation cleaning
- Conference room maintenance
- Kitchen/break room cleaning
- After-hours service
- Customized schedules
- Quality assurance

**Residential Cleaning Sydney**
- Regular house cleaning
- Deep cleaning services
- Spring cleaning
- Move-in/move-out cleaning
- Eco-friendly products
- Flexible scheduling

**Carpet Cleaner Sydney**
- Hot water extraction
- Steam cleaning
- Stain removal
- Odor elimination
- IICRC certified
- Commercial & residential

**End of Lease Cleaning Sydney / Bond Cleaning Sydney**
- Full property cleaning
- Kitchen deep clean
- Bathroom sanitization
- Window cleaning
- Carpet steam cleaning
- 100% bond back guarantee

**Rangehood Cleaning Sydney**
- Commercial kitchen exhaust cleaning
- Ductwork cleaning
- Filter replacement
- Compliance documentation
- AS 1851-2012 standard
- Fire safety compliance

### SEO Requirements for Services Page:
- Title: "Cleaning Services Sydney | Commercial, Office, Residential | HygieneXperts"
- Meta Description: "Complete cleaning services across Sydney: commercial cleaning, office cleaning, house cleaning, carpet cleaning, bond cleaning. Free quotes. Call +61 498 203 983"
- Multiple H2 tags with keywords
- Internal links to homepage
- Service area mentions

---

## CONTACT.HTML PAGE STRUCTURE

### Required Sections:

#### 1. Hero Section
- Title: "Contact HygieneXperts - Get Your Free Cleaning Quote"

#### 2. Contact Form Fields:
```html
- Full Name (required)
- Email Address (required)
- Phone Number (required)
- Service Type (dropdown):
  * Commercial Cleaning Sydney
  * Office Cleaning Services Sydney
  * Residential Cleaning Sydney
  * Carpet Cleaner Sydney
  * End of Lease Cleaning Sydney
  * Rangehood Cleaning Sydney
  * Other
- Property Type (dropdown):
  * Office/Commercial
  * Residential Home
  * Apartment/Unit
  * Industrial
- Preferred Contact Method (radio):
  * Phone
  * Email
- Message (textarea, required)
- Submit Button: "Request Free Quote"
```

#### 3. Contact Information Cards:
- **Phone**: +61 498 203 983
- **Email**: info@hygienexperts.com.au
- **Address**: 12C Tungarra Rd, Girraween, NSW 2145
- **Hours**: 24/7 Available
- **Response Time**: Within 24 hours

#### 4. Service Areas Map Section
- List of Sydney suburbs served
- Service coverage radius

#### 5. FAQ Section (5-8 questions)
- How quickly can you provide service?
- What are your rates?
- Are you insured?
- Do you use eco-friendly products?
- Do you offer emergency cleaning?

#### 6. Google Maps Embed
```html
<iframe 
  src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3314.1234567890!2d151.1726638!3d-33.7307353!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x5cee8aad5858532a!2sHygieneXperts!5e0!3m2!1sen!2sau!4v1234567890"
  width="100%" 
  height="450" 
  style="border:0;" 
  allowfullscreen="" 
  loading="lazy">
</iframe>
```

### SEO Requirements for Contact Page:
- Title: "Contact HygieneXperts | Commercial Cleaning Sydney | Free Quote"
- Meta Description: "Contact Sydney's leading cleaning service. Free quotes, 24/7 availability, fast response. Call +61 498 203 983 or fill our quick form."
- H1: "Contact HygieneXperts for Professional Commercial Cleaning Sydney"
- Schema markup for ContactPage

---

## CSS ADDITIONS FOR OTHER PAGES

### Contact Page Specific Styles:
```css
.contact-form-section {
    background-color: var(--bg-light);
    padding: 80px 0;
}

.form-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 20px;
    max-width: 800px;
    margin: 0 auto;
}

.form-group {
    margin-bottom: 20px;
}

.form-group label {
    display: block;
    font-weight: 600;
    margin-bottom: 8px;
    color: var(--text-dark);
}

.form-control {
    width: 100%;
    padding: 14px;
    border: 2px solid var(--border-color);
    border-radius: 8px;
    font-size: 15px;
    transition: var(--transition);
}

.form-control:focus {
    border-color: var(--primary-color);
    outline: none;
}

.form-control-full {
    grid-column: 1 / -1;
}

textarea.form-control {
    min-height: 150px;
    resize: vertical;
}

.contact-info-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 30px;
    margin: 50px 0;
}

.contact-info-card {
    background-color: var(--bg-white);
    padding: 30px;
    border-radius: 12px;
    text-align: center;
    box-shadow: var(--shadow-sm);
}

.contact-icon {
    width: 60px;
    height: 60px;
    background-color: rgba(0, 102, 204, 0.1);
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    margin: 0 auto 20px;
    color: var(--primary-color);
}
```

### Services Page Specific Styles:
```css
.service-detail-section {
    padding: 80px 0;
    border-bottom: 1px solid var(--border-color);
}

.service-detail-section:nth-child(even) {
    background-color: var(--bg-light);
}

.service-detail-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 60px;
    align-items: center;
}

.service-detail-image img {
    border-radius: 12px;
    box-shadow: var(--shadow-md);
}

.service-features {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 20px;
    margin: 30px 0;
}

.service-feature-item {
    display: flex;
    align-items: flex-start;
    gap: 12px;
}

.pricing-box {
    background: linear-gradient(135deg, var(--primary-color), var(--secondary-color));
    color: white;
    padding: 30px;
    border-radius: 12px;
    margin: 30px 0;
}

.pricing-box h3 {
    font-size: 24px;
    margin-bottom: 10px;
}

.price {
    font-size: 36px;
    font-weight: 900;
}
```

---

## JAVASCRIPT ADDITIONS

### For Contact Form:
Already included in main script.js file - form validation is complete.

### For Services Page:
```javascript
// Service tabs or accordions (if needed)
const serviceTabs = document.querySelectorAll('.service-tab');
const serviceContents = document.querySelectorAll('.service-content');

serviceTabs.forEach(tab => {
    tab.addEventListener('click', () => {
        const target = tab.dataset.target;
        
        serviceTabs.forEach(t => t.classList.remove('active'));
        serviceContents.forEach(c => c.classList.remove('active'));
        
        tab.classList.add('active');
        document.getElementById(target).classList.add('active');
    });
});
```

---

## QUICK CREATION STEPS

1. **Copy index.html structure**
2. **Replace hero content** with page-specific content
3. **Add page-specific sections** as outlined above
4. **Update meta tags** and title
5. **Add internal links** back to homepage
6. **Include schema markup** if applicable
7. **Test all links** and forms
8. **Validate HTML** at validator.w3.org

---

## CONTENT WRITING GUIDELINES

### For Each Page:
- Minimum 1000 words for About, Services pages
- Use primary keywords naturally (2-3% density)
- Include secondary keywords throughout
- Write in engaging, professional tone
- Break content into digestible paragraphs
- Use bullet points for features/benefits
- Include clear CTAs every 300-400 words
- Add internal links to homepage
- Optimize images with alt tags

### Keyword Placement:
- H1 tag: Primary keyword
- First paragraph: Primary keyword
- H2 tags: Secondary keywords
- Throughout content: Natural variations
- Meta description: Primary keyword
- Image alt tags: Relevant keywords

---

This guide ensures consistency across all pages while maintaining SEO best practices and user experience standards.
