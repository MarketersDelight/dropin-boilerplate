# dropin-boilerplate

A boilerplate of minimal setup for a drop in to start making your own drop-in.

### Basic requirements

*   The Dropin Package folder to be the name of the Drop-in.
*   Contains a `.php` file named the same as the folder, here is where your dropin initiated code starts, a simple drop in may only need this, a complex one may need other `includes` you can make these as you wish.
*   a must have is the `config.json` file which lets the Dropin manager know the details about this plugin.

```json
{
	"name" : "Drop in Name",
	"author" : "Name, Company",
	"version" : "1.0",
	"description" : "About the Drop in",
	"dropin_url" : "",
	"author_url" : "",
	"settings_url" : "index.php",
	"icon" : "dashicons-warning",
	"colors" : "#2e2e2e, #549948"
}
```

## Usage

Download this boilerplate:

Download this boilerplate: [https://github.com/MarketersDelight/dropin-boilerplate/archive/refs/tags/v1.0.0.zip](https://github.com/MarketersDelight/dropin-boilerplate/archive/refs/tags/v1.0.0.zip)

Edit the config.json and rename the package and php file and you're on your way.
