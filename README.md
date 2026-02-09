# Temple Management SaaS

A web-based SaaS application for Hindu temple management, focusing on devotee registration and service booking.

## Features

### Current Features (v1.0)
- **Devotee Registration Form**
  - Primary devotee name
  - Gotra (common for all family members)
  - Individual Nakshatra for each person
  - Support for up to 10 family members
  - Service selection dropdown (10 services)
  - Form validation
  - Stub response ("OK") on submission

### Form Fields
1. **Primary Devotee**
   - Name (required)
   - Gotra (required, shared with family)
   - Nakshatra (required)

2. **Family Members** (up to 10)
   - Name (required)
   - Nakshatra (required, unique per member)
   - Gotra (inherited from primary devotee)

3. **Service Selection**
   - Dropdown with 10 dummy services (Service-1 through Service-10)

## Technology Stack
- HTML5
- CSS3 (with gradient background in Indian flag colors)
- Vanilla JavaScript
- No external dependencies

## Usage

1. Open `index.html` in a web browser
2. Fill in the primary devotee information
3. Click "+ Add Family Member" to add family members (up to 10)
4. Select a service from the dropdown
5. Click "Submit Registration"
6. You'll see an "OK" response message

## Future Enhancements
- Backend API integration
- Database storage
- Payment processing
- Service management dashboard
- Devotee history tracking
- Receipt generation
- Admin panel

## Local Development

Simply open `index.html` in your browser. No build process required.

## Live Demo

View at: https://kbharada.github.io/temple-management-saas/

## License

MIT