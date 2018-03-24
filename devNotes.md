singularity build --writable cli-tools.img Singularity

# This one doesn't give errors
singularity build --sandbox cli-tools.img Singularity 

singularity shell --writable cli-tools.img
