ENTRYPOINT instraction use to run container same as CMD 
but there are few deffrence from CMD 
1. ENTRYPONT can't overide the commend
2. Where as CMD is overide the commend
3. when we override the ENTRYPOINT commend this can append the ENTRYPONT and throw an error
4. for best practice we use CMD and ENTRYPOINT two intractions with one Dockerfile 

######
formet
######

CMD <[orgiment-for-ENTRYPOINT]>
ENTRYPOINT <[commends-for-docker-container]>

      so in this case we want execute the CMD and ENTRYPOINT as well. by refurence to this exampile :-
         ENTRYPONT excute defalt commends 
         CMD supply the argumets to the ENTRYPONT
 So when we want to overide the argments it's possible to do that becase CMD as overide the commend

