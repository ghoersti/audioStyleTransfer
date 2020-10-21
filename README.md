# audioStyleTransfer


## Start Container
Depending on OS and preference run one of the following startup scripts.
* This will pull the correct version of tensorflow from docker hub.
* Build the image if it is not yet pulled 
* Create a container 
* Map the container to the root of where ever the repository was cloned 
### Power Shell
`docker run -v ${PWD}:/home/jovyan/work  -p 8888:8888  -p 6006:6006 jupyter/tensorflow-notebook:abdb27a6dfbb`

### Windows
`docker run -v %cd%:/home/jovyan/work  -p 8888:8888  -p 6006:6006 jupyter/tensorflow-notebook:abdb27a6dfbb`

### Linux
`docker run -v ${pwd}:/home/jovyan/work  -p 8888:8888  -p 6006:6006 jupyter/tensorflow-notebook:abdb27a6dfbb`




