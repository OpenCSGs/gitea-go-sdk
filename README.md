# Gitea SDK for Go

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Release](https://raster.shields.io/badge/dynamic/json.svg?label=release&url=https://gitea.com/api/v1/repos/gitea/go-sdk/releases&query=$[0].tag_name)](https://gitea.com/gitea/go-sdk/releases)
[![Join the chat at https://img.shields.io/discord/322538954119184384.svg](https://img.shields.io/discord/322538954119184384.svg)](https://discord.gg/Gitea)
[![Go Report Card](https://goreportcard.com/badge/code.gitea.io/sdk)](https://goreportcard.com/report/code.gitea.io/sdk)
[![GoDoc](https://godoc.org/code.gitea.io/sdk/gitea?status.svg)](https://godoc.org/code.gitea.io/sdk/gitea)

This project acts as a client SDK implementation written in Go to interact with the Gitea API implementation. For further informations take a look at the current [documentation](https://pkg.go.dev/code.gitea.io/sdk/gitea).

Note: function arguments are escaped by the SDK.

## Use it

```go
import "github.com/OpenCSGs/gitea-go-sdk/gitea"
```

## Version Requirements
 * go >= 1.13
 * gitea >= 1.11

## Contributing

Fork -> Patch -> Push -> Pull Request

## Authors

* [Maintainers](https://github.com/orgs/go-gitea/people)
* [Contributors](https://github.com/go-gitea/go-sdk/graphs/contributors)

## License

This project is under the MIT License. See the [LICENSE](LICENSE) file for the full license text.
