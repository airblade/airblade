Here are my main open source repos.


### Ruby / Rails

- [factor](//github.com/airblade/factor-public) - a zero-dependency Ruby client for FreeAgent's API.
  - Factor has shown its mettle over 5 years of constant production use.
- [quo_vadis](//github.com/airblade/quo_vadis) - multifactor authentication for Rails 6 and 7.
  - Devise is over-engineered; rodauth and Rails are different shapes.
- [template_form](//github.com/airblade/template_form) - simple Rails form builder using templates to define the HTML.
  - Specify the HTML you want with, well, HTML (not Ruby, unlike most form builders).
  - I use this in all my Rails apps; it does everything I need (and nothing I don't, so it may not cover your use case).
- [logicum](//github.com/airblade/logicum) - a simple, consistent interface for executing a unit of business logic.
  - An experiment; it works well but I'm not sure how much benefit there really is.
- [paper_trail](//github.com/paper-trail-gem/paper_trail) - tracks changes to your Rails models.
  - I released this in 2010, grew it for a couple of years into the most popular versioning gem for Rails, then handed it to a new maintainer.
- [css_dryer](//github.com/airblade/css_dryer) - the first nested-CSS plugin for Rails (2006!).
  - Happy times!


### JavaScript

- [stimulus-datepicker](//github.com/airblade/stimulus-datepicker) - Stimulus-powered, accessible date picker.
  - Also supports Vim hjkl navigation :)


### Vim

- [vim-gitgutter](//github.com/airblade/vim-gitgutter) - shows git diff markers in the sign column and stages/unstages/undoes hunks and partial hunks.
  - Including intra-line highlighting more sophisticated than GitHub's.
  - Vim's most popular diff plugin and my most starred repo.
- [vim-rooter](//github.com/airblade/vim-rooter) - changes Vim working directory to project root.
  - Originally written for the one and only Topfunky.
- [vim-localorie](//github.com/airblade/vim-localorie) - easy lookup of translations for Rails i18n YAML keys.
  - The niftiest part is a line-number-preserving YAML reader
- [vim-matchquote](//github.com/airblade/vim-matchquote) - %-style motion for single/double quotation marks, backticks, and pipe.
- [vim-tag-closer](//github.com/airblade/vim-tag-closer) - close HTML tags on demand.
- [vim-highline](//github.com/airblade/vim-highline) - toggle a line highlight for any line.
- [vim-accent](//github.com/airblade/vim-accent) - type accented characters without remembering their pseudo versions.
- [vim-current-search-match](//github.com/airblade/vim-current-search-match) - highlights the current search match.
- [vim-tcs](//github.com/airblade/vim-tcs) - integrates [tcs](//github.comm/airblade/tcs) with Vim.
- [voom](//github.com/airblade/voom) - a simplest-thing-that-works plugin manager for Vim.


### Other

- [tcs](//github.comm/airblade/tcs) - Tailwind class sorter.
  - Sorts the classes in your HTML into Tailwind's recommended class order.
  - Standalone; does not require Prettier.
- [git-stager](//github.com/airblade/git-stager) - stage and unstage files using only your space bar.
  - No more `git add path/to/deeply/nested/file`.
  - Written in Ruby but I feel it should be bash or POSIX shell.
- [volksbanker-awk](//github.com/airblade/volksbanker-awk) - AWK program to convert Volksbank bank statements into FreeAgent-compatible ones.
- [sinter](//github.com/airblade/sinter) - Barebones syntax-error checking.
