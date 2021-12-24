# chia-fail2ban
fail2ban module for the chia node to try and lessen the impact of dust storms by temporarily banning non functional peers, this will ensure the introducer keeps giving you fresh peers that hopefully work better than the ones you are currently connected to

modify config.yaml
log_level = WARNING to INFO

modify jail.d/chia.conf to ensure the path to the log file is correct
