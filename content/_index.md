---
title: 'Home'
date: 2023-10-24
type: landing
sections:
  - block: resume-biography
    content:
      username: admin
    design:
      spacing:
        padding: [0, 0, 0, 0]
    biography:
      style: 'text-align: justify; font-size: 0.8em;'  # Закрытая кавычка!

  - block: collection
    content:
      filters:
        folders: [blog]
      title: "Последние записи блога"
      count: 5
      sort_by: 'Date'
      sort_ascending: false
    design:
      spacing:
        padding: ['3rem', 0, '6rem', 0]
      view: list
      columns: '1'
---