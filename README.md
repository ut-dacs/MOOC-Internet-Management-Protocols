# MOOC-Internet-Management-Protocols
Configuration and support files for the Nagios exercises of the MOOC Internet Management Protocols.
See: https://learnintsec.org/

The following files are for Vagrant installation:
- vagrantfile: For initial Ubuntu VM setup
- server-provision: To install Nagios, Apache and SNMP within the VM
 
The following files are for Nagios:
- nagios.cfg: Overrides the standard Nagios configuration file to disable localhost.cfg
- nagioshost.cfg: replaces localhost.cfg. Only monitors load, ssh and http
- my_tests.cfg: to define your private (test) command, host and service definitions
- exercise.cfg: to enter the answers for the exercises. This content must be uploaded to the MOOC platform
