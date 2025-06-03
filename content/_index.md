---
title: 'Home'
date: 2023-10-24
type: landing
sections:
  - block: resume-biography
    content:
      # The user's folder name in content/authors/
      username: admin
    design:
      spacing:
        padding: [0, 0, 0, 0]
      biography:
        style: 'text-align: justify; font-size: 0.8em;'
  - block: collection
  content:
    filters:
      folders: [blog]  # Указывает на папку с записями
    # Добавьте параметры отображения:
    title: "Последние записи блога"
    subtitle: ""
    count: 5            # Количество отображаемых записей
    sort_by: 'Date'     # Сортировка по дате
    sort_ascending: false # Новые сверху
  design:
    view: list          # Формат отображения (list/compact)
    columns: '1'         # Количество колонок
    spacing:
      padding: ['3rem', 0, '6rem', 0]  # Отступы
      
