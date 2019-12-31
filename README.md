# Dependencies
- Hugo (https://gohugo.io/)

# Compilation
Input posts are written in org format (https://orgmode.org/) and converted to
hugo markdown format by ox-hugo plugin (https://ox-hugo.scripter.co/). Once in
markdown format, hugo converts it into static html site

# Build
- During development

``` sh
# Start hugo server
hugo server

# Start hugo server with drafts enabled
hugo server -D
```

- Build steps

``` sh
# Generate static site in "docs"
hugo
```
