---
widget: contact
headless: true  # This file represents a page section.

# ... Put Your Section Options Here (title etc.) ...
title: Contact Us
subtitle: ''
weight: 10

content:
  # Automatically link email and phone or display as text?
  autolink: false

  # Email form provider
  form:
    provider: netlify
    formspree:
      id:
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: true

  # Contact details (edit or remove options as required)
  email: kathryn.willi@colostate.edu
  phone: 888 888 88 88
  address:
    street: 450 Serra Mall
    city: Stanford
    region: CA
    postcode: '94305'
    country: United States
    country_code: US
  coordinates:
    latitude: '37.4275'
    longitude: '-122.1697'
  directions: Enter Building 1 and take the stairs to Office 200 on Floor 2

    
design:
  # Choose how many columns the section has. Valid values: '1' or '2'.
  columns: '2'
---