## Purpose

Collection of asset files I like to use that can be plugged into the public folder of a fresh Rails install.  This comes with a partial view that contains the pre-generated links to the files included.

## Usage

Fresh Rails App:
	cd into your public folder
clone this repo:
	git clone https://github.com/bradministrator/assets

	this creates the assets folder inside public along with the repo files

move the header link file to your layouts folder:
	mv _asset_helper_stub.html.erb ../app/views/layouts/

edit your app/views/layouts/application.html.erb (or whichever layout file you configured your app to use) and in the head section include the following line:
	<%= render partial: '/layouts/_asset_helper_stub.html.erb %>

## License

use it, abuse it?

You are subject to the licenses of the libraries contained herein
