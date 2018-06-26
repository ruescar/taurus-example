# Taurus example

This repository contains examples for the usage of [Taurus](http://gettaurus.org/) automation framework.

## Usage
    
    bzt simple.yml
    bzt simple.yml -report
    bzt simple.yml -gui
    bzt existing-script.yml -report
    bzt ramp-up.yml -report
    bzt ramp-up.yml blazemeter-config.yml -cloud -report -o modules.blazemeter.token=${BLAZEMETER_TOKEN}
    bzt -locations -o modules.blazemeter.token="${BLAZEMETER_TOKEN}"
    
    
    
