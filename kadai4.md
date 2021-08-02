```uml
@startuml
particpant お客
particpant ホール係
particpant 厨房
お客 -> ホール係: 注文
お客　<-- ホール係:　注文した料理
ホール係　<- 厨房: 完成した料理
ホール係　-> 厨房: 席番号と料理
@enduml
```
