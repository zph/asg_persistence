aws_stuff
=========

General AWS scripts

attach_volume.py - attach an EBS volume by tag info. Script will search for a volume with given name in it's AZ and attach it for you

	usage: attach_volume.py [-h] [--tag TAG] --value VALUE --attach_as ATTACH_AS
	
	Attach EBS Volume
	
	optional arguments:
	  -h, --help            show this help message and exit
	  --tag TAG
	  --value VALUE
	  --attach_as ATTACH_AS
	                        device path e.g. /dev/xvdb
	
