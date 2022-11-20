<!-- ---
widget: contact
widget_id: Contact
headless: true
weight: 60
title: Contact
subtitle: null
active: true
content:
  form:
    provider: netlify
    formspree:
      ? id
    netlify:
      captcha: false
  autolink: true
  office_hours:
    - Monday 10:00 to 13:00
    - Wednesday 09:00 to 10:00
  phone: 888 888 88 88
  appointment_url: https://calendly.com
  directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
  address:
    street: 450 Serra Mall
    city: Stanford
    region: CA
    postcode: "94305"
    country: United States
    country_code: US
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: https://twitter.com/Twitter
    - icon: video
      icon_pack: fas
      name: Zoom Me
      link: https://zoom.com
  coordinates:
    latitude: "37.4275"
    longitude: "-122.1697"
  email: test@example.org
design:
  columns: "2"
--- -->
---
# An instance of the Contact widget.
# Documentation: https://sourcethemes.com/academic/docs/page-builder/
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 60

title: Contact
subtitle:

content:
  # Automatically link email and phone or display as text?
  autolink: true
  
  # Email form provider
  form:
    provider: netlify
    formspree:
      id:
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: false
  
design:
  columns: '2'
---