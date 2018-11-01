---
title: Test post for post_link tag
date: 2018-11-01 00:00:00
---
1. Using post title:

{% post_path old-post-is-ancient %}

Testing a <a href="{% post_path old-post-is-ancient %}">link</a>.

{% post_link old-post-is-ancient %}

2. Using filename:

{% post_path old-post %}

Testing a <a href="{% post_path old-post %}">link</a>.

{% post_link old-post %}