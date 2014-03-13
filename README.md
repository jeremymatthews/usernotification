usernotification
================
This command-line tool can be used to create user-based notifications from the Notification Center in 10.7 (or greater)

Install
-------
Clone repository and install `/usr/local/bin/usernotification`

	git clone https://github.com/jeremymatthews/usernotification.git
	cd usernotification
	sudo xcrun xcodebuild clean install DSTROOT=/

Usage
-----

	Usage: usernotification [-identifier <identifier>] [-title <title>] [-subtitle <subtitle>] [-informativeText <text>]
	
	Options:
	    -identifier NAME        some existing app identifier(default: com.apple.finder)
	    -title TEXT             title text
	    -subtitle TEXT          subtitle text
	    -informativeText TEXT   informative text

License
-------

Coming soon.
