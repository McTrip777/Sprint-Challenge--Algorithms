Add your answers to the Algorithms exercises here.

a) (n^3) (infinite)

This is an endless loop unless n has the value 0, 1 or a negative number.
its a while loop that that says while (a) is less than (n^3) then run.
In the loop a = a + (n^2) so a will never be larger than (n^3)


b) n^3
<!-- for i in range(n):                         0(n)
      i += 1 
      for j in range(i + 1, n):                 0(n)
        j += 1 
        for k in range(j + 1, n):               0(n)
          k += 1 
          for l in range(k + 1, 10 + k):        0(1)
            l += 1 
            sum += 1  -->
   

This one was not easy to understand but if you really look at it, all the values are passed around. So whatever n is passed in as, is what i, j and k will be. so this is a n^3 algorithm.


c) 0(n)

whatever number is passed in is what is going to determine how many times it runs so this is a 0(n) algorithm