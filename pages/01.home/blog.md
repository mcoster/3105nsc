---
title: Home
body_classes: 'header-image fullwidth'
child_type: item
post_icon: calendar-o
content:
    items: '@self.children'
    limit: 10
    order:
        by: date
        dir: desc
    pagination: '1'
modular_content:
    items: '@self.modular'
    order:
        by: default
        custom:
            - _important-reminders
            - _unit-preparations
feed:
    description: '3105NSC Advanced Organic Chemistry'
    limit: 10
hide_git_sync_repo_link: false
metadata:
    'twitter:card': summary
    'twitter:site': '@getgrav'
    'twitter:creator': '@MarkCoster_Chem'
    'og:title': '3105NSC Advanced Organic Chemistry'
    'og:description': 'Course Hub website for 3105NSC Advanced Organic Chemistry at Griffith University'
    'twitter:image': 'https://3105nsc.mcoster.net/user/pages/01.home/3105NSC-twitter-image.JPG'
---

