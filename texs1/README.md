## 实验一：SQL实验执行语句，优化指导
### 教材中的查询语句：                          
- Query 1

    ![](./img/1.png)    
- Query 2            
![](./img/2.png)       
###结果：                                 
- Result 1:                                       
![](./img/3.png)                              
- Result 2:   
 ![](./img/5.png.)
 ###分析：
   - Analysis 1:                                            
   ![](./img/4.png) 
   - Analysis 2:     
   ![](./img/6.png)
   My anlysis:      
   Query1的查询消耗的内存少于Query2的内存，且Query1采用索引扫描，Query2用的是全表两者相比，Query 1的查询效率更高
   ### 我的查询语句：      
   - Code:         
   ![](./img/7.png)
   - Result:    
   ![](./img/8.png)
   - Analysis   
   ![](./img/9.png)