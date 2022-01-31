# hugo-theme

## Installation

### As a Hugo Module (recommended)

1. From your project's root directory, initiate the hugo module.

```
hugo mod init <git_repo_domain>/<your_user>/<your_project>
```
2. Add the theme's repo to your `config.[yaml,toml]`:

```yaml
theme: github.com/davidrbingham/hugo-theme
```

```toml
theme = ["github.com/davidrbingham/hugo-theme"]
```

### As Git Submodule

Inside the folder of your Hugo site run:

```
git submodule add https://github.com/davidrbingham/hugo-theme.git themes/hugh-theme
```

For more information read the [official setup guide][2] of Hugo.

## The config file

You will find an example config file in [`demo/config.yaml`][3].

[1]: https://gohugo.io/
[2]: https://gohugo.io/overview/installing/
