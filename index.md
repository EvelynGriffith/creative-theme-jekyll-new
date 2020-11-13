---
layout: home
header:
  title: Paper, Pencil, and Everything in Between!
  text: >
    Welcome to Lillian Griffith's Portfolio! To view her masterpeices click on the button below and let's get started!
  action: # action button is optional
    label: Find Out More
    url: '#about'


sections:
  - type: call-to-action.html
    section_id: about
    background_style: bg-primary
    title: Learn More about the Artist!
    text: To learn more about what Lillian works on you can get connected with her, or fill out one of our forms! To get connected, please click the button below!
    actions:
      - title: Get Connected!
        url: '#services'
        class: btn-light

  - type: services.html
    section_id: services
    #background_style: bg-info
    title: At Your Service
    services:
      - title: Commission Form!
        text: To request a specific artistic peice, please fill out this form!
        icon: fa-paper-plane
      - title: Contact Form!
        icon: fa-laptop-code
        text: To get in touch with the artist, please fill out this form!


  - type: portfolio.html
    # this section has always ID 'portfolio'
    #section_id: portfolio
    #background_style: bg-dark
    projects:
      - title: Project 1
        text: This is a very short project description.
        # the images are located in:
        # img/portfolio/fullsize
        # img/portfolio/thumbnails
        icon: 1.jpg
        url: '#'
      - title: Project 2
        text: This project was done by Lillian in her freshman year of high school and represents.....
        icon: img/portfolio/fullsize/Clay Tree.png
        url: '#'
      - title: Project 3
        text: This is a very short project description.
        icon: 3.jpg
        url: '#'
      - title: Project 4
        text: This is a very short project description.
        icon: 4.jpg
        url: '#'
      - title: Project 5
        text: This is a very short project description.
        icon: 5.jpg
        url: '#'
      - title: Project 6
        text: This is a very short project description.
        icon: 6.jpg
        url: '#'

  - type: aside.html
    section_id: aside
    title: View More!
    text: To view more, please click the button below!
    actions:
      - title: Portfolio
        url: 
        class: btn-light

  - type: members.html
    section_id: members
    title: Our Crew!
    background_style: bg-info text-white
    members:
      - title: Christina M. Aponte
        text: Singer and Songwriter
        image: assets/img/members/person1.jpg
        url: '#'
      - title: Gary D. Stevens
        text: Bass guitar.
        image: assets/img/members/person2.jpg
        url: '#'
      - title: Devon J. Fletcher
        text: Lead guitar.
        image: assets/img/members/person3.jpg
        url: '#'
      - title: Todd E. Anderson
        text: Drums, percussion.
        image: assets/img/members/person5.jpg
        url: '#'
      - title: Daniel T. Riley
        text: Musician, songwriter, producer.
        image: assets/img/members/person6.jpg
        url: '#'
      - title: Ella P. Walter
        text: PR.
        image: assets/img/members/person7.jpg
        url: '#'

  - type: timeline.html
    section_id: timeline
    title: Major Achievements!
    background_style: bg-dark text-primary
    last_image: assets/img/timeline-end.png
    actions:
      - image: assets/img/portfolio/thumbnails/1.jpg
        title: >+
          2017-2018
          **Humble Beginnings**
        text: >-
          We begun with small group of people willing to work hard and make our
          teaching skills worth , in front of all others!
      - image: assets/img/portfolio/thumbnails/2.jpg
        title: >+
          November 2019
          An Coaching started
        text: >-
          We started to gather like minded people and started our stategies
          and future plans to them. As a result , interested people joined us!

  - type: contact.html
    section_id: contacts
    title: Let's Get In Touch!
    text: >-
      Fill out these forms to get in touch with Lillian! Or you can find her on social media/send her an email!
    actions:
    - title: E-Mail
      icon: fa-envelope
      url: mailto:contact@yourwebsite.com
    - title: Facebook
      icon: fa-facebook
      icon_type: fab
      url: '#'
    - title: Contact Form!
      icon: fa-envelope
      url: '#"
  

---
