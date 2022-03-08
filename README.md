# H.V.A.S.
<img alt="HVAS" height="40px" src="https://i.imgur.com/u2obU99.png" />

## Hora Video Analytic System

Try all the models at [app.horavision.ai](https://app.horavision.ai) by making a free account. See [here](https://github.com/davide-zagami/hvas) for how to use the platform or the API.

### Car damage recognition MaskRCNN model.

The car is segmented into its macro components, and each component is given a damage level ranging in 5 different values from "good" to "completely destroyed / missing".

#### Performance

| Model  | Arch | Complexity (GFLOPs) | Size (Mp) | Segm AP @ [IoU=0.50:0.95] (%) |
| ------------------- | ------ | ------ | ----- | ---- |
| Car damage recognition | MaskRCNN | 82.62   | 58.40  | 74.1 |

#### Demo:
![](https://i.imgur.com/wKzIT6g.jpg)
![](https://i.imgur.com/ZUqp1or.jpg)
![](https://i.imgur.com/CqP3F4M.jpg)
![](https://i.imgur.com/9GAKu0Q.jpg)
![](https://i.imgur.com/faeRcxy.jpg)
![](https://i.imgur.com/swJ1yPQ.jpg)
![](https://i.imgur.com/7HlShoO.jpg)
![](https://i.imgur.com/L4W7GpL.jpg)
![](https://i.imgur.com/dnVgOQ3.jpg)
