# pre-commit-hooks

Reusable pre-commit hooks

<!-- toc -->

* [Hooks](#hooks)
  * [Go Err Check](#go-err-check)
  * [Go Fumpt](#go-fumpt)
  * [Go Fmt Import](#go-fmt-import)
  * [Go Static Check](#go-static-check)
  * [Go Vet](#go-vet)
  * [License-Eye](#license-eye)
  * [Packer Format](#packer-format)
  * [Packer Validate](#packer-validate)
* [Contributing](#contributing)
  * [Open in Gitpod](#open-in-gitpod)
  * [Open in a container](#open-in-a-container)

<!-- Regenerate with "pre-commit run -a markdown-toc" -->

<!-- tocstop -->

## Hooks

### Go Err Check

> Go-ified version of hook in [Bahjat's project](https://github.com/Bahjat/pre-commit-golang)

```yaml
repos:
  - repo: https://github.com/mrsimonemms/pre-commit-hooks
    rev: "" # Use the ref you want to point at
    hooks:
      - id: go-err-check
```

Use [kisielk/errcheck](https://github.com/kisielk/errcheck) to check that you
checked errors

### Go Fumpt

> Go-ified version of hook in [Bahjat's project](https://github.com/Bahjat/pre-commit-golang)

```yaml
repos:
  - repo: https://github.com/mrsimonemms/pre-commit-hooks
    rev: "" # Use the ref you want to point at
    hooks:
      - id: gofumpt
```

Use [mvdan/gofumpt](https://github.com/mvdan/gofumpt) to check your Go formatting

### Go Fmt Import

> Go-ified version of hook in [Bahjat's project](https://github.com/Bahjat/pre-commit-golang)

```yaml
repos:
  - repo: https://github.com/mrsimonemms/pre-commit-hooks
    rev: "" # Use the ref you want to point at
    hooks:
      - id: go-fmt-import
```

Use [goimports](https://pkg.go.dev/golang.org/x/tools/cmd/goimports) to format
your import statementstps://github.com/mvdan/gofumpt) to check your Go formatting

### Go Static Check

> Go-ified version of hook in [Bahjat's project](https://github.com/Bahjat/pre-commit-golang)

```yaml
repos:
  - repo: https://github.com/mrsimonemms/pre-commit-hooks
    rev: "" # Use the ref you want to point at
    hooks:
      - id: go-static-check
```

Use [staticcheck](https://staticcheck.dev) to lint your Go code

### Go Vet

> Go-ified version of hook in [Bahjat's project](https://github.com/Bahjat/pre-commit-golang)

```yaml
repos:
  - repo: https://github.com/mrsimonemms/pre-commit-hooks
    rev: "" # Use the ref you want to point at
    hooks:
      - id: go-vet
```

Use [go vet](https://pkg.go.dev/cmd/vet) to check your Go code

### License-Eye

```yaml
repos:
  - repo: https://github.com/mrsimonemms/pre-commit-hooks
    rev: "" # Use the ref you want to point at
    hooks:
      - id: license-eye
```

Add [SkyWalking-Eyes](https://github.com/apache/skywalking-eyes) and check that
the files have the correct headers implemented.

### Packer Format

```yaml
repos:
  - repo: https://github.com/mrsimonemms/pre-commit-hooks
    rev: "" # Use the ref you want to point at
    hooks:
      - id: packer-fmt
```

Run [Packer fmt](https://developer.hashicorp.com/packer/docs/commands/fmt)
command.

### Packer Validate

```yaml
repos:
  - repo: https://github.com/mrsimonemms/pre-commit-hooks
    rev: "" # Use the ref you want to point at
    hooks:
      - id: packer-validate
```

Run [Packer validate](https://developer.hashicorp.com/packer/docs/commands/validate)
command.

## Contributing

### Open in Gitpod

* [Open in Gitpod](https://gitpod.io/from-referrer/)

### Open in a container

* [Open in a container](https://code.visualstudio.com/docs/devcontainers/containers)
