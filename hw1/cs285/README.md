# Replicate

## 1. Behavioral cloning

### Ant

* `--ep_len 1000 --eval_batch_size 5000 --num_agent_train_steps_per_iter 1000`

```
Eval_AverageReturn : -54.065528869628906
Eval_StdReturn : 97.98095703125
Eval_MaxReturn : 40.087284088134766
Eval_MinReturn : -289.3897399902344
Eval_AverageEpLen : 261.65
Train_AverageReturn : 4713.6533203125
Train_StdReturn : 12.196533203125
Train_MaxReturn : 4725.849609375
Train_MinReturn : 4701.45654296875
Train_AverageEpLen : 1000.0
Train_EnvstepsSoFar : 0
TimeSinceStart : 23.60179305076599
Training Loss : 0.35761886835098267
Initial_DataCollection_AverageReturn : 4713.6533203125
```

* `--ep_len 1000 --eval_batch_size 5000 --num_agent_train_steps_per_iter 10000`

```
Eval_AverageReturn : 1074.0963134765625
Eval_StdReturn : 479.5704345703125
Eval_MaxReturn : 1749.302978515625
Eval_MinReturn : 158.9032745361328
Eval_AverageEpLen : 727.125
Train_AverageReturn : 4713.6533203125
Train_StdReturn : 12.196533203125
Train_MaxReturn : 4725.849609375
Train_MinReturn : 4701.45654296875
Train_AverageEpLen : 1000.0
Train_EnvstepsSoFar : 0
TimeSinceStart : 26.63428497314453
Training Loss : 0.06373836100101471
Initial_DataCollection_AverageReturn : 4713.6533203125
```

* `--ep_len 1000 --eval_batch_size 5000 --num_agent_train_steps_per_iter 100000`

```
Eval_AverageReturn : 2622.38232421875
Eval_StdReturn : 663.0209350585938
Eval_MaxReturn : 3315.81982421875
Eval_MinReturn : 1512.325927734375
Eval_AverageEpLen : 1000.0
Train_AverageReturn : 4713.6533203125
Train_StdReturn : 12.196533203125
Train_MaxReturn : 4725.849609375
Train_MinReturn : 4701.45654296875
Train_AverageEpLen : 1000.0
Train_EnvstepsSoFar : 0
TimeSinceStart : 53.5476610660553
Training Loss : 0.01192072406411171
Initial_DataCollection_AverageReturn : 4713.6533203125
```

### Walker2d

* `--ep_len 1000 --eval_batch_size 5000 --num_agent_train_steps_per_iter 10000`

```
Eval_AverageReturn : 602.5153198242188
Eval_StdReturn : 630.01318359375
Eval_MaxReturn : 3119.06298828125
Eval_MinReturn : 1.3341410160064697
Eval_AverageEpLen : 172.43333333333334
Train_AverageReturn : 5566.845703125
Train_StdReturn : 9.237548828125
Train_MaxReturn : 5576.08349609375
Train_MinReturn : 5557.6083984375
Train_AverageEpLen : 1000.0
Train_EnvstepsSoFar : 0
TimeSinceStart : 62.437166690826416
Training Loss : 0.019336936995387077
Initial_DataCollection_AverageReturn : 5566.845703125
```

## 2. DAgger

### Ant

* `--n_iter 100 --ep_len 1000 --eval_batch_size 1000 --num_agent_train_steps_per_iter 1000`

```
Eval_AverageReturn : 4040.078125
Eval_StdReturn : 0.0
Eval_MaxReturn : 4040.078125
Eval_MinReturn : 4040.078125
Eval_AverageEpLen : 1000.0
Train_AverageReturn : 107.56397247314453
Train_StdReturn : 18.555986404418945
Train_MaxReturn : 143.74069213867188
Train_MinReturn : 68.45995330810547
Train_AverageEpLen : 40.0
Train_EnvstepsSoFar : 99433
TimeSinceStart : 140.19433188438416
Training Loss : 0.011497423984110355
Initial_DataCollection_AverageReturn : 4713.6533203125
```

