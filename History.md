0.5.1 / 2015-01-30
------------------
* Fix compatibility issue with bundler. #8
* Add a check for the current working directory on boot2docker / docker-machine. #7


0.5.0 / 2015-12-25
------------------
* Add cross ruby version 2.3.0.
* Replace RVM ruby version 2.2.2 with 2.3.0 and set it as default.
* Add support for docker-machine in addition to deprecated boot2docker.
* Drop runtime support for ruby-1.8. Cross build for 1.8 is still supported.


0.4.3 / 2015-07-09
------------------
* Ensure the user and group names doesn't clash with names in the image.


0.4.2 / 2015-07-04
------------------
* Describe use of environment variables in README.
* Provide RCD_IMAGE, RCD_HOST_RUBY_PLATFORM and RCD_HOST_RUBY_VERSION to the container.
* Add unzip tool to docker image.


0.4.1 / 2015-07-01
------------------
* Make rake-compiler-dock compatible to ruby-1.8 to ease the usage in gems still supporting 1.8.
* Use separate VERSION and IMAGE_VERSION, to avoid unnecessary image downloads.
* Finetune help texts and add FAQ links.


0.4.0 / 2015-06-29
------------------
* Add support for OS-X.
* Try boot2docker init and start, when docker is not available.
* Add colorized terminal output.
* Fix usage of STDIN for sending data/commands into the container.
* Limit gemspec to ruby-1.9.3 or newer.
* Allow spaces in user name and path on the host side.


0.3.1 / 2015-06-24
------------------
* Add :sigfw and :runas options.
* Don't stop the container on Ctrl-C when running interactively.
* Workaround an issue with sendfile() leading to broken files when using boot2docker on Windows.


0.3.0 / 2015-06-17
------------------
* Workaround an issue with broken DLLs when building on Windows.
* Print docker command line based on verbose flag of rake.
* Add check for docker and instructions for install.


0.2.0 / 2015-06-08
------------------
* Add a simple API for running commands within the rake-compiler-dock environment.
* Respect ftp, http and https_proxy settings from the host.
* Add wget to the image


0.1.0 / 2015-05-27
------------------
* first public release
