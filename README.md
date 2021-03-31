# meson-scheduling
### next generation content scheduling 
\
&nbsp;

## problem definition


### 1.background and context
In the development of meson.network we find that 
meson is indeed a distributed CDN network. The meson.network is public and open that everyone with a server 
can join this network. Currenlty there are about 200 nodes in meson.network and the number is still increasing .
Each node server in meson.network varies in storage size and bandwidth size.
\
&nbsp;

### 2.goal of meson.network
For any given file it can be stored on meson.network nodes servers. If the file is hot in some country it will be stored on one or more server nodes in that country. If there is no reqeust to some file ,that file will not be stored on any node server in meson.network. So in general 
the meson.network is a cache layer which caches hot files
on nodes that are in the same country where these hot files exist.
\
&nbsp;


### 3.scheduling problem
Generally in a specific country, we have multiple files which need to be stored on multiple nodes for some time ,
the scheduling algorithm deals with this distributing and storage process to achive max efficiency.

### 3.1 Problem variables
#### 3.11 node server array with storage capacity (sc) and bandwith capacity(bc) 

[ &nbsp;node0(sc0,bc0), &nbsp; node1(sc1,bc1)..... , noden(scn,bcn)&nbsp;]

#### 3.12 files array with file size (fz) and file request frequency (ff)

[ &nbsp; file0(fz0,ff0),&nbsp; file1(fz1,ff1)&nbsp; .....,&nbsp; filen(fzn,ffn)&nbsp; ]

### 3.2 scheduling algorithm controls
according to 3.1 varibales , scheduling algorithm will  
control storing process and recycling process of files  over the node servers in a specific contry to achive max 
transmition efficiency.









