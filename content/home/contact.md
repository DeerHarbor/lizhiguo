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
  email: glz1997@tju.edu.cn
  phone: +86 18802293110
  address:
    street: No.5 Kelian Road
    city: Shenzhen
    region: Guangdong
    postcode: '94305'
    country: China
    country_code: CHN
  coordinates:
    latitude: '22.724033'
    longitude: '113.913925'
  directions: Shenzhen Bay Laboratory 
#  office_hours:
#    - 'Monday 10:00 to 13:00'
 #   - 'Wednesday 09:00 to 10:00'
#  appointment_url: 'https://calendly.com'
#  contact_links:
 #   - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/Twitter'
    - icon: video
      icon_pack: fas
      name: Zoom Me
      link: 'https://zoom.com'

design:
  columns: '2'
---
