---
title: Home
body_classes: 'header-image fullwidth'
child_type: item
content:
    items: '@self.children'
    limit: 10
    order:
        by: date
        dir: desc
    pagination: '1'
hide_git_sync_repo_link: false
continue_links_as_buttons: true
modular_content:
    items: '@self.modular'
    order:
        by: default
        custom:
            - _important-reminders
            - _unit-preparations
feed:
    description: 'Grav CMS Open Course Hub Description'
    limit: 10
---

