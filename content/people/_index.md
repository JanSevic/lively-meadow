---
# To publish author profile pages, remove all the `build` and `cascade` settings below.
# build:
#   render: never
# cascade:
#   build:
#     render: never
#     list: always

type: landing

sections:
  - block: collection
    id: people
    content:
      title: Our Team
      text: Meet the group.
      count: 0             # 0 = show all
      filters:
        folders:
          - people        # list author profiles
        #tag: team          # optional: only those tagged "team"
      sort_by: 'Title'     # or 'Date'
      sort_ascending: true
    design:
      view: article-grid
      fill_image: false
      columns: 3
      show_read_time: false
      show_date: false
      show_read_more: false
---
