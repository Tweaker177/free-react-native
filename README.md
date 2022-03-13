nicTemplates to be made for React Native develoment and deployment on ios devices 
============

A set of NIC templates that I hope to build on to make a new one that allows for creation of React Native projects directly from theos on a jailbroken iPhone or iPad, or through ssh to one from a computer.  so far they are unmodified from original theos github.

# Templates included:

- Application (Objective-C and Swift)

Templates planned to be included:

-React Application
-React Library
-React tool

# Usage:

## Interactive

	$ $THEOS/nic.pl

- Select the desired template.
- Input the values for each query

## Programmatic

	$ nic.pl -p "package.name" -n "ProjectName" -u "User name" --nic template.nic.tar

# Building:

	$ build.sh

------------

Tweak template is a modified version of the template found in https://github.com/DHowett/theos/tree/master/templates/iphone/tweak.nic.tar.

libactrivator listener template is a modified version of https://github.com/rpetrich/libactivator/tree/master/example.t

application_swift template is a modified version of https://github.com/theos/theos/tree/master/templates/ios/theos/application.nic.tar

tool_swift template is a modified version of https://github.com/theos/theos/tree/master/templates/ios/theos/tool.nic.tar
