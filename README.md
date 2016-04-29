OpenDevToolkit.net
==================

The Open Development Toolkit will act as a hub around open development, bringing together tools and
training materials in one place, with the aim of increasing use of open
development data and encouraging its use to inform decisions within the
sector.

More information on the [Open development Toolkit](http://opendevtoolkit.net)


## How to contribute

See the [guide](https://github.com/zararah/opendevtoolkit/blob/gh-pages/how-to-contribute.md) for details.


## Technology set-up

The repository is configured to use [Jekyll](https://jekyllrb.com/) to serve pages as a static site. Use of Jeckyll is supported by [GitHub pages](https://pages.github.com/).


## Running a local version

    # Clone the repository and navigate into the directory
    git clone https://github.com/zararah/opendevtoolkit.git
    cd opendevtoolkit

    # Set-up jekyll if not already installed (note this requires [RubyGems](https://rubygems.org/pages/download))
    gem install jekyll

    # Run an on-the-fly development version
    jekyll serve

    # Open a web browser and navigate to http://127.0.0.1:4000/


## Deploying to a web server
	
	# Download the repository as above, however output the static files rather than serving on the fly
	jekyll build

	# The static website files will now be in the '_site' directory
	# These can be transfered to your server, for example using ftp or scp
