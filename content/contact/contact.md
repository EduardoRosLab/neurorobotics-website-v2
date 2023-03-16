---
# An instance of the Contact widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 10

title: Contact
subtitle:

content:
  # Contact (edit or remove options as required)

  email: jesusgarrido@ugr.es
  phone: +34958241000 Ext. 20633
  address:
    street: CITIC-UGR. Calle Periodista Rafael Gómez Montero 2
    city: Granada
    region: Andalucía
    postcode: '18071'
    country: Spain
    country_code: SP
    content:
      coordinates:
        latitude: '37.1977852'
        longitude: '-3.6240453'
  directions: Enter the CITIC Building and take the elevator to 1st floor. Office 1.3
#  office_hours:
#    - 'Monday 10:00 to 13:00'
#    - 'Wednesday 09:00 to 10:00'
#  appointment_url: 'https://calendly.com'
  #contact_links:
  #  - icon: comments
  #    icon_pack: fas
  #    name: Discuss on Forum
  #    link: 'https://discourse.gohugo.io'

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
  columns: '1'
---
