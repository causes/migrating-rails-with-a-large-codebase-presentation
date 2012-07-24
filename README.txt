Migrating Rails with a Large Codebase

Causes Engineering: Greg Hurrell and Adam Derewecki
This presentation details our journey of upgrading the Causes app from Rails 2.1
to Rails 3.2.x and our learnings along the way.

Presentation technology
  - reveal.js: JS slideshow library
  - highlight.js: JS syntax highlighting library, with themes

To build locally:
  # make sure the prerequisites are in place
  git submodule update --init
  bundle

  # edit the index.haml file to taste, then build
  bundle exec rake
