##### ARG
this instraction will supply few varibules at image creation 
ARG only instarction you can use before FROM instraction. ARG declared before, can't be accessed after FROM intsraction

##### using combain of ENV And ARG for best results
this is one type method using two types of instraction at one time to putt envorimet veriables inside the container to reference of ARG variables 
   like this 
ARG VERSION
FROM almalinux :${VERISON:-8}
ARG GREETING
ENV GREET=${GREETING}
RUN echo "$GREETING"   