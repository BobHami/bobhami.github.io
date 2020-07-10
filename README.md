# Site setings
name: 'Horace'
description: 'Horace is a simple Jekyll theme for writers and bloggers. Explore it yourself.'
meta_description: 'Jekyll template, minimal style, perfect for bloggers.'
logo: 'assets/images/logo.png'
favicon: 'assets/images/favicon.ico'
baseurl: 
production_url: https://horace.netlify.com/
disqus: 'justgoodthemes'
mailchimp_url: '//justgoodthemes.us3.list-manage.com/subscribe/post?u=78f1bab16028354caeb23aecd&amp;id=4a7330d117'
cover_image: bc_1.jpg
# Add your GA Tracking Id
ga_analytics: 


# Author
author:
  name: 'Daniel Bennett'
  image: 'authorimage.jpg'
  greetings: 'Hi there!'
  description: "My name is Daniel Bennett. I'm a freelance front-end developer, author and speaker based in Austin, TX. It’s nice to meet you."
  bio: 'Daniel is a designer, photographer, speaker, author of a couple of books about typography and the founder of photo magazine Curious.'

# Contact form setings
email: youremail@email.com
contact_page_description: "Horace theme comes with a contact form built-in. You can use this form with Formspree service and get up to 50 submissions for free. Also, you can easily switch to another service if you want."
thankyou_page_description: "Your message has been successfully sent. We will contact you very soon!"

# Social links
twitter: 'username'
facebook: 'username'
github: 'username'
codepen: 'username'
dribbble: 'username'
medium: '@username'
instagram: 'username'
pinterest: 'username'
linkedin: 'username'
producthunt: '@username'

# Navigation
navigation:
  - text: About
    url: /about/
  - text: Style Guide
    url: /style-guide/
  - text: Contact Me
    url: /contact/

# Required Plugins
plugins_dir:
  - jekyll-paginate
  - jekyll-tagsgenerator
  - jekyll-seo-tag
  - jekyll-sitemap

# Pagination
paginate: 5
paginate_path: /page:num/

# Permalinks
permalink: /:title

# Other
markdown: kramdown

# Sass
sass:
  sass_dir: _sass
  style: compressed
