```sequence
սʿ->�쵼: �׳���
Note right of �쵼: �׳����ӵ����Ļ
�쵼-->սʿ: ͬ־�Ǻ�
սʿ->>�쵼: Ϊ�������
```
```flow
st=>start: �����ӽ��̳�
op=>operation: ������
cond=>condition: ���ӿ�������?
e=>end: ���̳�
st->op->cond
cond(yes)->e
cond(no)->op
```

```mermaid
gantt
title ����ͼ
dateFormat YYYY-MM-DD
section ��1
����1 :a1, 2023-01-01, 30d
����2 : 20d
section ��2
����3 : after a1 ,12d
����4 : 24d
```

``` mermaid
classDiagram
Class01 <|-- AveryLongClass : Cool
Class03 *-- Class04
Class05 o-- Class06
Class07 .. Class08
Class09 --> C2 : Where am i?
Class09 --* C3
Class09 --|> Class07
Class07 : equals()
Class07 : Object[] elementData
Class01 : size()
Class01 : int chimp
Class01 : int gorilla
Class08 <--> C2: Cool label
```
