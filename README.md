# rtetrust

Website for the Ronald Tickner Educational Trust.

http://ecresswell.github.io/rtetrust/

## Local development

Requires Ruby and Bundler. Install dependencies with `bundle install`.

To serve locally on WSL2, output `_site` to the Linux filesystem to avoid NTFS permission issues:

```
bundle exec jekyll serve --destination /tmp/rtetrust-site
```