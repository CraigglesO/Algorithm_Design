# Depth First Search

Psuedo Code
-----------

```bash
           3.141592653589793238462643383279502884197
         1693993751058209749445923078164062862089986
       280348253421170679821480865132823066470938446
      0955058223172535940812848111745028410270193852
     11055596446229489549303819644288109756659334461
    284756482337867831652712019091456485669234603486
   104543266482133936072602491412737245870066063155 
  881748815209209628292540917153643678925903600113  
 30530548820      46652         13841               
 4695194          15116        094330               
572703            65759        59195                
30921            861173        81932                
6117             93105         11854                
                807446         23799                
                627495        673518                
                857527        248912                
               279381         830119                
               491298         336733                
              6244065         664308                
              6021394         9463952               
             2473719         07021798               
             6094370         27705392               
            17176293         17675238               
            46748184         676694051              
           32000568          127145263              
           56082778          577134275              
          778960917          3637178721             
          468440901          2249534301             
         465495853           71050792279            
         689258923           54201995611            
        2129021960           864034418159           
        8136297747            71309960518           
       7072113499             99998372978           
       0499510597             31732816096           
       3185950244              594553469            
        08302642               522308253            
        3446850                 3526193     Depth First Search
      
      DFS(G)

      1 for each vertex u in set G.V
      2   u.color = WHITE
      3   u.parent = NIL
      4 time = 0
      5 for each vertex u in set G.V
      6   if u.color == WHITE
      7     DFS-VISIT(G,u)

      DFS-VISIT(G,u)

      1 time = time + 1                 // white vertex u has just been discovered
      2 u.d = time
      3 u.color = GRAY
      4 for each v in set G.adj[u]
      5   if v.color == WHITE
      6     v.parent = u
      7     DFS-VISIT(G,v)
      8 u.color = BLACK
      9 time = time + 1
     10 u.f = time



```


About
--------
```clojure

```

