# How to compile
### go into the MatiArchISO folder
### use a docker container or vm with arch linux and install archiso with
``` pacman -S archiso ``` 
### go into the MatiArchISO folder and write 
``` sudo mkarchiso -v -r -w ./work/ -o ./output/ releng ```
### wait until it compiles (aproximately 10 minutes depending on the processor)
### then open the output folder and the iso should be there to install anywhere
