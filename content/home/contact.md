---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Contact
subtitle: If you want to get in touch, please use this contact form. All messages will be forwarded directly to my e-mail inbox and I will get back to you as soon as possible.

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
   contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/Twitter'
    - icon: researchgate
      icon_pack: ai
      name: Follow me on ResearchGate!
      link: 'https://www.researchgate.net/profile/Anna-Luisa-Haecker-2'

design:
  columns: '2'
---
