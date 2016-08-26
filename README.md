# ABSK
>modify sk66 to ABSK, do not via one node twice.

##Repo
- [alpha/frame](https://github.com/lucyking/alpha/tree/frame)

##About
- refer to [neooelric](https://github.com/neooelric)'s framework [codeCraft3.0_SK66 project](https://github.com/neooelric/codeCraft3.0_SK66),but the core algorithm ASK/ABSK is wrote by myself.
- sk66 may obtain loop route,ABSK do NOT.
- the code will use the __Modified__ Dijkstra() to find all the __k shortest path__ between node(i)_node(j) (i,j) E Vs.
- ABSK is such like BSK,the same does ASK.
- ABSK/ASK(...,asi)  --> asi determines how many __shortest path__  should be selected.
- lne184: use LocateSetNode to get the K shortest subpath from node,to all possible Vx',will check the the ``set<int> processed``,make sure there's no vied node in subpath.

##Build
- make
  - build the target from src
  
- make clean
  - rm *.o ${TARGET}
  
##Run
- ./toobar a.csv b.csv log

##Todo
- the code is all in a muddle,may modify sooner.
- fx SK66() or VECTK() is useless. 
