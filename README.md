# TACAS-22-Artifact-Evaluation

This is the pre-acceptance artifact for the research paper "Efficient Translation From Limit Deterministic Büchi Automata to Deterministic ω-Automata".

In this artifact, we provide the source code for COLA, the tool implementing the determinization algorithm presented in the paper, and the executables for the tools SPOT and OWL we compare with.
The execution of the tools on the benchmark files is managed by benchexec; thus the artifact contains all files needed to execute the benchmarks, together with scripts and TeX files used to generate the plots presented in the paper, either in the main part or in the appendix.

The experimental results presented in the paper have been obtained by running the tools on a desktop machine with more memory than that assigned to the TACAS22 virtual machine (see the paper for details). Thus we had to adapt the resource constraints for benchexec to fit the virtual machine settings.
