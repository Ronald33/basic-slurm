# basic-slurm

Primero cargue el modulo openmpit con el siguiente comando:

module load openmpi/4.1.0

A continuación genere el ejecutable con el siguiente comando:

mpicc hello.c -o hello

Finalmente envie el job:

sbatch job.slrm

