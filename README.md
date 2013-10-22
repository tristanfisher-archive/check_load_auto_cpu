check_load_auto_cpu
===================

cpu load can be meaningless.  more so when it's not even related to the number of cores you have.  this fixes the latter, godspeed on the former

    usage: check_load_auto_cpu [-h] [-v] [-t [TIME]] [-c CRITICAL] [-w WARNING]
                               [-d]

    A Nagios-ready python script for giving system load as an average over the
    numberof CPUs in your machine.

    optional arguments:
      -h, --help            show this help message and exit
      -v, --version         Show script version and exit
      -t [TIME], --time [TIME]
                            Specify which interval you want (1,5,15 minute)
                            (default: 5)
      -c CRITICAL, --critical CRITICAL
                            The integer on which you want to alert critical
      -w WARNING, --warning WARNING
                            The integer on which you want to start warning
      -d, --debug           Debugging -- Output the alert details
