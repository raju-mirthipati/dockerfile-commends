##### ONBUILD 
-> this instarction is used to set some hardguide lines to image; we can control users they have to refrence our image as base image
-> this instarction not excute on mother builder

##### formet
FROM almalinux
ONBUILD ADD simple.txt /tem  ->
                               when we build this image the container doest add txt" file in container 
                             -> 
                               the other hand users excute this dockerfile the file will be added in the tem/ directory  