* `--n_iter 10 --ep_len 1000 --eval_batch_size 5000 --num_agent_train_steps_per_iter 1000`

```
Eval_AverageReturn : 796.5311279296875
Eval_StdReturn : 92.86796569824219
Eval_MaxReturn : 961.458740234375
Eval_MinReturn : 698.0799560546875
Eval_AverageEpLen : 1000.0
Train_AverageReturn : 50.58924102783203
Train_StdReturn : 16.584745407104492
Train_MaxReturn : 92.32283020019531
Train_MinReturn : 19.20334815979004
Train_AverageEpLen : 39.26923076923077
Train_EnvstepsSoFar : 9051
TimeSinceStart : 18.930088758468628
Training Loss : 0.09366338700056076
Initial_DataCollection_AverageReturn : 4713.6533203125
```

* `--n_iter 50 --ep_len 1000 --eval_batch_size 5000 --num_agent_train_steps_per_iter 1000`

```
Eval_AverageReturn : 2243.810791015625
Eval_StdReturn : 1533.7076416015625
Eval_MaxReturn : 4119.94775390625
Eval_MinReturn : 438.18707275390625
Eval_AverageEpLen : 572.1
Train_AverageReturn : 103.1474609375
Train_StdReturn : 22.539709091186523
Train_MaxReturn : 144.11805725097656
Train_MinReturn : 48.327171325683594
Train_AverageEpLen : 40.0
Train_EnvstepsSoFar : 49414
TimeSinceStart : 108.36071705818176
Training Loss : 0.020054688677191734
Initial_DataCollection_AverageReturn : 4713.6533203125
```

* `--n_iter 50 --ep_len 1000 --eval_batch_size 5000 --num_agent_train_steps_per_iter 10000`

```
Eval_AverageReturn : 4660.6474609375
Eval_StdReturn : 119.95995330810547
Eval_MaxReturn : 4823.7158203125
Eval_MinReturn : 4498.73876953125
Eval_AverageEpLen : 1000.0
Train_AverageReturn : 118.64093017578125
Train_StdReturn : 16.76449966430664
Train_MaxReturn : 154.62954711914062
Train_MinReturn : 80.15579986572266
Train_AverageEpLen : 40.0
Train_EnvstepsSoFar : 49117
TimeSinceStart : 406.0949172973633
Training Loss : 0.003641360206529498
Initial_DataCollection_AverageReturn : 4713.6533203125
```

### Walker2d

* `--n_iter 50 --ep_len 1000 --eval_batch_size 5000 --num_agent_train_steps_per_iter 10000`

```
Eval_AverageReturn : 476.41162109375
Eval_StdReturn : 110.92069244384766
Eval_MaxReturn : 838.125244140625
Eval_MinReturn : 285.82183837890625
Eval_AverageEpLen : 158.59375
Train_AverageReturn : 34.642662048339844
Train_StdReturn : 0.691923975944519
Train_MaxReturn : 36.232120513916016
Train_MinReturn : 33.33369445800781
Train_AverageEpLen : 40.0
Train_EnvstepsSoFar : 49011
TimeSinceStart : 330.7918038368225
Training Loss : 0.0013908379478380084
Initial_DataCollection_AverageReturn : 5566.845703125
```

* `--n_iter 100 --ep_len 1000 --eval_batch_size 5000 --num_agent_train_steps_per_iter 10000`

```
Eval_AverageReturn : 539.0479125976562
Eval_StdReturn : 152.84634399414062
Eval_MaxReturn : 1091.467529296875
Eval_MinReturn : 389.1151123046875
Eval_AverageEpLen : 169.86666666666667
Train_AverageReturn : 34.8885612487793
Train_StdReturn : 0.6078105568885803
Train_MaxReturn : 35.98003387451172
Train_MinReturn : 33.846641540527344
Train_AverageEpLen : 40.0
Train_EnvstepsSoFar : 99011
TimeSinceStart : 928.1692872047424
Training Loss : 0.0008697555749677122
Initial_DataCollection_AverageReturn : 5566.845703125
```

* `--n_iter 50 --ep_len 1000 --eval_batch_size 5000 --num_agent_train_steps_per_iter 10000 --n_layers 4`

