以下データから作った学習モデル<br>

[dataset/plane](https://github.com/seigot/ai_race_data_sample/tree/main/dataset/plane)<br>

<br>
trtファイルは大きいので、以下の通り結合してから使用下さい。<br>
<br>
結合

```
cat sample_plane_trt_p* > sample_plane_trt.pth
```

分割

```
split -b 45m -a 1 sample_plane_trt.pth sample_plane_trt_p
```
