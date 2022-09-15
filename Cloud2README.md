In the API, create your instance creation request as you would normally, but when specifying a machineType value, use one of the following formats. Replace NUMBER_OF_CPUS with the number of CPUs and AMOUNT_OF_MEMORY_MB with the amount of memory you want. Provide memory in MB units.

For N1 machine types, use:
zones/ZONE/machineTypes/custom-NUMBER_OF_CPUS-AMOUNT_OF_MEMORY_MB

For N2 machine types, use:
zones/ZONE/machineTypes/n2-custom-NUMBER_OF_CPUS-AMOUNT_OF_MEMORY_MB

For N2D machine types, use:
zones/ZONE/machineTypes/n2d-custom-NUMBER_OF_CPUS-AMOUNT_OF_MEMORY_MB

For E2 machine types, use:
zones/ZONE/machineTypes/e2-custom-NUMBER_OF_CPUS-AMOUNT_OF_MEMORY_MB

For E2 shared-core custom machine types, use:
zones/ZONE/machineTypes/e2-custom-SHARED_CORE_MACHINE_SIZE-AMOUNT_OF_MEMORY_MB

URL would create an instance with 4 vCPUs and 5 GB (5120 MB) of memory:

zones/us-central1-f/machineTypes/custom-4-5120 

<!--
**Laharikaranam35/Laharikaranam35** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
