## nemex

[UNOFFICIAL] A tiny app to track and curate ideas and projects. It’s self-hosted and based on markdown.    

More info: [nemex.io](http://nemex.io)


### About the development

The official nemex project doesn't seem to be getting much attention, so this project is intended to make general improvements to nemex for anyone who might find it useful.

### Usage

Change the username and password in the `config.php` and upload all files to your server. 

nemex expects to have a `projects/` directory to upload and save all files into. This directory needs to be writeable by PHP. On many shared hosters, this means you'll have to set the chmod to 0777. Also see the `FILE_CREATION_MODE` setting in the config.php.

