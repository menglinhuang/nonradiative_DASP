# Nonradiative_DASP
# Description
For DASP users, the files in C_N and Ge_Zn are the input files needed for nonradiative capture calculation. These files are the output results of DASP-DEC for defect energetics, with formation energies and transition levels printed in `defect.log`. Taking C_N as an example, what you need to do is:

- cd C_N/
- properly modify `Job Scheduling` part in `dasp.in`, so that DASP can do automated calculations with one click.
- execute `dasp 5`, and DASP will do all the calculations with the aid of job dependencies provided by pbs/slurm.
- wait until the calculated results are saved.

You will find the results of configuration coordinate diagram and capture coefficient.

<img src="https://github.com/menglinhuang/nonradiative_DASP/blob/main/images/cc.png" width=375>
<img src="https://github.com/menglinhuang/nonradiative_DASP/blob/main/images/capture.png" width=375>

# Reference
Please consider citing: Huang et al. Journal of Semiconductors, 4, 042101 (2022)

The documentation can be loaded from: http://hzwtech.com/files/software/DASP/html/index.html
