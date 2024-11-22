## Output once we run python CNN.py


2024-11-22 08:53:48.297482: I tensorflow/core/platform/cpu_feature_guard.cc:210] This TensorFlow binary is optimized to use available CPU instructions in performance-critical operations.
To enable the following instructions: AVX2 FMA, in other operations, rebuild TensorFlow with the appropriate compiler flags.
2024-11-22 08:53:49.586748: W tensorflow/compiler/tf2tensorrt/utils/py_utils.cc:38] TF-TRT Warning: Could not find TensorRT
Downloading data from https://storage.googleapis.com/tensorflow/tf-keras-datasets/train-labels-idx1-ubyte.gz
29515/29515 ━━━━━━━━━━━━━━━━━━━━ 0s 0us/step
Downloading data from https://storage.googleapis.com/tensorflow/tf-keras-datasets/train-images-idx3-ubyte.gz
26421880/26421880 ━━━━━━━━━━━━━━━━━━━━ 3s 0us/step   
Downloading data from https://storage.googleapis.com/tensorflow/tf-keras-datasets/t10k-labels-idx1-ubyte.gz
5148/5148 ━━━━━━━━━━━━━━━━━━━━ 0s 0us/step
Downloading data from https://storage.googleapis.com/tensorflow/tf-keras-datasets/t10k-images-idx3-ubyte.gz
4422102/4422102 ━━━━━━━━━━━━━━━━━━━━ 0s 0us/step
2024-11-22 08:54:01.340138: W external/local_tsl/tsl/framework/cpu_allocator_impl.cc:83] Allocation of 75264000 exceeds 10% of free system memory.
2024-11-22 08:54:01.427538: W external/local_tsl/tsl/framework/cpu_allocator_impl.cc:83] Allocation of 37632000 exceeds 10% of free system memory.
2024-11-22 08:54:01.613359: W external/local_tsl/tsl/framework/cpu_allocator_impl.cc:83] Allocation of 37632000 exceeds 10% of free system memory.
[iteration]: 0, [LOSS]: 0.672200
[iteration]: 10, [LOSS]: 0.724182
[iteration]: 20, [LOSS]: 0.698101
[iteration]: 30, [LOSS]: 0.671083
[iteration]: 40, [LOSS]: 0.703809
[iteration]: 50, [LOSS]: 0.692727
[iteration]: 60, [LOSS]: 0.693482
[iteration]: 70, [LOSS]: 0.675668
[iteration]: 80, [LOSS]: 0.721813
[iteration]: 90, [LOSS]: 0.688234
[iteration]: 100, [LOSS]: 0.697554
[iteration]: 110, [LOSS]: 0.694965
[iteration]: 120, [LOSS]: 0.692376
[iteration]: 130, [LOSS]: 0.688774
[iteration]: 140, [LOSS]: 0.688234
[iteration]: 150, [LOSS]: 0.671545
[iteration]: 160, [LOSS]: 0.712930
[iteration]: 170, [LOSS]: 0.675502
[iteration]: 180, [LOSS]: 0.689787
[iteration]: 190, [LOSS]: 0.687199
2024-11-22 08:54:04.941430: W external/local_tsl/tsl/framework/cpu_allocator_impl.cc:83] Allocation of 37632000 exceeds 10% of free system memory.
2024-11-22 08:54:05.031715: W external/local_tsl/tsl/framework/cpu_allocator_impl.cc:83] Allocation of 37632000 exceeds 10% of free system memory.
Epoch 1/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 1s 1ms/step - loss: 0.0840 - val_loss: 0.0339
Epoch 2/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 0s 1ms/step - loss: 0.0318 - val_loss: 0.0273
Epoch 3/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 0s 985us/step - loss: 0.0258 - val_loss: 0.0226
Epoch 4/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 1s 1ms/step - loss: 0.0213 - val_loss: 0.0200
Epoch 5/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 0s 1ms/step - loss: 0.0192 - val_loss: 0.0184
Epoch 6/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 0s 1ms/step - loss: 0.0178 - val_loss: 0.0175
Epoch 7/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 1s 1ms/step - loss: 0.0166 - val_loss: 0.0168
Epoch 8/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 0s 1ms/step - loss: 0.0163 - val_loss: 0.0164
Epoch 9/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 1s 1ms/step - loss: 0.0161 - val_loss: 0.0160
Epoch 10/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 1s 1ms/step - loss: 0.0159 - val_loss: 0.0159
[iteration]: 0, [LOSS]: 0.692231
[iteration]: 10, [LOSS]: 0.699277
[iteration]: 20, [LOSS]: 0.687453
[iteration]: 30, [LOSS]: 0.677962
[iteration]: 40, [LOSS]: 0.670106
[iteration]: 50, [LOSS]: 0.662325
[iteration]: 60, [LOSS]: 0.644802
[iteration]: 70, [LOSS]: 0.625271
[iteration]: 80, [LOSS]: 0.609055
[iteration]: 90, [LOSS]: 0.523987
[iteration]: 100, [LOSS]: 0.571625
[iteration]: 110, [LOSS]: 0.513643
[iteration]: 120, [LOSS]: 0.506671
[iteration]: 130, [LOSS]: 0.474119
[iteration]: 140, [LOSS]: 0.521455
[iteration]: 150, [LOSS]: 0.378397
[iteration]: 160, [LOSS]: 0.365411
[iteration]: 170, [LOSS]: 0.337632
[iteration]: 180, [LOSS]: 0.531617
[iteration]: 190, [LOSS]: 0.381731
[iteration]: 0, [LOSS]: 0.668614
[iteration]: 10, [LOSS]: 0.624279
[iteration]: 20, [LOSS]: 0.608272
[iteration]: 30, [LOSS]: 0.592763
[iteration]: 40, [LOSS]: 0.566369
[iteration]: 50, [LOSS]: 0.518203
[iteration]: 60, [LOSS]: 0.431845
[iteration]: 70, [LOSS]: 0.451204
[iteration]: 80, [LOSS]: 0.255006
[iteration]: 90, [LOSS]: 0.196092
[iteration]: 100, [LOSS]: 0.398142
[iteration]: 110, [LOSS]: 0.136838
[iteration]: 120, [LOSS]: 0.124327
[iteration]: 130, [LOSS]: 0.244332
[iteration]: 140, [LOSS]: 0.394044
[iteration]: 150, [LOSS]: 0.118974
[iteration]: 160, [LOSS]: 0.216392
[iteration]: 170, [LOSS]: 0.230799
[iteration]: 180, [LOSS]: 0.150670
[iteration]: 190, [LOSS]: 0.204054
Epoch 1/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 1s 1ms/step - loss: 0.0701 - val_loss: 0.0308
Epoch 2/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 0s 1ms/step - loss: 0.0278 - val_loss: 0.0218
Epoch 3/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 0s 1ms/step - loss: 0.0200 - val_loss: 0.0181
Epoch 4/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 0s 970us/step - loss: 0.0169 - val_loss: 0.0159
Epoch 5/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 0s 989us/step - loss: 0.0150 - val_loss: 0.0144
Epoch 6/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 1s 1ms/step - loss: 0.0139 - val_loss: 0.0136
Epoch 7/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 0s 1ms/step - loss: 0.0130 - val_loss: 0.0129
Epoch 8/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 0s 1ms/step - loss: 0.0124 - val_loss: 0.0122
Epoch 9/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 0s 1ms/step - loss: 0.0120 - val_loss: 0.0119
Epoch 10/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 1s 1ms/step - loss: 0.0116 - val_loss: 0.0116
[iteration]: 0, [LOSS]: 0.675849
[iteration]: 10, [LOSS]: 0.683337
[iteration]: 20, [LOSS]: 0.719699
[iteration]: 30, [LOSS]: 0.662163
[iteration]: 40, [LOSS]: 0.631985
[iteration]: 50, [LOSS]: 0.587698
[iteration]: 60, [LOSS]: 0.528811
[iteration]: 70, [LOSS]: 0.471510
[iteration]: 80, [LOSS]: 0.505003
[iteration]: 90, [LOSS]: 0.395969
[iteration]: 100, [LOSS]: 0.366321
[iteration]: 110, [LOSS]: 0.236837
[iteration]: 120, [LOSS]: 0.404763
[iteration]: 130, [LOSS]: 0.306200
[iteration]: 140, [LOSS]: 0.296489
[iteration]: 150, [LOSS]: 0.229005
[iteration]: 160, [LOSS]: 0.152154
[iteration]: 170, [LOSS]: 0.284832
[iteration]: 180, [LOSS]: 0.255644
[iteration]: 190, [LOSS]: 0.188249
[iteration]: 0, [LOSS]: 0.840009
[iteration]: 10, [LOSS]: 0.801199
[iteration]: 20, [LOSS]: 0.686186
[iteration]: 30, [LOSS]: 0.568808
[iteration]: 40, [LOSS]: 0.481289
[iteration]: 50, [LOSS]: 0.575734
[iteration]: 60, [LOSS]: 0.433821
[iteration]: 70, [LOSS]: 0.553517
[iteration]: 80, [LOSS]: 0.425860
[iteration]: 90, [LOSS]: 0.444707
[iteration]: 100, [LOSS]: 0.593897
[iteration]: 110, [LOSS]: 0.409689
[iteration]: 120, [LOSS]: 0.628394
[iteration]: 130, [LOSS]: 0.307800
[iteration]: 140, [LOSS]: 0.278779
[iteration]: 150, [LOSS]: 0.341728
[iteration]: 160, [LOSS]: 0.295085
[iteration]: 170, [LOSS]: 0.416076
[iteration]: 180, [LOSS]: 0.283843
[iteration]: 190, [LOSS]: 0.280860
Epoch 1/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 1s 1ms/step - loss: 0.0806 - val_loss: 0.0325
Epoch 2/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 1s 1ms/step - loss: 0.0305 - val_loss: 0.0262
Epoch 3/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 1s 1ms/step - loss: 0.0249 - val_loss: 0.0226
Epoch 4/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 1s 1ms/step - loss: 0.0215 - val_loss: 0.0206
Epoch 5/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 0s 1ms/step - loss: 0.0201 - val_loss: 0.0194
Epoch 6/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 0s 940us/step - loss: 0.0190 - val_loss: 0.0186
Epoch 7/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 1s 980us/step - loss: 0.0181 - val_loss: 0.0180
Epoch 8/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 1s 1ms/step - loss: 0.0176 - val_loss: 0.0175
Epoch 9/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 0s 1ms/step - loss: 0.0171 - val_loss: 0.0171
Epoch 10/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 1s 919us/step - loss: 0.0167 - val_loss: 0.0168
[iteration]: 0, [LOSS]: 0.642286
[iteration]: 10, [LOSS]: 0.742766
[iteration]: 20, [LOSS]: 0.633308
[iteration]: 30, [LOSS]: 0.544834
[iteration]: 40, [LOSS]: 0.659850
[iteration]: 50, [LOSS]: 0.472925
[iteration]: 60, [LOSS]: 0.493642
[iteration]: 70, [LOSS]: 0.438447
[iteration]: 80, [LOSS]: 0.441382
[iteration]: 90, [LOSS]: 0.544536
[iteration]: 100, [LOSS]: 0.568962
[iteration]: 110, [LOSS]: 0.395242
[iteration]: 120, [LOSS]: 0.382350
[iteration]: 130, [LOSS]: 0.319223
[iteration]: 140, [LOSS]: 0.490586
[iteration]: 150, [LOSS]: 0.340140
[iteration]: 160, [LOSS]: 0.355104
[iteration]: 170, [LOSS]: 0.365440
[iteration]: 180, [LOSS]: 0.452400
[iteration]: 190, [LOSS]: 0.373520
[iteration]: 0, [LOSS]: 0.727209
[iteration]: 10, [LOSS]: 0.705013
[iteration]: 20, [LOSS]: 0.677225
[iteration]: 30, [LOSS]: 0.681562
[iteration]: 40, [LOSS]: 0.649280
[iteration]: 50, [LOSS]: 0.593860
[iteration]: 60, [LOSS]: 0.603086
[iteration]: 70, [LOSS]: 0.567723
[iteration]: 80, [LOSS]: 0.502087
[iteration]: 90, [LOSS]: 0.413122
[iteration]: 100, [LOSS]: 0.419752
[iteration]: 110, [LOSS]: 0.256711
[iteration]: 120, [LOSS]: 0.325010
[iteration]: 130, [LOSS]: 0.296549
[iteration]: 140, [LOSS]: 0.221051
[iteration]: 150, [LOSS]: 0.463161
[iteration]: 160, [LOSS]: 0.332190
[iteration]: 170, [LOSS]: 0.479340
[iteration]: 180, [LOSS]: 0.248093
[iteration]: 190, [LOSS]: 0.143688
Epoch 1/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 1s 1ms/step - loss: 0.0704 - val_loss: 0.0309
Epoch 2/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 1s 1ms/step - loss: 0.0273 - val_loss: 0.0212
Epoch 3/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 0s 1ms/step - loss: 0.0199 - val_loss: 0.0181
Epoch 4/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 1s 1ms/step - loss: 0.0174 - val_loss: 0.0161
Epoch 5/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 1s 1ms/step - loss: 0.0155 - val_loss: 0.0148
Epoch 6/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 0s 1ms/step - loss: 0.0143 - val_loss: 0.0137
Epoch 7/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 0s 1ms/step - loss: 0.0132 - val_loss: 0.0128
Epoch 8/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 0s 1ms/step - loss: 0.0125 - val_loss: 0.0124
Epoch 9/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 0s 1ms/step - loss: 0.0120 - val_loss: 0.0119
Epoch 10/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 1s 1ms/step - loss: 0.0118 - val_loss: 0.0117
[iteration]: 0, [LOSS]: 0.682230
[iteration]: 10, [LOSS]: 0.658926
[iteration]: 20, [LOSS]: 0.607854
[iteration]: 30, [LOSS]: 0.581581
[iteration]: 40, [LOSS]: 0.529634
[iteration]: 50, [LOSS]: 0.404506
[iteration]: 60, [LOSS]: 0.315447
[iteration]: 70, [LOSS]: 0.361972
[iteration]: 80, [LOSS]: 0.425541
[iteration]: 90, [LOSS]: 0.182714
[iteration]: 100, [LOSS]: 0.154918
[iteration]: 110, [LOSS]: 0.225182
[iteration]: 120, [LOSS]: 0.196318
[iteration]: 130, [LOSS]: 0.167399
[iteration]: 140, [LOSS]: 0.108822
[iteration]: 150, [LOSS]: 0.321977
[iteration]: 160, [LOSS]: 0.108737
[iteration]: 170, [LOSS]: 0.101276
[iteration]: 180, [LOSS]: 0.115499
[iteration]: 190, [LOSS]: 0.185220
[iteration]: 0, [LOSS]: 0.695658
[iteration]: 10, [LOSS]: 0.694549
[iteration]: 20, [LOSS]: 0.672642
[iteration]: 30, [LOSS]: 0.625898
[iteration]: 40, [LOSS]: 0.479747
[iteration]: 50, [LOSS]: 0.565349
[iteration]: 60, [LOSS]: 0.465087
[iteration]: 70, [LOSS]: 0.437610
[iteration]: 80, [LOSS]: 0.393078
[iteration]: 90, [LOSS]: 0.422464
[iteration]: 100, [LOSS]: 0.534550
[iteration]: 110, [LOSS]: 0.384177
[iteration]: 120, [LOSS]: 0.575080
[iteration]: 130, [LOSS]: 0.410868
[iteration]: 140, [LOSS]: 0.322225
[iteration]: 150, [LOSS]: 0.375062
[iteration]: 160, [LOSS]: 0.290818
[iteration]: 170, [LOSS]: 0.343212
[iteration]: 180, [LOSS]: 0.273185
[iteration]: 190, [LOSS]: 0.319665
Epoch 1/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 1s 1ms/step - loss: 0.0806 - val_loss: 0.0345
Epoch 2/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 1s 1ms/step - loss: 0.0332 - val_loss: 0.0299
Epoch 3/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 1s 1ms/step - loss: 0.0283 - val_loss: 0.0253
Epoch 4/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 0s 944us/step - loss: 0.0241 - val_loss: 0.0228
Epoch 5/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 0s 1ms/step - loss: 0.0221 - val_loss: 0.0213
Epoch 6/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 0s 979us/step - loss: 0.0207 - val_loss: 0.0204
Epoch 7/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 0s 1ms/step - loss: 0.0197 - val_loss: 0.0197
Epoch 8/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 0s 966us/step - loss: 0.0191 - val_loss: 0.0190
Epoch 9/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 1s 1ms/step - loss: 0.0185 - val_loss: 0.0186
Epoch 10/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 0s 1ms/step - loss: 0.0182 - val_loss: 0.0183
[iteration]: 0, [LOSS]: 0.670346
[iteration]: 10, [LOSS]: 0.670956
[iteration]: 20, [LOSS]: 0.632788
[iteration]: 30, [LOSS]: 0.631273
[iteration]: 40, [LOSS]: 0.559265
[iteration]: 50, [LOSS]: 0.530936
[iteration]: 60, [LOSS]: 0.400052
[iteration]: 70, [LOSS]: 0.253400
[iteration]: 80, [LOSS]: 0.246871
[iteration]: 90, [LOSS]: 0.129530
[iteration]: 100, [LOSS]: 0.188777
[iteration]: 110, [LOSS]: 0.148166
[iteration]: 120, [LOSS]: 0.029339
[iteration]: 130, [LOSS]: 0.056762
[iteration]: 140, [LOSS]: 0.070406
[iteration]: 150, [LOSS]: 0.151719
[iteration]: 160, [LOSS]: 0.015580
[iteration]: 170, [LOSS]: 0.026759
[iteration]: 180, [LOSS]: 0.048598
[iteration]: 190, [LOSS]: 0.201687
[iteration]: 0, [LOSS]: 0.688220
[iteration]: 10, [LOSS]: 0.712034
[iteration]: 20, [LOSS]: 0.650668
[iteration]: 30, [LOSS]: 0.633225
[iteration]: 40, [LOSS]: 0.651999
[iteration]: 50, [LOSS]: 0.497930
[iteration]: 60, [LOSS]: 0.512472
[iteration]: 70, [LOSS]: 0.228398
[iteration]: 80, [LOSS]: 0.412405
[iteration]: 90, [LOSS]: 0.425608
[iteration]: 100, [LOSS]: 0.402591
[iteration]: 110, [LOSS]: 0.397287
[iteration]: 120, [LOSS]: 0.120580
[iteration]: 130, [LOSS]: 0.243656
[iteration]: 140, [LOSS]: 0.276401
[iteration]: 150, [LOSS]: 0.321823
[iteration]: 160, [LOSS]: 0.051099
[iteration]: 170, [LOSS]: 0.136494
[iteration]: 180, [LOSS]: 0.295478
[iteration]: 190, [LOSS]: 0.391206
Epoch 1/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 1s 1ms/step - loss: 0.0767 - val_loss: 0.0280
Epoch 2/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 1s 1ms/step - loss: 0.0250 - val_loss: 0.0214
Epoch 3/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 0s 1ms/step - loss: 0.0198 - val_loss: 0.0181
Epoch 4/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 0s 1ms/step - loss: 0.0173 - val_loss: 0.0166
Epoch 5/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 1s 1ms/step - loss: 0.0156 - val_loss: 0.0148
Epoch 6/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 1s 1ms/step - loss: 0.0141 - val_loss: 0.0137
Epoch 7/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 1s 1ms/step - loss: 0.0130 - val_loss: 0.0126
Epoch 8/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 0s 1ms/step - loss: 0.0121 - val_loss: 0.0121
Epoch 9/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 0s 987us/step - loss: 0.0118 - val_loss: 0.0119
Epoch 10/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 0s 1ms/step - loss: 0.0116 - val_loss: 0.0116
[iteration]: 0, [LOSS]: 0.737773
[iteration]: 10, [LOSS]: 0.678961
[iteration]: 20, [LOSS]: 0.617849
[iteration]: 30, [LOSS]: 0.503478
[iteration]: 40, [LOSS]: 0.429657
[iteration]: 50, [LOSS]: 0.246446
[iteration]: 60, [LOSS]: 0.279752
[iteration]: 70, [LOSS]: 0.144855
[iteration]: 80, [LOSS]: 0.185239
[iteration]: 90, [LOSS]: 0.282476
[iteration]: 100, [LOSS]: 0.163283
[iteration]: 110, [LOSS]: 0.114661
[iteration]: 120, [LOSS]: 0.244923
[iteration]: 130, [LOSS]: 0.352353
[iteration]: 140, [LOSS]: 0.161937
[iteration]: 150, [LOSS]: 0.099237
[iteration]: 160, [LOSS]: 0.109951
[iteration]: 170, [LOSS]: 0.038028
[iteration]: 180, [LOSS]: 0.210633
[iteration]: 190, [LOSS]: 0.079147
[iteration]: 0, [LOSS]: 0.805533
[iteration]: 10, [LOSS]: 0.657735
[iteration]: 20, [LOSS]: 0.746927
[iteration]: 30, [LOSS]: 0.661955
[iteration]: 40, [LOSS]: 0.618968
[iteration]: 50, [LOSS]: 0.595123
[iteration]: 60, [LOSS]: 0.533105
[iteration]: 70, [LOSS]: 0.473472
[iteration]: 80, [LOSS]: 0.424525
[iteration]: 90, [LOSS]: 0.419597
[iteration]: 100, [LOSS]: 0.358228
[iteration]: 110, [LOSS]: 0.368373
[iteration]: 120, [LOSS]: 0.398956
[iteration]: 130, [LOSS]: 0.307159
[iteration]: 140, [LOSS]: 0.344268
[iteration]: 150, [LOSS]: 0.371409
[iteration]: 160, [LOSS]: 0.193872
[iteration]: 170, [LOSS]: 0.272285
[iteration]: 180, [LOSS]: 0.257878
[iteration]: 190, [LOSS]: 0.282172
Epoch 1/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 1s 1ms/step - loss: 0.0774 - val_loss: 0.0334
Epoch 2/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 0s 918us/step - loss: 0.0320 - val_loss: 0.0269
Epoch 3/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 0s 939us/step - loss: 0.0252 - val_loss: 0.0223
Epoch 4/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 1s 921us/step - loss: 0.0214 - val_loss: 0.0201
Epoch 5/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 1s 1ms/step - loss: 0.0193 - val_loss: 0.0185
Epoch 6/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 0s 934us/step - loss: 0.0179 - val_loss: 0.0176
Epoch 7/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 1s 1ms/step - loss: 0.0172 - val_loss: 0.0170
Epoch 8/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 1s 2ms/step - loss: 0.0165 - val_loss: 0.0165
Epoch 9/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 0s 1ms/step - loss: 0.0162 - val_loss: 0.0161
Epoch 10/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 1s 949us/step - loss: 0.0159 - val_loss: 0.0158
[iteration]: 0, [LOSS]: 0.699155
[iteration]: 10, [LOSS]: 0.699155
[iteration]: 20, [LOSS]: 0.692645
[iteration]: 30, [LOSS]: 0.690697
[iteration]: 40, [LOSS]: 0.692350
[iteration]: 50, [LOSS]: 0.692240
[iteration]: 60, [LOSS]: 0.695396
[iteration]: 70, [LOSS]: 0.685546
[iteration]: 80, [LOSS]: 0.712609
[iteration]: 90, [LOSS]: 0.699155
[iteration]: 100, [LOSS]: 0.695753
[iteration]: 110, [LOSS]: 0.692500
[iteration]: 120, [LOSS]: 0.693999
[iteration]: 130, [LOSS]: 0.693454
[iteration]: 140, [LOSS]: 0.692600
[iteration]: 150, [LOSS]: 0.692350
[iteration]: 160, [LOSS]: 0.692601
[iteration]: 170, [LOSS]: 0.695348
[iteration]: 180, [LOSS]: 0.698345
[iteration]: 190, [LOSS]: 0.710889
[iteration]: 0, [LOSS]: 0.743063
[iteration]: 10, [LOSS]: 0.633358
[iteration]: 20, [LOSS]: 0.642633
[iteration]: 30, [LOSS]: 0.625490
[iteration]: 40, [LOSS]: 0.595915
[iteration]: 50, [LOSS]: 0.452318
[iteration]: 60, [LOSS]: 0.478984
[iteration]: 70, [LOSS]: 0.408920
[iteration]: 80, [LOSS]: 0.400471
[iteration]: 90, [LOSS]: 0.581330
[iteration]: 100, [LOSS]: 0.484597
[iteration]: 110, [LOSS]: 0.350492
[iteration]: 120, [LOSS]: 0.468707
[iteration]: 130, [LOSS]: 0.197719
[iteration]: 140, [LOSS]: 0.121923
[iteration]: 150, [LOSS]: 0.264998
[iteration]: 160, [LOSS]: 0.186627
[iteration]: 170, [LOSS]: 0.146614
[iteration]: 180, [LOSS]: 0.289298
[iteration]: 190, [LOSS]: 0.146886
Epoch 1/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 1s 2ms/step - loss: 0.0671 - val_loss: 0.0294
Epoch 2/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 0s 1ms/step - loss: 0.0267 - val_loss: 0.0212
Epoch 3/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 1s 1ms/step - loss: 0.0198 - val_loss: 0.0176
Epoch 4/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 0s 1ms/step - loss: 0.0169 - val_loss: 0.0156
Epoch 5/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 1s 1ms/step - loss: 0.0150 - val_loss: 0.0140
Epoch 6/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 1s 1ms/step - loss: 0.0133 - val_loss: 0.0129
Epoch 7/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 1s 1ms/step - loss: 0.0125 - val_loss: 0.0121
Epoch 8/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 1s 1ms/step - loss: 0.0118 - val_loss: 0.0115
Epoch 9/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 0s 1ms/step - loss: 0.0113 - val_loss: 0.0112
Epoch 10/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 0s 1ms/step - loss: 0.0109 - val_loss: 0.0110
[iteration]: 0, [LOSS]: 0.647857
[iteration]: 10, [LOSS]: 0.691282
[iteration]: 20, [LOSS]: 0.676396
[iteration]: 30, [LOSS]: 0.755217
[iteration]: 40, [LOSS]: 0.687904
[iteration]: 50, [LOSS]: 0.640946
[iteration]: 60, [LOSS]: 0.673297
[iteration]: 70, [LOSS]: 0.625896
[iteration]: 80, [LOSS]: 0.653624
[iteration]: 90, [LOSS]: 0.622420
[iteration]: 100, [LOSS]: 0.541231
[iteration]: 110, [LOSS]: 0.645860
[iteration]: 120, [LOSS]: 0.577490
[iteration]: 130, [LOSS]: 0.579729
[iteration]: 140, [LOSS]: 0.460512
[iteration]: 150, [LOSS]: 0.559595
[iteration]: 160, [LOSS]: 0.483571
[iteration]: 170, [LOSS]: 0.480887
[iteration]: 180, [LOSS]: 0.415953
[iteration]: 190, [LOSS]: 0.433771
[iteration]: 0, [LOSS]: 0.699602
[iteration]: 10, [LOSS]: 0.670680
[iteration]: 20, [LOSS]: 0.632784
[iteration]: 30, [LOSS]: 0.615135
[iteration]: 40, [LOSS]: 0.554832
[iteration]: 50, [LOSS]: 0.416270
[iteration]: 60, [LOSS]: 0.429715
[iteration]: 70, [LOSS]: 0.375870
[iteration]: 80, [LOSS]: 0.366275
[iteration]: 90, [LOSS]: 0.399374
[iteration]: 100, [LOSS]: 0.392746
[iteration]: 110, [LOSS]: 0.341359
[iteration]: 120, [LOSS]: 0.422462
[iteration]: 130, [LOSS]: 0.299591
[iteration]: 140, [LOSS]: 0.189027
[iteration]: 150, [LOSS]: 0.356096
[iteration]: 160, [LOSS]: 0.332129
[iteration]: 170, [LOSS]: 0.236116
[iteration]: 180, [LOSS]: 0.161675
[iteration]: 190, [LOSS]: 0.412666
Epoch 1/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 1s 1ms/step - loss: 0.0805 - val_loss: 0.0306
Epoch 2/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 1s 968us/step - loss: 0.0285 - val_loss: 0.0253
Epoch 3/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 0s 993us/step - loss: 0.0242 - val_loss: 0.0215
Epoch 4/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 1s 921us/step - loss: 0.0204 - val_loss: 0.0190
Epoch 5/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 1s 1ms/step - loss: 0.0187 - val_loss: 0.0176
Epoch 6/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 0s 991us/step - loss: 0.0172 - val_loss: 0.0168
Epoch 7/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 1s 942us/step - loss: 0.0164 - val_loss: 0.0162
Epoch 8/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 1s 987us/step - loss: 0.0159 - val_loss: 0.0157
Epoch 9/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 1s 1ms/step - loss: 0.0155 - val_loss: 0.0153
Epoch 10/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 1s 994us/step - loss: 0.0150 - val_loss: 0.0150
[iteration]: 0, [LOSS]: 0.672955
[iteration]: 10, [LOSS]: 0.658146
[iteration]: 20, [LOSS]: 0.624965
[iteration]: 30, [LOSS]: 0.478894
[iteration]: 40, [LOSS]: 0.413549
[iteration]: 50, [LOSS]: 0.376407
[iteration]: 60, [LOSS]: 0.262492
[iteration]: 70, [LOSS]: 0.385754
[iteration]: 80, [LOSS]: 0.299710
[iteration]: 90, [LOSS]: 0.160725
[iteration]: 100, [LOSS]: 0.253750
[iteration]: 110, [LOSS]: 0.171561
[iteration]: 120, [LOSS]: 0.104670
[iteration]: 130, [LOSS]: 0.210922
[iteration]: 140, [LOSS]: 0.074687
[iteration]: 150, [LOSS]: 0.205368
[iteration]: 160, [LOSS]: 0.074308
[iteration]: 170, [LOSS]: 0.141006
[iteration]: 180, [LOSS]: 0.137485
[iteration]: 190, [LOSS]: 0.146437
[iteration]: 0, [LOSS]: 0.671169
[iteration]: 10, [LOSS]: 0.662479
[iteration]: 20, [LOSS]: 0.671405
[iteration]: 30, [LOSS]: 0.564264
[iteration]: 40, [LOSS]: 0.515214
[iteration]: 50, [LOSS]: 0.577441
[iteration]: 60, [LOSS]: 0.475522
[iteration]: 70, [LOSS]: 0.472532
[iteration]: 80, [LOSS]: 0.402184
[iteration]: 90, [LOSS]: 0.373168
[iteration]: 100, [LOSS]: 0.382791
[iteration]: 110, [LOSS]: 0.379924
[iteration]: 120, [LOSS]: 0.436714
[iteration]: 130, [LOSS]: 0.340488
[iteration]: 140, [LOSS]: 0.165777
[iteration]: 150, [LOSS]: 0.176971
[iteration]: 160, [LOSS]: 0.184085
[iteration]: 170, [LOSS]: 0.182796
[iteration]: 180, [LOSS]: 0.174073
[iteration]: 190, [LOSS]: 0.172949
Epoch 1/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 1s 2ms/step - loss: 0.0717 - val_loss: 0.0290
Epoch 2/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 0s 1ms/step - loss: 0.0255 - val_loss: 0.0196
Epoch 3/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 1s 986us/step - loss: 0.0183 - val_loss: 0.0173
Epoch 4/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 1s 1ms/step - loss: 0.0163 - val_loss: 0.0156
Epoch 5/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 0s 1ms/step - loss: 0.0148 - val_loss: 0.0142
Epoch 6/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 1s 1ms/step - loss: 0.0135 - val_loss: 0.0131
Epoch 7/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 0s 1ms/step - loss: 0.0125 - val_loss: 0.0124
Epoch 8/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 0s 1ms/step - loss: 0.0120 - val_loss: 0.0120
Epoch 9/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 1s 1ms/step - loss: 0.0116 - val_loss: 0.0117
Epoch 10/10
375/375 ━━━━━━━━━━━━━━━━━━━━ 0s 1ms/step - loss: 0.0113 - val_loss: 0.0115
[iteration]: 0, [LOSS]: 0.734965
[iteration]: 10, [LOSS]: 0.723683
[iteration]: 20, [LOSS]: 0.703081
[iteration]: 30, [LOSS]: 0.689690
[iteration]: 40, [LOSS]: 0.696715
[iteration]: 50, [LOSS]: 0.689690
[iteration]: 60, [LOSS]: 0.693777
[iteration]: 70, [LOSS]: 0.692386
[iteration]: 80, [LOSS]: 0.693429
[iteration]: 90, [LOSS]: 0.705169
[iteration]: 100, [LOSS]: 0.696682
[iteration]: 110, [LOSS]: 0.698803
[iteration]: 120, [LOSS]: 0.690316
[iteration]: 130, [LOSS]: 0.696682
[iteration]: 140, [LOSS]: 0.693951
[iteration]: 150, [LOSS]: 0.698090
[iteration]: 160, [LOSS]: 0.709413
[iteration]: 170, [LOSS]: 0.698804
[iteration]: 180, [LOSS]: 0.693777
[iteration]: 190, [LOSS]: 0.687012
