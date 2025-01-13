# tourofx

Like [Tour of Go](https://go.dev/tour/) but you can use other language

## Usage

- Update the content in [tour/_content](tour/_content) folder
  + Add new lessons in [`tour/_content/tour`](tour/_content/tour)
  + Update some JS files. Checkout the part with MODIFYME inside `_content` folder: `grep -R -w MODIFYME tour/_content`
- Run the tour server: `go run main.go`

## Notes

The code is from https://github.com/golang/website
