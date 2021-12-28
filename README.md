# chia-fail2ban
fail2ban module for the chia node to try and lessen the impact of dust storms by temporarily banning non functional or slower peers, this will ensure the introducer keeps giving you fresh peers that hopefully work better than the ones you are currently connected to.

please only activate this during a dust storm as it will indiscriminately ban peers that are on a lower peak than you or have any network issues at all. 
running this during normal times makes you a very bad netizen.

modify config.yaml
log_level = WARNING to DEBUG

modify jail.d/chia.conf to ensure the path to the log file is correct
