# ds-config

some shared configuration files

### using the latest and greatest (unstable) version

This is the location of the current tip of the develop branch:

https://raw.githubusercontent.com/DillonSoftware/ds-config/develop/checkstyle.xml

### creating a new version

We're trying to use git flow to manage the versions here.

Here are the steps to create a new release (1.0.1 in this example):

	git flow release start 1.0.1
	git flow release finish 1.0.1
	git push --all && git push --tags

After that's all done, you can refer to the new version as:

https://raw.githubusercontent.com/DillonSoftware/ds-config/1.0.1/checkstyle.xml
