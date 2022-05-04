# An open-source project to teach simmers how to make mods & custom content, built by Creator Musings

Questions? Ask on the Creator Musings [Discord Server](https://discord.gg/qxz5Kn5).

# Running locally
- [install docker](https://docs.docker.com/engine/install/) 
- Run ```docker run -i -t --rm -u 1000:1000 -p 4000:4000 -v `pwd`:/opt/app -v `pwd`/.bundler/:/opt/bundler -e BUNDLE_PATH=~/opt/bundler -w /opt/app ruby:2.7 bash -c "bundle install && bundle exec jekyll serve --watch -H 0.0.0.0"```

---
This course was created using the [Jekyll Course template from P2PU](http://github.com/p2pu/jekyll-course-template).

Course content ("Modules") are shared under a [CC BY-NC-SA 4.0 license](https://creativecommons.org/licenses/by-nc-sa/4.0/).
