# unohee.github.io

Plain-text CV of Heewon Oh, served by GitHub Pages at https://unohee.github.io.

- Content: `index.md` (Markdown, edit this to update the CV)
- Layout: `_layouts/default.html` (one page, no images, fonts or scripts)
- Build: GitHub Pages legacy Jekyll build from `master` / root

Local preview (no Gemfile; installs gems into a throwaway GEM_HOME):

    export GEM_HOME=/tmp/jekyll-gems PATH=/tmp/jekyll-gems/bin:$PATH
    gem install --no-document jekyll kramdown-parser-gfm jekyll-seo-tag
    jekyll build -d /tmp/cv-site    # or: jekyll serve
