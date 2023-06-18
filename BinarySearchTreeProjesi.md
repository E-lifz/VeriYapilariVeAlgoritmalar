### **Soru**
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.   
Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

### **Çözüm**

[0,1,2,3,4,5,6,7,8,9]    
root = 4      

1. adım: 4'ün sağında 5, solunda 3 bulunur.

4    
/ \  
3 5

2. adım: 5'in sağında 6 bulunur. 3'ün solunda ise 2 yer alır.

 4    
/ \  
3  5   
/  \     
2  6      

3. adım: 6'nın sağında 7 bulunur. 2'nin solunda ise 1 bulunur.

 4    
/ \  
3  5   
/  \     
2  6   
/  \      
1  7

4. adım: 7'nin sağında 8 bulunur. 1'in solunda ise 0 yer alır.

 4    
/ \  
3  5   
/  \        
2  6   
/  \        
1  7    
/  \       
0   8

5. adım: 8'in sağında 9 bulunur.

 4    
/ \  
3  5   
/  \        
2  6   
/  \        
1  7    
/  \       
0   8   9