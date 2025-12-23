# Fort Lupton Lumber Mill - Project Notes

## Business Overview

**Business Name:** Fort Lupton Lumber Mill  
**Business Type:** Lumber mill operations  
**Location:** Fort Lupton, Colorado (assumed based on name)  

## Primary Goals

1. **Information**: Provide comprehensive information about the mill's services, products, and operations
2. **E-Commerce**: Enable online ordering and sales, particularly for shavings products

## Target Audience

- Local farms requiring animal bedding (shavings)
- Construction businesses needing lumber
- Individual contractors and DIY customers
- Agricultural operations

## Site Requirements

### Required Pages

1. **Home** - Introduction, hero section, key offerings highlights
2. **About** - Company history, values, team, facilities
3. **Services** - Detailed service offerings and capabilities
4. **Order Shavings Now** - E-commerce functionality for shavings products with ordering form
5. **FAQ** - Common questions about products, delivery, pricing
6. **Contact** - Contact form, location map, business hours, phone/email

### Technical Stack

- **Format:** HTML, CSS, JavaScript (vanilla)
- **Hosting:**  GitHub Pages, Netlify, or Vercel (static hosting)
- **Deployment:* Git-based deployment with continuous integration

## Success Criteria for "Website Complete"

### Functional Requirements

- [ ] All 6 required pages created with appropriate content sections
- [ ] Navigation system functional across all pages
- [ ] Order Shavings Now page has working product listings and order form
- [ ] Contact form properly configured and tested
- [ ] FAQ section populated with relevant Q&A
- [ ] Responsive layout works on mobile, tablet, and desktop

### Content Requirements

- [ ] Business branding (name, tagline, colors) consistently applied
- [ ] Product descriptions written for shavings and lumber offerings
- [ ] Service descriptions complete and accurate
- [ ] Contact information verified (address, phone, email, hours)
- [ ] About page content drafted (can be placeholder pending client input)

### E-Commerce Requirements

- [ ] Product catalog structured for shavings (types, quantities, pricing)
- [ ] Order form captures: customer info, product selection, quantity, delivery preferences
- [ ] Order submission mechanism configured (email notification or Wix store integration)
- [ ] Payment integration scoped (if required) or clearly marked for future phase

### Visual & UX Requirements

- [ ] Color scheme (#3B5D3A primary, #F5E3C3 secondary) applied consistently
- [ ] Typography clear and readable (Sans-Serif family)
- [ ] Logo placeholder positioned and sized appropriately
- [ ] Call-to-action buttons prominent ("Order Now", "Contact Us", etc.)
- [ ] Images/placeholders for products, facilities, team (where applicable)

### Deployment Requirements

- [ ] Site published to Wix staging environment
- [ ] All pages accessible via navigation
- [ ] Forms tested and confirmed functional
- [ ] Site URL provided for review
- [ ] Basic SEO elements configured (page titles, meta descriptions)

## Architecture Decisions

**Decision 1:** JSON schema approach Static HTML/CSS/JS architecture
- Given Build a fully functional static website using HTML, CSS, and vanilla JavaScript
- JSON schema serves as content structure reference for building HTML pages
- Separate HTML files for each page with shared header/footer components
- CSS for styling, responsive design, and branding
- JavaScript for interactive elements (navigation, forms, FAQ accordions)
