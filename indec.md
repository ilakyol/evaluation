# Average Evaluation Table(per 100 model?)


| Complexity Class         |Errors* per Model| Average Edge-Edge Crossings per Model  | Average Edge-Node Intersections per Model      | Average Label Intersections per Model      | Average Imprecisions per Model   | Average Complexity Degree per Model    |
|----------------|---------------------|--------------------------|-------------------------|--------------------|----------------------|----------------------|
| Simple        |0,363636363| 0,045454545          | 0,03030303               | 0,075757576             |0              | 5,106060606    |
| Medium        |0,898148148| 0,277777778          | 0,87962963               | 1,157407407             | 0,527777778   | 14,14814815    |
| Complex       |1,057471264| 1,551724138          | 2,482758621              | 4,655172414             | 2,390804598   | 37,8045977     |
| Total         |0,816091954| 0,643678161          | 1,199233716              | 2,049808429             | 1,01532567    | 19,74712644    |

# Per Degree Evaluation Table

|  Average Edge-Edge Crossings per Degree  | Average Edge-Node Intersections per Degree      | Average Label Intersections per Degree      | Average Imprecisions per Degree   | 
|---------------------|--------------------------|-------------------------|--------------------|
| 0,032596042  | 0,06072953            |     0,103802872        |       0,051416376       | 

# Change of respected Intersections/Errors with complexity increase

| Complexity Class         |Errors* per Model| Average Edge-Edge Crossings per Model  | Average Edge-Node Intersections per Model      | Average Label Intersections per Model      | Average Imprecisions per Model   | Average Complexity Degree per Model    |
|----------------|---------------------|--------------------------|-------------------------|--------------------|----------------------|----------------------|
| Simple-Medium   | 1.469907407          | 5.111111111             | 14.27777778  |28.02777778             |/inf           | 1.77085394    |
| Medium-Complex  | 0.177390686          | 4.586206897             | 3.022068966  |1.822504537             |3.529945554    | 1.672052717   |
| Simple-Complex  | 1.908045977          | 33.13793103             | 60.44827586  |80.93103448             |/inf           | 6.403867799   |
