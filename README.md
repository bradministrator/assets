## Purpose

Collection of asset files I like to use that can be plugged into the public folder of a fresh Rails install.  This comes with a partial view that contains the pre-generated links to the files included.

## Usage
Tested using rails 4.2.1

In a Fresh Rails App:
```bash
	cd public
```
clone this repo:
```bash
	git clone https://github.com/bradministrator/assets
```

move the header link file to your layouts folder:
```bash
	mv _asset_helper_stub.html.erb ../app/views/layouts/
```

edit your app/views/layouts/application.html.erb (or whichever layout file you configured your app to use) and in the head section include the following line:
```erb
	<%= render partial: '/layouts/_asset_helper_stub.html.erb %>
```

## License

use it, abuse it?

You are subject to the licenses of the libraries contained herein
