## Graph Based State Machine
This finds a random entry point for three distinct states: life status, weapon state, and player turn order. Using graph based mechanics.

~~~
         alive dead undead
 alive   a,a   a,d  a,u
 dead    d,a   d,d  d,u
 undead  u,a   u,a  u,u

         epee ishi bache
 epee    e,e  e,i  e,b
 ishi    i,e  i,i  i,b
 bache   b,e  b,i  b,b

         player spider enemy
 player  p,p    p,s    p,e
 spider  s,p    s,s    s,e
 enemy   e,p    e,s    e,e
~~~
