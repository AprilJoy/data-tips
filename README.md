# data-tips

## 数据碎碎念
开一个小专栏，说一说对数据的认识和理解	，是为记。

## 数据碎碎念1
>正确的数据统计开始于细心。	

where event_day = '20160311' 和  where event_day = '201610311'
看出这两者的区别了么？是的，仅仅多了一个1。但是这会造成两个表连接时，一个表中的数据全部为空，进而造成实际统计的结果与逻辑上构想的结果产生出入。这种微小的错误，发生了就很难查出。正确的数据统计开始于细心。	