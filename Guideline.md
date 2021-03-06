## Guidelines:

* Follow the Link: <https://codingcompetitions.withgoogle.com/kickstart>
* Solve either in C or C++ or Java or Python.
* Create a folder within the Question Folder with name `FirstName-ProgrammingLanguage`, for ex: `Falguni-Python`.

    In the folder:
    - Add Code File with name `questionname.extension`, for ex: `Allocation.py`.
    - Add Editor Screenshot as shown below:
    
      <img src="https://github.com/BlankCoders/GoogleKickStart2020_Solutions/blob/master/assets/EditorSS/falguni_soln.png">
      
    Check Example Repository: [Falguni-Python](https://github.com/BlankCoders/GoogleKickStart2020_Solutions/tree/master/Round%20A/Allocation/Falguni-Python)
    
* If you upload code that is inspired from somewhere, write the resource by commenting first line like this:

```
# Inspired or took help from xyz
T=int(input())
A=[]
for t in range(1,T+1):
    N,B=[int(s) for s in input().split(" ")]
    A=list(map(int, input().split()))
    count=0
    A.sort()
    for i in range(len(A)):
        if(B>=A[i]):
            B=B-A[i]
            count+=1
    print("Case #{}: {}".format(t,count))
    A.clear()
```

* Plagirism is strongly discouraged.
