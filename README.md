# ITMS_Availability_Tests
Ready-to-run scripts for checking the ITMS service availability.

After cloning the repo, make sure:
1. You have Gradle installed.
2. Gradle's bin folder is added to system $PATH environment variable.
3. Make run files executable:
```chmod +x ./run*```
2. Your cloud token is valid in any of the config files i.e. ```artefacts/configFile-espresso-real.json```

To run Perfecto Espresso test on real devices:

```./run-espresso-on-real-devices```

To run Perfecto Espresso test on virtual devices:

```./run-espresso-on-virtual-devices```

To run Perfecto Espresso test on real devices:

```./run-xcuitest-on-real-devices```

To run Perfecto Espresso test on virtual devices:

```./run-xcuitest-on-virtual-devices```
