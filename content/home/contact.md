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
  email: meikangusa@gmail.com
  phone: (213) 551-4592
  address:
    street: 3454 Trousdale Parkway
    city: Los Angeles
    region: CA
    postcode: '90089-0153'
    country: United States
    country_code: US
  coordinates:
    latitude: '34.0224'
    longitude: '-118.2851'
  directions: AHF Building #105
#  office_hours:
#    - 'Monday 10:00 to 13:00'
#    - 'Wednesday 09:00 to 10:00'
#  appointment_url: 'https://meikang.netlify.app'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/meican77'
#    - icon: video
#      icon_pack: fas
#      name: Zoom Me
#      link: 'https://zoom.com/5155941958'

design:
  columns: '2'
---
