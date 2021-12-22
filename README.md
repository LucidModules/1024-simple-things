# 1024-simple-things
One day I've read on warsztat.gd that `to create a game you just need to implement 2000 simple things`. While web applications are less complex than games, there is still a long way to go from `git init` to production.

Therefore, I paraphrase this sentence into:

`The web app is just 1024 simple things to do.`

This repository is a guide for web app decomposition. To help us detect incorrect time estimates early, and warn us when we plan to fly too close to the sun.
It starts as single README file, but it may be divided into Wiki pages in the future.

## Administrator Dashboard
- authentication
  - login page
  - registration with CLI or by Super Administrator
- authorization (ACL)
- password recovery via e-mail
- 2FA

## Customer account
- authentication
  - login page
  - registration page
- welcome email
- password recovery
- 2FA
- Social Login

## Contact form
- register custom domain

## Mailing
- integration with 3rd party mailing provider
- embedded SVG might not be rendered properly - use base64 or provide a link to the image

## Navigation
- menu
- breadcrumbs
- footer links
