# Go HTTP Headers Package

This package provides a collection of common HTTP header constants. These constants are useful for setting HTTP request or response headers and can be used in various Go-based web applications and HTTP-related scenarios.

## Features

- Contains constants for common HTTP headers like `Content-Type`, `User-Agent`, `Authorization`, and more.
- Simple installation and easy to use in other Go projects.

## Installation

To install the package, use the following command:

```shell
go get github.com/skodnik/go-httpheaders
```

You can also install a specific version or the latest version with go install:

```shell
go install github.com/skodnik/go-httpheaders@latest
```

## Usage

To use the HTTP header constants in your Go project, import the package and reference the constants by name. Here's an example of how you might use this package to set HTTP request headers:

```go
package main

import (
    "fmt"
    "github.com/skodnik/go-httpheaders/httpheaders"
)

func main() {
    fmt.Println("HTTP Header for Content-Type:", httpheaders.ContentType)
    fmt.Println("HTTP Header for User-Agent:", httpheaders.UserAgent)
    fmt.Println("HTTP Header for Authorization:", httpheaders.Authorization)
}
```

## Contributing

Contributions are welcome! If you have suggestions for additional HTTP header constants or other improvements, please open an issue or submit a pull request.

## License

[GNU General Public License v3](LICENSE)

## Disclaimer

The author is not liable for any claims, losses, or other liabilities arising from or related to the use, distribution, or other handling of this software.