Add your answers to the Algorithms exercises here.

a) 0(n)

The value of the while loop is n^3 and the value of (a) after it runs once is a+n^2
drop the constant n^3 / n^2 == 0(n)


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



Part II
def storyHeight(n):
    f = lowest floor that egg will break                                    
    first = 0
    last = n
    while height f isn't found 
        current = last/2
       if egg breaks from current:
            last = current
            first - last / 2
        elif egg doesn't break from current:
            first = current
            first + last / 2
