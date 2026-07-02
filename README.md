## The commands line here are applications in


--Based linux systems and bash and sh and others commands based systems linux Debian

--require terminal mode in your system operation.


## Example command list proccess and services your system

--list services and process

> $ ps -ef

> $ ps -aux


#### list services and process especifique with grep

> $ ps -ef | grep "oralce"

> $ ps -aux |grep "java"


#### list with collumns with awk

> $ ps -ef | awk {'print $1 $5 $7 $8'}

> $ ps -ef | awk {'print $1 "  -  " $5 "  -  " $7 "  -  "  $8'}

> $ ps -aux | awk {'print $1 $2 $9 $10 $11'}

> $  ps -aux | awk {'print $1 " - " $2 " - " $9 " - " $10 " - " $11'}

  



#### well this is in implementation, brave more commits...


#### Final publish this 
