---
published: false
layout: post
comments: true
title: dark-SJT
date: 2022-01-27 08:30:00
repo: https://github.com/Korak-997/dark-SJT
download: https://github.com/Korak-997/dark-SJT/archive/refs/heads/master.zip
demo: https://korak-997.github.io/dark-sjt/
author: Korak Kurani
thumbnail: dash.jpg
license: MIT
license_link: https://opensource.org/license/MIT
---

Dark- Simple Jekyll Theme, is a [Jekyll](https://jekyllrb.com/) theme.

It is **100%** Free and Open Source :)

## Installation

### Usage

* First of all here is a list of things you need to install on your **PC** before being able to edit or develop the **Website**
  * [Ruby](https://www.ruby-lang.org/en/) , version >= 3.0.0
  * [Jekyll](https://jekyllrb.com/), version >= 4

Then simply **Clone** or **Download** the repository into your pc.

* Open Terminal in the project folder and use these commands
  * this will install all needed gems and packages
    * `$ bundle install`
  * This build and runs the website on `localhost:4000`
    * `$ jekyll serve`
* Now by opening your browser and going to `localhost:4000` you should see the Website running :P

### Edits and Personalizations

The theme is made generally so you should get into the codes and change some details based on your needs.

* `_config.yml`: here you can change main informations like
  * title for your website
  * author for your website
  * description for your website
  * profile image (For this you need to upload your own also in `assets/images`)
  * email
  * telefon number
  * brand logo (at the moment is only as TEXT possible)
* `favicon.png`: you can simply delete this file and upload your own `favicon` with the same name and it will be automatically updated in browser
* `_data`: here you can edit many of websites data
  * `projects.json`: here you can add links and descriptions for your own projects
  * `sections.json`: here you can add or remove website sections like (About, Projects)
  * `skills.json`: here you can change the list to match your skills, simply add or remove names or tools or programming languages and you get a related Icon :)
  * `scoials.json`: here you can add or remove links to your social accounts
* `_includes/sections/about.html`: here you can edit your about section by adding any texts you like

### Notes

* In case you added any social accounts or skills and the Icon was missing you should check how the name of the icon actually is from the providers
  * For social icons visit [Ui Kit Icon](https://getuikit.com/docs/icon)
  * For skill icons visit [Dev Icon](https://devicon.dev/)

* For informations on deploying your website [click here](https://jekyllrb.com/docs/github-pages/) or [click here](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/creating-a-github-pages-site-with-jekyll) or [click here](https://www.moncefbelyamani.com/making-github-pages-work-with-latest-jekyll/)

## Contribute

Feel free to use or edit it in anyway you love , or you can simply make a **PR** to change something :D

* **PR**s can be made to [Dev-branch](https://github.com/Korak-997/dark-SJT/tree/dev)

You found an Issue or there is something you wish it will be better just open a new [ISSUE](https://github.com/Korak-997/dark-SJT/issues/new/choose)

## Credits

* [Dev Icon](https://devicon.dev/) used for **Skills Icons**
* [Ui Kit](https://getuikit.com/) used for **Styling**
* [Pixabay](https://pixabay.com/) used for **Profile Pic**
* [Favicon.io](https://favicon.io/) used for **Generating Favicon**
