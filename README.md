# SmartMet International Documentation
Documentation for SmartMet systems that are deployed internationally.

## SmartMet Data Processing Server
* Rocky Linux 8 minimal
* Install Guide https://github.com/fmidev/smartmet-install

### Data
* Add GFS https://github.com/fmidev/smartmet-data-gfs
* Add GFS https://github.com/fmidev/smartmet-data-gem
* Add SYNOP  https://github.com/fmidev/smartmet-data-gts-synop
* Add SOUNDING  https://github.com/fmidev/smartmet-data-gts-sounding
  

### Cron
* Use /smartmet/cnf/cron/cron.d to run scheduled scripts. Do not use smartmet users crontab.

### Triggers
* Use /smartmet/cnf/triggers.d to run scripts when some file or directory updates
* Trigger file name is the path to triggering directory, in file name replace / with :

### NOTES
* Do not modify system provided files, they may be overwritten with package updates

## Kubernetes Cluster
* RKE2 3 node cluster
* Install Guide https://docs.rke2.io/install/ha

## Instal Guides for SmartMet Workstation software
* Smartmet Workstation [Install Guide](/Install/SmartMet%20Workstation.md)
* Smartmet Alert [Install Guide](/Install/SmartMet%20Alert.md)
