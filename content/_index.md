---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Hi there :)
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
    design:
      spacing:
        padding: ['50px', '0', '50px', '0']
  # - block: portfolio
  #   id: projects
  #   content:
  #     title: Research Areas & Projects
  #     text: |-
  #       <center>
  #       The main research areas which I am interested in. These are kept intentionally broad, at least for now.
  #       </center>
  #       <br/>
  #     filters:
  #       folders:
  #         - project
  #   design:
  #     # Choose how many columns the section has. Valid values: '1' or '2'.
  #     columns: '1'
  #     view: masonry
  #     # For Showcase view, flip alternate rows?
  #     flip_alt_rows: false
  #     spacing:
  #       padding: ['50px', '0', '50px', '0']
  - block: portfolio
    id: publications
    content:
      title: Publications
      text: |-
        <center>
        This list contains most but not all of my publications.</br>
        Please check my <a href="https://scholar.google.com/citations?hl=en&user=oJUHhu4AAAAJ">Google Scholar page</a> for a complete list.
        </center>
        <br/>
      filters:
        folders:
          - publication
    design:
      columns: '1'
      view: compact
      spacing:
        padding: ['50px', '0', '0', '0']
---
