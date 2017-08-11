# home123

groupId com.highbrow.apps
artifactId home123
version 1.0-SNAPSHOT

App Structure
ourapp
web - Meteor application 1
	client - Web specific client
	server - Server code which works with web and mobile client
	lib - Lib code which works with web and mobile client
mobile - Meteor application 2
	client - Cordova specific client
	server - Symlink of ../web/server
	lib - Symlink of ../web/lib
staticweb - Meteor application 3
	client - code that can runs on desktop or mobile browser
	server - Server code which works with desktop or mobile browser
	lib - Lib code which works with desktop or mobile browser

