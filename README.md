# Tower-of-Hanoi_Octave

function [from , to , via ] = hanoimove (n, from , to , via )
  if ( n == 1 )
    printf("Move disk from A to C");
  else
    hanoimove(n-1, A, B, C);
    hanoimove(1, A, C, B);
    hanoimove(n-1, B, C, A);
  endif
endfunction􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀􀀀
