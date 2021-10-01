# Calculations progress
For filtering in in [Mlflow](http://acireale.iiar.pwr.edu.pl/mlflow/) use the following template

	params.agent = 'acs2ga' and params.hash = 'sha256' and params.modulo = '8'


# Done

	01 make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=6 -P hash=md5 -P agent=acs2 -P modulo=8"
	02 make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=3 -P hash=sha256 -P agent=acs -P modulo=16"
	03 make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=20 -P hash=md5 -P agent=acs2ga -P modulo=4"
	04 make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=3 -P hash=md5 -P agent=acs2 -P modulo=4"
	05 make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=3 -P hash=sha256 -P agent=acs2ga -P modulo=32"
	06 make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=6 -P hash=sha256 -P agent=acs -P modulo=4"
	07 make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=20 -P hash=sha256 -P agent=yacs -P modulo=4"
	08 make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=3 -P hash=md5 -P agent=acs2 -P modulo=32"
	09 make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=20 -P hash=md5 -P agent=acs -P modulo=32"
	10 make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=3 -P hash=sha256 -P agent=acs2 -P modulo=32"
	11 make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=3 -P hash=sha256 -P agent=acs2 -P modulo=8"
	12 make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=6 -P hash=md5 -P agent=acs2 -P modulo=32"
	13 make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=11 -P hash=sha256 -P agent=yacs -P modulo=4"
	14 make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=11 -P hash=md5 -P agent=yacs -P modulo=8"
	15 make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=6 -P hash=md5 -P agent=yacs -P modulo=16"
	16 make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=20 -P hash=md5 -P agent=acs -P modulo=32"
	17 make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=20 -P hash=md5 -P agent=yacs -P modulo=8"
	18 make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=3 -P hash=md5 -P agent=acs2ga -P modulo=4"
	19 make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=6 -P hash=md5 -P agent=acs2 -P modulo=16"
	20 make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=11 -P hash=md5 -P agent=yacs -P modulo=16"
	21 make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=3 -P hash=md5 -P agent=acs2ga -P modulo=32"
	22 make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=3 -P hash=md5 -P agent=acs -P modulo=8"
	23 make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=11 -P hash=md5 -P agent=acs2ga -P modulo=4"
	24 make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=6 -P hash=md5 -P agent=acs2ga -P modulo=8"
	25 make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=11 -P hash=md5 -P agent=acs2 -P modulo=32"
	26 make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=11 -P hash=md5 -P agent=yacs -P modulo=4"
	27 make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=11 -P hash=md5 -P agent=acs2 -P modulo=16"
	28 make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=20 -P hash=md5 -P agent=yacs -P modulo=16"
	29 make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=6 -P hash=sha256 -P agent=yacs -P modulo=32"
	30 make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=6 -P hash=sha256 -P agent=yacs -P modulo=16"
	31 make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=11 -P hash=sha256 -P agent=yacs -P modulo=16"
	32 make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=20 -P hash=sha256 -P agent=yacs -P modulo=16"
	33 make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=11 -P hash=sha256 -P agent=acs2ga -P modulo=16"
	34 make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=20 -P hash=sha256 -P agent=acs2ga -P modulo=8"

## In progress (acireale)

	1 make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=20 -P hash=md5 -P agent=acs2 -P modulo=16"
	2 make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=20 -P hash=sha256 -P agent=acs2 -P modulo=16"
	3 make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=11 -P hash=md5 -P agent=acs2 -P modulo=4"
	4 make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=20 -P hash=sha256 -P agent=acs2 -P modulo=8"
	5 make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=20 -P hash=sha256 -P agent=acs2 -P modulo=4"

## In progress (prometheus)
Modify the `slurm/slurm.sh` file relevant parameters to run the computations.

	PARAMETERS[1]="-P trials=250000 -P rmpx-size=11 -P hash=sha256 -P agent=yacs -P modulo=8"
	PARAMETERS[2]="-P trials=250000 -P rmpx-size=3 -P hash=sha256 -P agent=yacs -P modulo=8"
	PARAMETERS[3]="-P trials=250000 -P rmpx-size=11 -P hash=sha256 -P agent=acs2 -P modulo=16"
	PARAMETERS[4]="-P trials=250000 -P rmpx-size=3 -P hash=sha256 -P agent=acs2ga -P modulo=16"
	PARAMETERS[5]="-P trials=250000 -P rmpx-size=11 -P hash=sha256 -P agent=acs -P modulo=16"
	PARAMETERS[6]="-P trials=250000 -P rmpx-size=3 -P hash=sha256 -P agent=acs2 -P modulo=4"
	PARAMETERS[7]="-P trials=250000 -P rmpx-size=6 -P hash=sha256 -P agent=acs2 -P modulo=16"
	PARAMETERS[8]="-P trials=250000 -P rmpx-size=6 -P hash=sha256 -P agent=acs2 -P modulo=4"
	PARAMETERS[9]="-P trials=250000 -P rmpx-size=6 -P hash=sha256 -P agent=acs2 -P modulo=32"
	PARAMETERS[10]="-P trials=250000 -P rmpx-size=11 -P hash=sha256 -P agent=acs2ga -P modulo=8"
	PARAMETERS[10]="-P trials=250000 -P rmpx-size=11 -P hash=sha256 -P agent=acs2ga -P modulo=8"
	PARAMETERS[11]="-P trials=250000 -P rmpx-size=3 -P hash=sha256 -P agent=yacs -P modulo=16"
	PARAMETERS[12]="-P trials=250000 -P rmpx-size=11 -P hash=sha256 -P agent=acs2 -P modulo=4"
	PARAMETERS[13]="-P trials=250000 -P rmpx-size=3 -P hash=sha256 -P agent=acs2ga -P modulo=8"
	PARAMETERS[14]="-P trials=250000 -P rmpx-size=6 -P hash=sha256 -P agent=acs2ga -P modulo=8"
	PARAMETERS[15]="-P trials=250000 -P rmpx-size=3 -P hash=sha256 -P agent=acs2 -P modulo=16"
	PARAMETERS[16]="-P trials=250000 -P rmpx-size=11 -P hash=sha256 -P agent=acs2 -P modulo=8"
	PARAMETERS[17]="-P trials=250000 -P rmpx-size=11 -P hash=sha256 -P agent=acs2 -P modulo=32"
	PARAMETERS[18]="-P trials=250000 -P rmpx-size=20 -P hash=sha256 -P agent=acs2ga -P modulo=16"
	PARAMETERS[19]="-P trials=250000 -P rmpx-size=6 -P hash=sha256 -P agent=acs2ga -P modulo=16"
	PARAMETERS[20]="-P trials=250000 -P rmpx-size=3 -P hash=sha256 -P agent=acs -P modulo=32"



### Selected next tasks (queue)

	PARAMETERS[16]="-P trials=250000 -P rmpx-size=20 -P hash=sha256 -P agent=acs -P modulo=32"
	make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=3 -P hash=md5 -P agent=acs -P modulo=32"
	make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=20 -P hash=md5 -P agent=yacs -P modulo=32"
	make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=11 -P hash=md5 -P agent=acs -P modulo=32"
	make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=11 -P hash=md5 -P agent=acs2ga -P modulo=32"
	make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=11 -P hash=md5 -P agent=acs2ga -P modulo=16"
	make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=20 -P hash=md5 -P agent=acs2ga -P modulo=8"
	make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=6 -P hash=md5 -P agent=acs -P modulo=32"
	make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=3 -P hash=md5 -P agent=acs2ga -P modulo=16"
	make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=3 -P hash=md5 -P agent=yacs -P modulo=4"
	make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=6 -P hash=md5 -P agent=yacs -P modulo=32"
	make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=6 -P hash=md5 -P agent=acs2 -P modulo=4"
	make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=11 -P hash=md5 -P agent=acs -P modulo=16"
	make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=11 -P hash=md5 -P agent=acs -P modulo=4"
	make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=3 -P hash=md5 -P agent=yacs -P modulo=16"
	make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=11 -P hash=md5 -P agent=acs2ga -P modulo=8"
	make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=3 -P hash=md5 -P agent=acs2 -P modulo=8"
	make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=6 -P hash=md5 -P agent=acs -P modulo=8"
	make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=3 -P hash=md5 -P agent=yacs -P modulo=32"
	make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=20 -P hash=md5 -P agent=acs -P modulo=16"
	make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=20 -P hash=md5 -P agent=yacs -P modulo=4"
	make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=20 -P hash=sha256 -P agent=acs2 -P modulo=32"
	make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=20 -P hash=md5 -P agent=acs2ga -P modulo=32"
	make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=11 -P hash=sha256 -P agent=acs -P modulo=4"
	make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=3 -P hash=md5 -P agent=acs2ga -P modulo=8"
	make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=20 -P hash=md5 -P agent=acs2 -P modulo=4"
	make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=3 -P hash=sha256 -P agent=acs -P modulo=4"
	make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=6 -P hash=md5 -P agent=yacs -P modulo=8"
	make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=11 -P hash=md5 -P agent=acs2 -P modulo=8"
	make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=6 -P hash=md5 -P agent=acs -P modulo=16"
	make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=20 -P hash=md5 -P agent=acs2 -P modulo=8"
	make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=20 -P hash=md5 -P agent=acs2 -P modulo=32"
	make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=6 -P hash=sha256 -P agent=acs -P modulo=32"
	make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=11 -P hash=md5 -P agent=yacs -P modulo=32"
	make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=20 -P hash=sha256 -P agent=acs -P modulo=8"
	make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=6 -P hash=md5 -P agent=acs2ga -P modulo=16"
	make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=3 -P hash=sha256 -P agent=yacs -P modulo=4"
	make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=20 -P hash=md5 -P agent=acs2ga -P modulo=16"
	make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=6 -P hash=sha256 -P agent=yacs -P modulo=4"
	make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=6 -P hash=md5 -P agent=acs2ga -P modulo=32"
	make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=6 -P hash=sha256 -P agent=acs2ga -P modulo=4"
	make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=20 -P hash=sha256 -P agent=yacs -P modulo=32"
	make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=20 -P hash=sha256 -P agent=acs -P modulo=16"
	make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=20 -P hash=md5 -P agent=acs -P modulo=8"
	make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=20 -P hash=md5 -P agent=acs -P modulo=4"
	make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=11 -P hash=sha256 -P agent=acs -P modulo=32"
	make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=6 -P hash=md5 -P agent=acs2ga -P modulo=4"
	make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=3 -P hash=md5 -P agent=acs -P modulo=16"
	make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=6 -P hash=sha256 -P agent=yacs -P modulo=8"
	make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=6 -P hash=md5 -P agent=acs -P modulo=4"
	make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=3 -P hash=md5 -P agent=acs2 -P modulo=16"
	make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=11 -P hash=md5 -P agent=acs -P modulo=8"
	make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=6 -P hash=sha256 -P agent=acs -P modulo=16"
	make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=20 -P hash=sha256 -P agent=yacs -P modulo=8"
	make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=6 -P hash=sha256 -P agent=acs2ga -P modulo=32"
	make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=20 -P hash=sha256 -P agent=acs2ga -P modulo=4"
	make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=3 -P hash=sha256 -P agent=acs -P modulo=8"
	make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=3 -P hash=md5 -P agent=acs -P modulo=4"
	make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=3 -P hash=sha256 -P agent=acs2ga -P modulo=4"
	make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=20 -P hash=sha256 -P agent=acs2ga -P modulo=32"
	make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=6 -P hash=sha256 -P agent=acs -P modulo=8"
	make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=11 -P hash=sha256 -P agent=acs2ga -P modulo=32"
	make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=11 -P hash=sha256 -P agent=acs -P modulo=8"
	make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=11 -P hash=sha256 -P agent=acs2ga -P modulo=4"
	make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=20 -P hash=sha256 -P agent=acs -P modulo=4"
	make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=11 -P hash=sha256 -P agent=yacs -P modulo=32"
	make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=6 -P hash=sha256 -P agent=acs2 -P modulo=8"



## To fix
	make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=3 -P hash=md5 -P agent=yacs -P modulo=8"
	make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=6 -P hash=md5 -P agent=yacs -P modulo=4"
	make docker_run_experiments PARAMS="-P trials=250000 -P rmpx-size=3 -P hash=sha256 -P agent=yacs -P modulo=32"

