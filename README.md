# tourofx

Like [Tour of Go](https://go.dev/tour/) but you can use other language

## Usage

- Update the content in [_content](_content) folder
  + Add new lessons in [`content/tour`](content/tour)
  + Update some JS files. Checkout the part with MODIFYME inside `_content` folder: `grep -R -w MODIFYME _content`
- Run the tour server: `go run main.go`

## Notes

The code is from https://github.com/golang/website
