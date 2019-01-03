---
layout: post
title:  "How I set up this blog with google domains, github pages and Jekyll"

---

1. Get a google domain name (already had one, so won't go into the details)

   - Set up an A record

   - Set up a CNAME record from <user>.github.io to <your-custom-domain-name> 

   - Optionally set up another CNAME record from from www to <your-custom-domain-name>

2. Set up Github Pages

   - Force enable https
   - Clone/Fork an existing Jekyll site

3. Post articles

   - Create a new file in the _posts folder with the naming convention <yyyy-mm-dd-title>.md
   - Add, commit & push to GitHub

##### References:

https://help.github.com/articles/setting-up-an-apex-domain/

https://www.smashingmagazine.com/2014/08/build-blog-jekyll-github-pages/

https://domains.google.com