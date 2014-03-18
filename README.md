perfsonar-scripts
=================

A collection of little scripts useful for perfSonar.

mirror-perfsonar-configs.sh
--------------------------
A script to mirror a set of configuration files from a central repository to a new location. This
is useful mainly when you have a perfSonar host that is not on a network that can access the config
files.

To deploy the script:

    curl https://raw.githubusercontent.com/igable/perfsonar-scripts/master/mirror-perfsonar-configs.sh -o /etc/cron.hourly/mirror-perfsonar-configs.sh
    chmod ugo+x /etc/cron.hourly/mirror-perfsonar-configs.sh

edit the output directory and temp directory:

    vim /etc/cron.hourly/mirror-perfsonar-configs.sh


Authors
---------
Ian Gable
Shawn McKee
