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
  autolink: false

  # Email form provider
  form:
    provider: netlify
    formspree:
      id:
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: false

  # Contact details (edit or remove options as required)
  email: enaveen98@gmail.com
  phone: +91 90032 78157
  address:
    street: 1 Convent Avenue
    city: New York
    region: NY
    postcode: '10027'
    country: United States
    country_code: US
  coordinates:
    latitude: '40.812880'
    longitude: '-73.952880'
  directions: 
  office_hours:
  # appointment_url: 'https://calendly.com'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM me on Twitter
      link: 'https://twitter.com/naveenelango98'
    - icon: instagram
      icon_pack: fab
      name: Checkout
      link: 'https://www.instagram.com/naveen_elango_/'

design:
  columns: '2'
---
