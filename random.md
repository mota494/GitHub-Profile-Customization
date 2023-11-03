# Index
<a href="#cards"><h3>∘Cards</h3></a>
<a href="#mermaid"><h3>∘Mermaid</h3></a>

<div align="center">
  
  # Cards</h1>
  
</div>

___

<div align="center">
  
  # Mermaid</h1>
  
</div>

```
Source: https://mermaid.js.org/
```

Mermaid is a simple and easy tool to learn that allows you to implement diagrams and charts, right now there's 9 different types of charts available.

<ol>
  <li><a href="#flowchart">Flowchart</a></li>
  <li></li>
  <li></li>
  <li></li>
  <li></li>
  <li></li>
  <li></li>
  <li></li>
  <li></li>
</ol>

### Flowchart

```mermaid
gantt
dateFormat  YYYY-MM-DD
title Adding GANTT diagram to mermaid
excludes weekdays 2014-01-10

section A section
Completed task            :done,    des1, 2014-01-06,2014-01-08
Active task               :active,  des2, 2014-01-09, 3d
Future task               :         des3, after des2, 5d
Future task2               :         des4, after des3, 5d

section B section
Completed task            :done,    des1, 2014-01-06,2014-01-08
Active task               :active,  des2, 2014-01-09, 3d
Future task               :         des3, after des2, 5d
Future task2               :         des4, after des3, 5d
```
