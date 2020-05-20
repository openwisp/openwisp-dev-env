# openwisp-dev-env
Automated development environment for OpenWISP, work in progress.

## First discussion

Summary:

- there's some consensus on using ansible to set up the development environment
- having an OpenWRT image ready to install on a VM or a device with all which is needed to work is OpenWISP would be very helpful (this overlaps with the plan of the next major release, which is good)
- the goals are:
  1. run the tool to get a full development env working out of the box and start contributing to openwisp
  2. run the tool periodically to update the openwisp modules according to one's configuration (if somebody is working on a fork & branch of some module, it may have to specify this in the configuration).
  
From the the [OpenWISP Mailing List](https://groups.google.com/d/msg/openwisp/kXnmasof_qs/_FtZG5WbAQAJ).
