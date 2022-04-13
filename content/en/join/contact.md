---
# An instance of the Contact widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 20

title: Contact

content:
  # Contact (edit or remove options as required)

  email: georgios.bouloukakis@telecom-sudparis.eu
  phone: 888 888 88 88
  address:
    street: 9 Rue Charles Fourier
    city: Courcouronnes FR
    region: Île-de-France
    postcode: '91000'
    country: France
    country_code: FR
  coordinates:
    longitude: '2.443393315594366'
    latitude: '48.625245547208046'
  directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
  office_hours:
    - 'Monday 10:00 to 13:00'
    - 'Wednesday 09:00 to 10:00'
  appointment_url: 'https://calendly.com'

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