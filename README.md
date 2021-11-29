ASG Persistence
================

Persisting things in Autoscaling Groups

**attach_volume.py** - attach an EBS volume by tag info. Script will search for a volume with given name in it's AZ and attach it for you

	usage: aws-volume-attach [-h] [--tag TAG] --value VALUE --attach_as ATTACH_AS

	Attach EBS Volume

	optional arguments:
	  -h, --help            show this help message and exit
	  --tag TAG             Tag key, defaults to Name
	  --value VALUE         The tag value to search for
	  --attach_as ATTACH_AS
	                        device path e.g. /dev/xvdb
