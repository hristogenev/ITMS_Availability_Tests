# ITMS Availability Tests
## Ready-to-run scripts for checking the ITMS service availability.

The repository contains everything needed (scripts, configuration and application files) for running a sample Espresso/XCUITest on any cloud. The only thing that you need to add to the config files is your cloud token.

## How to prepare and run the scripts

1. Clone the repo on your local machine or download as ZIP file and then extract.

``` git clone https://github.com/hristogenev/ITMS_Availability_Tests.git```

2. Make sure you have Gradle installed. If not -> https://gradle.org/install/
3. Make sure Gradle's bin folder is added to system $PATH environment variable.
  
4. Make all run files executable:
```chmod +x ./run*```

5. Make sure your cloud token is valid in all config files i.e. ```artefacts/configFile-espresso-real.json```

To run Perfecto Espresso test on real devices:

```./run-espresso-on-real-devices```

To run Perfecto Espresso test on virtual devices:

```./run-espresso-on-virtual-devices```

To run Perfecto Espresso test on real devices:

```./run-xcuitest-on-real-devices```

To run Perfecto Espresso test on virtual devices:

```./run-xcuitest-on-virtual-devices```
