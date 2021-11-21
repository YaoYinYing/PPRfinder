# PPRfinder java build
_built by Yinying Yao_


## Build the project
class files were build in IntelliJ IDEA

make jar file:
```shell
cd <PPRfinder-dir>/out/production/PPRfinder
jar -cvfe PPRfinder.jar pprfinder.PPRfinder pprfinder resources
```

test the jar executable
```shell
java -jar PPRfinder.jar
```

output:
```text
Program: PPRfinder (for characterising PPR motifs in proteins)
Version: 1.0
Usage: java -jar PPRfinder.jar <orfs.fasta> <orfs.domt>
<orfs.fasta>: fasta file of protein sequences
<orfs.domt>: domain table output from running hmmsearch on <orfs.fasta> with PPR HMMs
```
