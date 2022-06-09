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
  email: adel.bibi@eng.ox.ac.uk
  address:
    street: 20.16, Department of Engineering Science, University of Oxford, Parks Road
    city: Oxford
    postcode: OX1 3PJ
    country: United Kingdom
    country_code: UK
  coordinates:
    latitude: '51.76027734553316'
    longitude: '-1.259918449861943'
  # contact_links:
  #   - icon_pack: skype
  #     link: 'https://zoom.com'
  #   - icon: twitter
  #     icon_pack: fab
  #     name: DM Me
  #     link: 'https://twitter.com/Twitter'
  #   - icon: video
  #     icon_pack: fas
  #     name: Zoom Me
  #     link: 'https://zoom.com'

design:
  columns: '2'
---
