# Setup
> Note: you can ignore this file. It was just for who wants preview locally or
know how it was configured

## Way to preview locally how a page will render on github pages with no template configured
_This instructions is for any github repository_

**1. Create a Gemfile with this contend**

```ruby
source "https://rubygems.org"

gem "github-pages", group: :jekyll_plugins
```

**2. Install gems**: `bundle install`
**3. Preview pages at <http://localhost:4000/>**: `jekyll serve`
