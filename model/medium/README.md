以下データから作った学習モデル<br>
[dataset/sample](https://github.com/seigot/ai_race_data_sample/tree/main/dataset/sample)<br>
<br>
trtファイルは大きいので、以下の通り結合してから使用下さい。<br>
<br>
結合

```
cat sample_trt_p* > sample_trt.pth
```

分割

```
split -b 55m -a 1 sample_trt.pth sample_trt_p
```
