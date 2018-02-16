## PowerShell.docset

A script to build a PowerShell docset for [Dash](http://kapeli.com/dash).

It currently documents the 4,900+ `cmdlets` which are listed in the
`Cmdlet Reference` pages listed in `indexes.yaml`.

## Dependencies

Building the docset requires `Python` and `pip`. The dependencies are:

- `BeautifulSoup4`
- `PyYAML`
- `requests`

### Manual

It takes 70-90 minutes to build and the end result is a little over 100 MB
uncompressed.

Then open the Dash application and add the `PowerShell.docset` file.

## License

The docset is dedicated to the public domain. Refer to the `LICENSE` file for
more information.
