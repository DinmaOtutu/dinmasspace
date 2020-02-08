---
title: Home
sections:
  - component: HeroBlock
    content: ''
    section_id: hero
    title: Welcome! I hope you find this space interesting sooner or later!
    type: heroblock
  - component: PortfolioBlock
    layout_style: tiles
    num_projects_displayed: 2
    section_id: latest-projects
    subtitle: ''
    title: Recent
    type: portfolioblock
    view_all_text: View All
    view_all_url: portfolio/index.html
  - actions:
      - label: View Blog
        url: blog/index.html
    component: PostsBlock
    num_posts_displayed: 4
    section_id: latest-posts
    subtitle: ''
    title: Latest from the Blog
    type: postsblock
  - component: ContactBlock
    section_id: contact
    subtitle: ''
    title: Contact Me
    type: contactblock
menus:
  main:
    title: Home
    weight: 1
template: home
---