```
Eval_AverageReturn : 1337.567138671875
Eval_StdReturn : 1245.0079345703125
Eval_MaxReturn : 4390.490234375
Eval_MinReturn : 292.4056396484375
Eval_AverageEpLen : 318.6875
Train_AverageReturn : 35.080814361572266
Train_StdReturn : 0.8201188445091248
Train_MaxReturn : 36.76027297973633
Train_MinReturn : 33.53729248046875
Train_AverageEpLen : 40.0
Train_EnvstepsSoFar : 49004
TimeSinceStart : 401.9557182788849
Training Loss : 0.0014777682954445481
Initial_DataCollection_AverageReturn : 5566.845703125
```

* `--n_iter 50 --ep_len 10000 --eval_batch_size 50000 --num_agent_train_steps_per_iter 10000 --n_layers 4`

```
Eval_AverageReturn : 1290.2786865234375
Eval_StdReturn : 1242.4461669921875
Eval_MaxReturn : 5337.75830078125
Eval_MinReturn : 223.95962524414062
Eval_AverageEpLen : 308.7283950617284
Train_AverageReturn : 34.72490692138672
Train_StdReturn : 0.7058006525039673
Train_MaxReturn : 36.245079040527344
Train_MinReturn : 33.341773986816406
Train_AverageEpLen : 40.0
Train_EnvstepsSoFar : 49037
TimeSinceStart : 723.4485321044922
Training Loss : 0.0014196931151673198
Initial_DataCollection_AverageReturn : 5566.845703125
```

* `--n_iter 50 --ep_len 1000 --eval_batch_size 5000 --num_agent_train_steps_per_iter 10000 --n_layers 6`

```
Eval_AverageReturn : 467.9891662597656
Eval_StdReturn : 102.46186065673828
Eval_MaxReturn : 795.5381469726562
Eval_MinReturn : 282.3546447753906
Eval_AverageEpLen : 156.5
Train_AverageReturn : 35.00904083251953
Train_StdReturn : 0.9365123510360718
Train_MaxReturn : 37.12461853027344
Train_MinReturn : 32.941497802734375
Train_AverageEpLen : 40.0
Train_EnvstepsSoFar : 49003
TimeSinceStart : 472.13244104385376
Training Loss : 0.0012332041515037417
Initial_DataCollection_AverageReturn : 5566.845703125
```

* `--n_iter 50 --ep_len 1000 --eval_batch_size 5000 --num_agent_train_steps_per_iter 10000 --n_layers 4 --size 128`

```
Eval_AverageReturn : 374.1451110839844
Eval_StdReturn : 376.7660217285156
Eval_MaxReturn : 2154.695068359375
Eval_MinReturn : 233.03163146972656
Eval_AverageEpLen : 137.64864864864865
Train_AverageReturn : 34.46094512939453
Train_StdReturn : 0.6734303832054138
Train_MaxReturn : 36.316078186035156
Train_MinReturn : 33.425838470458984
Train_AverageEpLen : 40.0
Train_EnvstepsSoFar : 49009
TimeSinceStart : 496.32805728912354
Training Loss : 0.0007928024861030281
Initial_DataCollection_AverageReturn : 5566.845703125
```

* `--n_iter 200 --ep_len 1000 --eval_batch_size 5000 --num_agent_train_steps_per_iter 10000 --n_layers 4`

```
Eval_AverageReturn : 3960.825439453125
Eval_StdReturn : 1020.1004028320312
Eval_MaxReturn : 5201.52734375
Eval_MinReturn : 2734.312744140625
Eval_AverageEpLen : 781.1428571428571
Train_AverageReturn : 34.83725357055664
Train_StdReturn : 0.767741322517395
Train_MaxReturn : 36.97075653076172
Train_MinReturn : 33.943275451660156
Train_AverageEpLen : 40.0
Train_EnvstepsSoFar : 199004
TimeSinceStart : 3269.9124550819397
Training Loss : 0.00020596006652340293
Initial_DataCollection_AverageReturn : 5566.845703125
```