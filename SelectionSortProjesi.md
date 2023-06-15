### **Soru 1**

[22,27,16,2,18,6] -> Insertion Sort

* Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

### **Çözüm**

[22,27,16,2,18,6] == n   
[2,22,27,16,18,9] == n-1   
[2,9,22,27,16,18] == n-2   
[2,9,16,22,27,18] == n-3    
[2,9,16,18,22,27] == 1 

### **Soru 2**

* Big-O gösterimini yazınız.

### **Çözüm**

n+(n-1)+(n-2)+(n-3)+1   
n+n-1+n-2+n-3+1      
4n-4   
Big-O = O(n)

### **Soru 3**

* Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız 
    - Average case: Aradığımız sayının ortada olması
    - Worst case: Aradığımız sayının sonda olması
    - Best case: Aradığımız sayının dizinin en başında olması.  

### **Çözüm**

[2,9,16,**18**,22,27]

18 sayısı dizinin ortasında yer aldığı için "avarage case" kapsamındadır.

### **Soru 4**

* [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

### **Çözüm**

[7,3,5,8,2,9,4,15,6] == n    
[2,3,5,8,7,9,4,15,6] == n-1    
[2,3,4,8,7,9,5,15,6] == n-2    
[2,3,4,5,7,9,8,15,6] == n-3    
[2,3,4,5,6,9,8,15,7] == n-4