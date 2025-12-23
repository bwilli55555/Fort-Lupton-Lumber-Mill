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

- **Format:** JSON-based content structure
- **Hosting:** Wix platform
- **Deployment:** Wix site builder integration

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

**Decision 1:** JSON schema approach  
- Given Wix hosting constraint, use JSON to define content structure and page schemas
- JSON files serve as "source of truth" for site content and can guide Wix page builder setup

**Decision 2:** Hybrid information + e-commerce model  
- Prioritize information architecture first (5 informational pages)
- "Order Shavings Now" page as lightweight e-commerce entry point
- Keep order form simple initially; can expand to full Wix Store later if needed

## Open Questions & TODOs

- [ ] Confirm actual business location and contact details
- [ ] Obtain product photos or use stock lumber/shavings imagery
- [ ] Clarify payment processing requirements (Wix Payments, PayPal, offline?)
- [ ] Define shavings product variants (bag sizes, wood types, bulk options)
- [ ] Determine delivery/shipping options and coverage area
- [ ] Confirm if mill offers custom cutting services or additional products beyond standard lumber and shavings

## Phase Progress

- **Phase 0 (Initialize):** In Progress
- **Phase 1 (Plan):** Not Started
- **Phase 2 (Implement):** Not Started
- **Phase 3 (Integrate & Polish):** Not Started
- **Phase 4 (Deploy & Finalize):** Not Started
