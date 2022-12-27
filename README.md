# [jrgn.org](https://jrgn.org)

## About

This private repository is the [hugo](https://gohugo.io/) source code for my homelab website.

---

## Root directory command line usage

### - to [test changes](https://gohugo.io/commands/hugo_server/) on localhost (with drafts):

```pwsh
hugo server -D
```

### - to [create new content](https://gohugo.io/commands/hugo_new/):

```pwsh
hugo new [path] [flags]
```

- typical path value: posts/title.md

### - to [build and publish](https://gohugo.io/commands/hugo/):

- Change the publishDir value in config.toml if necessary

```pwsh
hugo
```
