# Color

`color` is a Go package that provides easy-to-use, colorful output for terminal
applications. It is simple to use and allows you to wrap your text with
vibrant, eye-catching colors that enhance readability and user experience. The
package provides functions for different colors including standard, bold,
underline, background, high intensity, and high intensity background colors.

## Installation

To use the color package in your Go code:

```bash
go get github.com/muxit-studio/color
```

## Usage

Import the color package into your Go file:

```go
import "github.com/muxit-studio/color"
```

Then use the various color functions to print colored text:

```go
fmt.Println(color.Red("This is red text"))
fmt.Println(color.Green("This is green text"))
```

You can also use the functions for bold, underline, and high intensity colors:

```go
fmt.Println(color.BGreen("This is bold green text"))
fmt.Println(color.UBlue("This is underlined blue text"))
fmt.Println(color.IYellow("This is high intensity yellow text"))
```

## Contributions

Contributions to the `color` package are very welcome! Feel free to submit a Pull
Request or open an Issue. License

`color` is available under the MIT License.
