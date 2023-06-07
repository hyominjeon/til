# Components of URL

## Format
* `scheme://host[:port][/path][?query]`
* example: `https://www.ibm.com/docs/en/ctsfz/5.2?topic=concepts-components-url`

## Scheme
* the protocol
* not case-sensitive
* example: `http` or `https`

## Host
* host name that holds the resource
* not case-sensitive
* can be replaced by IP address
* example: `www.ibm.com`

## Port
* well-known port numbers are omitted from URL
* most servers use the well-known port numbers
* case-sensitive
* example: `80`

## Path
* specific resource in the host that client wants to access
* case-sensitive
* example: `docs/en/ctsfz/5.2`

## Query
* information that resource can use for some purpose, such as searching or data processing
* usually name and value pairs, each pair separated by `&`
* case-sensitive
* examples
  * `topic=concepts-components-url`
  * `term=bluebird&source=browser-search`
