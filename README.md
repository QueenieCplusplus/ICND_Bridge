# ICND Bridge
Layer2 SW

* Preview:

https://github.com/QueenieCplusplus/ICND_Data_Link_Layer/blob/master/README.md#橋接器的交換技術

* 橋接技術的特性：

   * 每一區段自成碰撞區。 （一橋接器或是交換器最多能劃分出四個碰撞區，並且只有一個廣播區。）
   
   * 以同一橋接器（抑或是 L2 交換器）相連的所有設備（終端機、主機、工作站）亦為同一廣播區。
   
   * 所有區段必須採用同樣標準，倘若兩節點（源頭和目的）為不同標準，則中間需要經由路由器或是轉換式橋接器（非僅僅交換式橋接器）。
   
   * 在一交換式環境中，每區段僅能有一設備！但他們共享主要幹道，即為骨幹 Backbone，可同時將資料送出。
   

* Main Features:

橋接器提供了資料流管理 flux rate optimization 好比更大的地上停車場和更多的出入口, 而第二層交換器減少信號碰撞的方式則更是避免浪費頻寬，好似地上電子升降停車場（利用記憶體暫存的方式），當兩個以上的封包要同時送入同一區段時，封包會先暫時儲存在記憶體內，直到線路空出來為止。


