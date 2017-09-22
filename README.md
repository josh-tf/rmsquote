# RMS Quote

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

**RMS Quote** is a simple script that displays a random quote from Richard Stallman.

### Requirements:
| Programs |
| ------ |
| Curl | 
| Git |

### Installation

RMS Quote requires [Curl](https://curl.haxx.se/) to run, simply install *curl* with your available package manager.

```sh
$ git clone https://github.com/josh-tf/rmsquote.git
$ cd rmsquote
```

If you wish to run rms from anywhere simply copy to /bin
```sh
# cp rms /bin
You may need to change permissions for regular users to run
# chmod 755 /bin/rms
```
Once installed simply run from the folder **./rms** or if you copied to bin you can run **rms** from anywhere!
```sh
# ./rms
OR
# rms
```
***Please note*** - you may need to modify file permissions if copying to /bin as root/super user.

#### Sample output: 
Richard Stallman and a Random Quote (Generated using custom fortune list)
```sh
  _______________________________________
/ Once GNU is written, everyone will be \
| able to obtain good system software   |
\ free, just like air.                  /
 ---------------------------------------
             \        @@@@@@ @
              \     @@@@     @@
               \   @@@@ =   =  @@ 
                \ @@@ @ _   _   @@ 
                 @@@ @<0>)|(<0>  @@ 
                 @@@@   ~ | ~   @@
                 @@@ @  (o1o)    @@
                @@@    #######    @
                @@@   ##{+++}##   @@
               @@@@@ ## ##### ## @@@@
               @@@@@#############@@@@
              @@@@@@@###########@@@@@@
             @@@@@@@#############@@@@@
             @@@@@@@### ## ### ###@@@@
              @ @  @              @  @
                @                    @

```
### Todos

 - More endpoints (cat facts etc)
 - Re-write server in python (will publish on github)

License
----

MIT


**Free Software, Hell Yeah!**
