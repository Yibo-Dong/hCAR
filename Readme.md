## Readme

This repository keeps the artifacts for Hybrid CAR.

### Structure

```
.
├── benchmark 				// the benchmark we use
    ├── xxx.aig
    └── ...
├── code 					// source code 
    ├── caramel.zip			// our version of CAR, on top of simpleCAR, but in iterative style
    └── combineWithSOTA.zip // these solutions with Local implemented
        ├── BAC
        ├── BICAR
        └── KCAR
```

### Note

A few log files may be deprecated, because of the error in the pbs system on cluster :

> "ssh: connect to host admin port 22: Connection refused".

This is because the running time is long, but this does not really affect the processes running. When this happen, we will seek the server log and get the actual time printed. Meanwhile, due to anonymity, we are not able to provide the raw server logs which have rich personal information.


Besides, We're unable to provide the logs of BICAR here, due to its excessive enormous size.
For example, the size of `bicar_local(2)/pdtvisvsa16a29.log` is 59.97GB.  This may due to the heavy printing happened during BMC, which is written by authors of BICAR. We cannot find a possible way to upload it. We could only give the `.res` files here.
