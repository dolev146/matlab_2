# matlab_2

```

>> clear

to change the working dir
just change the path to the dir

scalars vectors matrices


>> x = 5

x =
    5

>> size(x)

ans = 
        1   1

>> v = [1,2,3]
>> size(v)
ans = 
        1   3

>> v = [1 2 3];

>> size(v)
ans =
        1   3

>> A = [1 2; 3 4;]
A = 
    1   2
    3   4

>> size(A)
ans = 
      2   2


>> v = v'
v = 
    1
    2
    3

>> v = [1; 2; 3;]
v = 
    1
    2
    3

>> size(v)
ans = 
      1   3
      

>> A(i,j)


>> A(1,1)
ans = 
      1
>> A(1,2)
ans =
      2
>> A(2,1)
ans = 
      3
      
>> A(1,:)
ans = 
        1   2
        
>> A(:,2)
ans = 
        2
        4

>> A(:,:)
ans = 
        1   2
        3   4
        
>> A = [1 2 3 4; 5 6 7 8; 9 10 11 12; 13 14 15 16;];
>> size(A)
ans =
      4   4
      
>> A
A = 
      1   2   3   4
      5   6   7   8
      9   10  11  12
      13  14  15  16
      
>> A(2:3,2:3)
ans = 
      6   7
      10  11

>> A(1:1)
ans = 
      1
      
>> 1:10
ans = 

      1   2   3   4   5   6   7   8   9   10
      
>> w =  1:10
>> size(w)
ans = 
        1   10
        
>> A = [1 2; 3 4];
>> B = [5 6; 7 8];
>> C = [9 10; 11 12];
>> A + B

ans = 
    6   8
    10  12
    
>> A - B

ans =
      -4    -4
      -4    -4
      
>> A*B

ans = 
    19  12
    43  50




























```
