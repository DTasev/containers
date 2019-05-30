all: mantid_base

mantid1-build:
	sudo singularity build --sandbox mantid.sif Singularity
mantid1-workbench:
	sudo singularity run --nv -B /run --writable --app workbench mantid.sif
mantid1-mantidplot:
	sudo singularity run --nv -B /run --writable --app mantidplot mantid.sif
mantid1-shell:
	sudo singularity run --nv -B /run --writable --app shell mantid.sif/
