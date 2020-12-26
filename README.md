# A GitHub action to run ShellCheck

Go to [ShellCheck](https://github.com/koalaman/shellcheck#readme) at GitHub

You can find the image on [Docker Hub](https://hub.docker.com/r/botsudo/action-doctum)

[![Docker Pulls](https://img.shields.io/docker/pulls/koalaman/shellcheck.svg)](https://hub.docker.com/r/koalaman/shellcheck)

I use the [koalaman/shellcheck](https://hub.docker.com/r/koalaman/shellcheck) for this action

## Example usage

```yml
  - uses: actions/checkout@v2
  - name: run shellcheck
    uses: sudo-bot/action-shellcheck@latest
    with:
        # https://github.com/koalaman/shellcheck#how-to-use
        cli-args: "myscript"
```
