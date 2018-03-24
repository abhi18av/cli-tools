singularity build --writable cli-tools.img Singularity

# This one doesn't give errors
singularity build --sandbox cli-tools.img Singularity 

singularity shell --writable cli-tools.img

## Now it can easily install and uninstall stuff

singularity exec --writable cli-tools.img yum install epel-release


- Binding the local folder with the singularity image
http://singularity.lbl.gov/docs-mount
