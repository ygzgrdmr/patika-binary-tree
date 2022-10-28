# patika-binary-tree

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

array in ilk elemanını kök olarak kabul ederiz ve sonrasında gelen elemanlar roottan büyük ise sağa küçük ise sola yazılarak ağaç oluşturulur 

-         7
         /
        5
        
-         7
         /
        5
       / 
      1  
      
      
-         7
         / \
        5   8
       / 
      1  
      
-         7
         / \
        5   8
       / 
      1
       \ 
        3 
        
 -        7
         / \
        5   8
       / \
      1   6 
       \ 
        3 
        
 -        7
         / \
        5   8
       / \
      1   6 
     / \ 
    0   3 
 -        7
         / \
        5   8
       / \   \
      1   6   9
     / \ 
    0   3 
    
 -        7
         / \
        5   8
       / \   \
      1   6   9
     / \ 
    0   3 
         \
           4
           
 -        7   ağacın son hali
         / \
        5   8
       / \   \
      1   6   9
     / \ 
    0   3 
       / \
      2   4         
 
