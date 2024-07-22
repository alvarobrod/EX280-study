# Enable developer self-service

1. Create a project `template-builder`  

2. The workloads in the project cannot request a total of more than 1 GiB of RAM, and they cannot use more than 2 GiB of RAM.  

3. The user who requests the project has the default *admin* role binding.  

4. Each workload in the project has the following properties:
  
```
Default memory request of 256 MiB  
  
Default memory limit of 512 MiB  
  
Minimum memory request of 128 MiB  
  
Maximum memory usage of 1 GiB  
```

5. Create a project template definition with the same properties  

6. Create and configure the project template    

7. Create a project to make sure it works as intended and check `resourcequotas` and `limitranges` to see if present
