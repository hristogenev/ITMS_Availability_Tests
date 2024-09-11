# ITMS_Availability_Tests
Ready-to-run scripts for checking the ITMS service availability.

After cloning the repo, 
1. make sure you "chmod" the executable files:
```chmod +x ./run*```
2. Make sure your cloud token is valid in any of the config files i.e. ```artefacts/configFile-espresso-real.json```

To run Perfecto Espresso test on real devices:

```./run-espresso-on-real-devices```

To run Perfecto Espresso test on virtual devices:

```./run-espresso-on-virtual-devices```

To run Perfecto Espresso test on real devices:

```./run-xcuitest-on-real-devices```

To run Perfecto Espresso test on virtual devices:

```./run-xcuitest-on-virtual-devices```
