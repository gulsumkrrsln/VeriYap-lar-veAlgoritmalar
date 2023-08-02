# VeriYaplarveAlgoritmalar
# PROJE 1
<hr>

### A: Selection sort aşamaları: [22,27,16,2,18,6] -> Insertion Sort
[22,27,16,2,18,6]<br>
[2,27,16,22,18,6]<br>
[2,6,16,22,18,27]<br>
[2,6,16,18,22,27]<br>
<hr>

### B: Big-O gösterimini yazınız.
<li>
 n+(n-1)+(n-2)...(n-4)+1=[n.(n+1)]/2=(n^2+n)/2 
 <li> o(n^2)
<hr>

### C: Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer?
 <li>Average Case
 <hr>

  ### D: [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
 <ol> <li> [2,3,5,8,7,9,4,15,6] 
 <li> [2,3,4,8,7,9,5,15,6] 
 <li> [2,3,4,5,7,9,8,15,6] 
  <li> [2,3,4,5,6,9,8,15,7] 
 <hr>

  # PROJE 2
 ### [16,21,11,8,12,22] -> Merge Sort
 
A) Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
B) Big-O gösterimini yazınız.
   <br>
 A) <br>
   <ol> <li>  [16, 21, 11] ve [8, 12, 22]
 <li> [16, 21, 11] -> [16], [21, 11] -> [21], [11]
 <li> [8, 12, 22] -> [8], [12, 22] -> [12], [22]
 <li> [16] [11, 21] -> [11, 16, 21]
 <li> [8] [12, 22] -> [8, 12, 22]
 <li> [11, 16, 21] ve [8, 12, 22] -> [8, 11, 12, 16, 21, 22]
  <li> [8, 11, 12, 16, 21] - Sonuç
<hr>
 B) <br>
   2x=n <br>
   X=logn <br>
   Big-0= o (nlogn) <br>
   <hr>

    # PROJE 3 
   ### [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
   
   Root 7'dir. <br>
5, soluna eklenir. <br>
1, soluna eklenir.<br>
8, sağına eklenir.<br>
3, 5'in soluna eklenir.<br>
6, 5'in sağına eklenir.<br>
0, 1'in soluna eklenir.<br>
9, 8'in sağına eklenir.<br>
4, 3'ün sağına eklenir.<br>
2, 1'in sağına eklenir.<br>
        7
       / \
      5   8
     / \   \
    1   6   9
   / \     
  0   3    
     / \
    2   4  
   <hr>
        &nbsp; 7 <br>
       / &nbsp; \ <br>
      5  &nbsp; &nbsp; &nbsp;  8 <br>
     / \ &nbsp;  &nbsp; &nbsp;  \ <br>
    1 &nbsp;   6 &nbsp; &nbsp;   9 <br>
   / \   &nbsp; &nbsp;   <br> 
  0 &nbsp; 3  &nbsp;  <br> 
   &nbsp;&nbsp;    / &nbsp; \ <br>
 &nbsp;  &nbsp;   2  &nbsp;  4  <br>
