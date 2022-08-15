---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

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

  # Contact details (edit or remove options as required)
  email: honggang@stat.tamu.edu
  phone: +1(979)-218-9013
  address:
    street: 2250 Dartmouth St. 628 Apt.
    city: College Station
    region: TX
    postcode: '77840'
    country: United States
    country_code: US
  office_hours:
    - 'Workdays'

design:
  columns: '2'
---
