
Makefile格式
============
```
target: dependencies
<Tab>Commands
```
target：所要建立的檔案  
dependencies：相依項目。 make 會據此決定是否要重新編譯 target。  
Commands：建立 target 的指令。  
預設上，make 會參考 all 這個目標項目，並依據它的 dependencies 來決定要建立哪些項目。若沒有 all 項目，則會採用 Makefile 裡的第一個項目。

Eclipse to Linux
================
在Project->Properties  
C/C++ Biuld->Tool Chain Editor  
將Current builder設為Gnu Make builder  
就會自動產生makefile及*.mk檔
