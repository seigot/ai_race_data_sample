以下データから作った学習モデル<br>
[https://github.com/seigot/ai_race_data/tree/main/dataset/20201107](https://github.com/seigot/ai_race_data/tree/main/dataset/20201107)<br>
<br>
trtファイルは大きいので、以下の通り結合してから使用下さい。<br>
<br>
結合

```
cat sample_trt_p_* > sample_trt.pth
```

分割

```
split -b 55m -a 1 sample_trt.pth sample_trt_p
```
