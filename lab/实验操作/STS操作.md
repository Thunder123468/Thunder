<<<<<<< HEAD
version https://git-lfs.github.com/spec/v1
oid sha256:5670202a43e921c3053e359b0022ad67d59328f62aff6bd712af6801a67c764b
size 623
=======
### Mapping：
对实空间这个二维平面进行扫图，进行正负范围内的电压变换，测量某一个电压下的dI/dV的数据，并最终画在一张四维图像中。
dI/dV的测量方法：加一个lockin，加一个正弦波让电压在固定点周围进行变换，并测量电流值，最后得出dI/dV。
![[华为扫描_20230727103632027.jpg|400]]
### Mapping图：
和[[STS操作#Mapping：||Mapping]]类似，是我在扫图的时候固定某一个电压值，进行dI/dV的测量，并画出这样的三维图像。
具体操作：打开Lockin，auto一下相位，把扫描速度降低（10nm/s)

>>>>>>> 784e441 (try)
