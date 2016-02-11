# Tower-of-Hanoi_Octave

function [from , to , via ] = hanoimove (n, from , to , via )
rodA . name = ’A ’ ; rodA . discs = [3 , 2 , 1]
rodB . name = ’B ’ ; rodB . discs = [ ]
rodC . name = ’C ’ ; rodC . discs = [ ]
[ rodA , rodB , rodC ] = hanoimove (3 , rodA , rodB , rodC)

  if ( ndisks == 1 )
    printf("Move disk from rod %d to rod %d\n", from, to);
  else
    hanoimove(ndisks-1, from, via, to);
    hanoimove(1, from, to, via);
    hanoimove(ndisks-1, via, to, from);
  endif
endfunction
 
hanoimove(4, 1, 2, 3);􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀

Example:

A: 3 2 1
B : [ ] ( 0 x0 )
C: [ ] ( 0 x0 )
􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀
A: 3 2
B: 1
C: [ ] ( 0 x0 )
􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀
A: 3
C: 2
B: 1
􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀
