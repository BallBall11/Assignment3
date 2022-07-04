

## Results

### 1

    python main.py --epochs=5 --lr=1e-2 --dim=32 --n_layer=1 --batch_size=32

- Best Epoch: 4
- Best Test MAE: 0.2833066341036322

### 2

    python main.py --epochs=5 --lr=1e-2 --dim=32 --n_layer=2 --batch_size=32

- Best Epoch: 1
- Best Test MAE: 1.0437957915823035

### 3

    python main.py --epochs=5 --lr=1e-3 --dim=32 --n_layer=1 --batch_size=32

- Best Epoch: 4
- Best Test MAE: 0.09768018915364643


### 4

    python main.py --epochs=5 --lr=1e-4 --dim=32 --n_layer=1 --batch_size=32 

- Best Epoch: 4
- Best Test MAE: 0.12545252370213594

### 5

    python main.py --epochs=5 --lr=1e-3 --dim=32 --n_layer=2 --batch_size=32

- Best Epoch: 4
- Best Test MAE: 0.06979661388043254

### 6

    python main.py --epochs=5 --lr=1e-3 --dim=32 --n_layer=3 --batch_size=32

- Best Epoch: 4
- Best Test MAE: 0.08007083530406654

### 7

    python main.py --epochs=5 --lr=1e-3 --dim=64 --n_layer=2 --batch_size=32

- Best Epoch: 4
- Best Test MAE: 0.05709451568521805

### 8

    python main.py --epochs=5 --lr=1e-3 --dim=64 --n_layer=4 --batch_size=32

- Best Epoch: 4
- Best Test MAE: 0.05227192343464519

### 9

    python main.py --epochs=5 --lr=1e-3 --dim=128 --n_layer=4 --batch_size=32

Fail

### 10 
    python main.py --epochs=50 --lr=1e-3 --dim=64 --n_layer=4 --batch_size=32

fail

### 11

    python main.py --epochs=20 --lr=1e-3 --dim=64 --n_layer=2 --batch_size=32

- Epoch: 001, Train MAE: 3.8365941, Validation MAE: 3.8656112, Test MAE: 3.8682546
- Epoch: 002, Train MAE: 0.3726896, Validation MAE: 0.4899678, Test MAE: 0.4914583
- Epoch: 003, Train MAE: 0.2608043, Validation MAE: 0.1658866, Test MAE: 0.1666761
- Epoch: 004, Train MAE: 0.2042616, Validation MAE: 0.0828673, Test MAE: 0.0838538
- Epoch: 005, Train MAE: 0.1673602, Validation MAE: 0.0568399, Test MAE: 0.0576503
- Epoch: 006, Train MAE: 0.1514585, Validation MAE: 0.0481662, Test MAE: 0.0486236
- Epoch: 007, Train MAE: 0.1313687, Validation MAE: 0.0444712, Test MAE: 0.0452075
- Epoch: 008, Train MAE: 0.1208547, Validation MAE: 0.0422192, Test MAE: 0.0425377
- Epoch: 009, Train MAE: 0.1091342, Validation MAE: 0.0411804, Test MAE: 0.0413260
- Epoch: 010, Train MAE: 0.1064709, Validation MAE: 0.0401834, Test MAE: 0.0407670
- Epoch: 011, Train MAE: 0.0969114, Validation MAE: 0.0398979, Test MAE: 0.0399527
- Epoch: 012, Train MAE: 0.0957903, Validation MAE: 0.0409461, Test MAE: 0.0399527
- Best Epoch: 11
- Best Test MAE: 0.0399527

### 12

    python main.py --epochs=20 --lr=1e-3 --dim=32 --n_layer=2 --batch_size=32

- Epoch: 001, Train MAE: 5.0583523, Validation MAE: 5.2677711, Test MAE: 5.2702005
- Epoch: 002, Train MAE: 0.4940053, Validation MAE: 0.6417031, Test MAE: 0.6443989
- Epoch: 003, Train MAE: 0.3031507, Validation MAE: 0.2408707, Test MAE: 0.2409526
- Epoch: 004, Train MAE: 0.2382170, Validation MAE: 0.1245616, Test MAE: 0.1248968
- Epoch: 005, Train MAE: 0.2041459, Validation MAE: 0.0789450, Test MAE: 0.0802061
- Epoch: 006, Train MAE: 0.1674932, Validation MAE: 0.0582323, Test MAE: 0.0594693
- Epoch: 007, Train MAE: 0.1466426, Validation MAE: 0.0512209, Test MAE: 0.0518112
- Epoch: 008, Train MAE: 0.1379513, Validation MAE: 0.0480095, Test MAE: 0.0485888
- Best Epoch: 11
- Best Test MAE: 0.0399527

### 13

    python main.py --epochs=20 --lr=1e-3 --dim=32 --n_layer=1 --batch_size=32 

- Epoch: 001, Train MAE: 5.9859721, Validation MAE: 8.2237814, Test MAE: 8.2268832 Time: 0.01 min
- Epoch: 002, Train MAE: 0.5579650, Validation MAE: 0.6764679, Test MAE: 0.6803953 Time: 0.02 min
- Epoch: 003, Train MAE: 0.3869099, Validation MAE: 0.2374880, Test MAE: 0.2397322 Time: 0.03 min
- Epoch: 004, Train MAE: 0.3027962, Validation MAE: 0.1310288, Test MAE: 0.1330707 Time: 0.03 min
- Epoch: 005, Train MAE: 0.2668934, Validation MAE: 0.0978159, Test MAE: 0.0992391 Time: 0.04 min
- Epoch: 006, Train MAE: 0.2198983, Validation MAE: 0.0788560, Test MAE: 0.0793610 Time: 0.05 min
- Epoch: 007, Train MAE: 0.2027965, Validation MAE: 0.0629866, Test MAE: 0.0640651 Time: 0.06 min
- Epoch: 008, Train MAE: 0.1687065, Validation MAE: 0.0568674, Test MAE: 0.0574430 Time: 0.07 min
- Epoch: 009, Train MAE: 0.1624415, Validation MAE: 0.0530299, Test MAE: 0.0533510 Time: 0.08 min
- Epoch: 010, Train MAE: 0.1596984, Validation MAE: 0.0502441, Test MAE: 0.0507726 Time: 0.09 min
- Epoch: 011, Train MAE: 0.1418414, Validation MAE: 0.0478519, Test MAE: 0.0483537 Time: 0.09 min
- Epoch: 012, Train MAE: 0.1349709, Validation MAE: 0.0462541, Test MAE: 0.0464973 Time: 0.10 min
- Epoch: 013, Train MAE: 0.1340593, Validation MAE: 0.0461559, Test MAE: 0.0465256 Time: 0.11 min
- Epoch: 014, Train MAE: 0.1235495, Validation MAE: 0.0452526, Test MAE: 0.0454611 Time: 0.12 min
- Epoch: 015, Train MAE: 0.1170691, Validation MAE: 0.0441752, Test MAE: 0.0442069 Time: 0.13 min
- Epoch: 016, Train MAE: 0.1175802, Validation MAE: 0.0430341, Test MAE: 0.0430697 Time: 0.14 min
- Epoch: 017, Train MAE: 0.1117471, Validation MAE: 0.0420966, Test MAE: 0.0423946 Time: 0.15 min
- Epoch: 018, Train MAE: 0.1075959, Validation MAE: 0.0413009, Test MAE: 0.0419670 Time: 0.15 min
- Epoch: 019, Train MAE: 0.1052134, Validation MAE: 0.0412585, Test MAE: 0.0414677 Time: 0.16 min
- Epoch: 020, Train MAE: 0.0982746, Validation MAE: 0.0394806, Test MAE: 0.0398026 Time: 0.17 min
- Best Epoch: 19
- Best Test MAE: 0.0398026208293789

### 14

    python main.py --epochs=20 --lr=1e-4 --dim=32 --n_layer=2 --batch_size=32 

- Epoch: 001, Train MAE: 12.8587687, Validation MAE: 8.3052920, Test MAE: 8.3047683 Time: 0.01 min
- Epoch: 002, Train MAE: 0.3132788, Validation MAE: 0.3264260, Test MAE: 0.3307344 Time: 0.02 min
- Epoch: 003, Train MAE: 0.2512410, Validation MAE: 0.1488345, Test MAE: 0.1529491 Time: 0.04 min
- Epoch: 004, Train MAE: 0.2252946, Validation MAE: 0.1272782, Test MAE: 0.1303432 Time: 0.05 min
- Epoch: 005, Train MAE: 0.2068072, Validation MAE: 0.1129760, Test MAE: 0.1159911 Time: 0.06 min
- Epoch: 006, Train MAE: 0.1840037, Validation MAE: 0.1008086, Test MAE: 0.1039156 Time: 0.08 min
- Epoch: 007, Train MAE: 0.1776727, Validation MAE: 0.0928219, Test MAE: 0.0952026 Time: 0.09 min
- Epoch: 008, Train MAE: 0.1645891, Validation MAE: 0.0860555, Test MAE: 0.0879033 Time: 0.10 min
- Epoch: 009, Train MAE: 0.1579562, Validation MAE: 0.0811592, Test MAE: 0.0828948 Time: 0.12 min
- Epoch: 010, Train MAE: 0.1464254, Validation MAE: 0.0768183, Test MAE: 0.0786885 Time: 0.13 min
- Epoch: 011, Train MAE: 0.1416267, Validation MAE: 0.0728045, Test MAE: 0.0747883 Time: 0.14 min
- Epoch: 012, Train MAE: 0.1309782, Validation MAE: 0.0693261, Test MAE: 0.0711291 Time: 0.15 min
- Epoch: 013, Train MAE: 0.1308312, Validation MAE: 0.0663207, Test MAE: 0.0685036 Time: 0.17 min
- Epoch: 014, Train MAE: 0.1232326, Validation MAE: 0.0636664, Test MAE: 0.0655367 Time: 0.18 min
- Epoch: 015, Train MAE: 0.1171657, Validation MAE: 0.0611089, Test MAE: 0.0631064 Time: 0.19 min
- Epoch: 016, Train MAE: 0.1201725, Validation MAE: 0.0593794, Test MAE: 0.0615033 Time: 0.20 min
- Epoch: 017, Train MAE: 0.1152095, Validation MAE: 0.0572887, Test MAE: 0.0594166 Time: 0.22 min
- Epoch: 018, Train MAE: 0.1085799, Validation MAE: 0.0554970, Test MAE: 0.0575157 Time: 0.23 min
- Epoch: 019, Train MAE: 0.1092546, Validation MAE: 0.0538478, Test MAE: 0.0558467 Time: 0.24 min
- Epoch: 020, Train MAE: 0.1033244, Validation MAE: 0.0521400, Test MAE: 0.0541293 Time: 0.26 min
- Best Epoch: 19
- Best Test MAE: 0.054129291555908135

### 15

    python main.py --epochs=20 --lr=1e-3 --dim=32 --n_layer=2 --batch_size=32

- Epoch: 001, Train MAE: 5.0586532, Validation MAE: 5.3184958, Test MAE: 5.3203039, Time(min): 11.88
- Epoch: 002, Train MAE: 0.4929627, Validation MAE: 0.6354334, Test MAE: 0.6378682, Time(min): 23.49
- Epoch: 003, Train MAE: 0.3032683, Validation MAE: 0.2344732, Test MAE: 0.2347256, Time(min): 35.08
- Epoch: 004, Train MAE: 0.2398193, Validation MAE: 0.1209201, Test MAE: 0.1210221, Time(min): 46.77
- Epoch: 005, Train MAE: 0.1970379, Validation MAE: 0.0803819, Test MAE: 0.0807861, Time(min): 59.19
- Epoch: 006, Train MAE: 0.1735681, Validation MAE: 0.0607522, Test MAE: 0.0617534, Time(min): 71.46
- Epoch: 007, Train MAE: 0.1441696, Validation MAE: 0.0508332, Test MAE: 0.0521074, Time(min): 83.70
- Epoch: 008, Train MAE: 0.1484952, Validation MAE: 0.0476389, Test MAE: 0.0488817, Time(min): 97.94
- Epoch: 009, Train MAE: 0.1220367, Validation MAE: 0.0441451, Test MAE: 0.0452350, Time(min): 109.67
- Epoch: 010, Train MAE: 0.1160830, Validation MAE: 0.0426301, Test MAE: 0.0436594, Time(min): 122.22
- Epoch: 011, Train MAE: 0.1113575, Validation MAE: 0.0419388, Test MAE: 0.0428633, Time(min): 136.97
- Epoch: 012, Train MAE: 0.1041467, Validation MAE: 0.0401465, Test MAE: 0.0412954, Time(min): 150.97
- Epoch: 013, Train MAE: 0.0988520, Validation MAE: 0.0398287, Test MAE: 0.0405163, Time(min): 166.06
- Epoch: 014, Train MAE: 0.0945211, Validation MAE: 0.0393975, Test MAE: 0.0399870, Time(min): 181.09
- Epoch: 015, Train MAE: 0.0922880, Validation MAE: 0.0379560, Test MAE: 0.0385669, Time(min): 195.27
- Epoch: 016, Train MAE: 0.0919089, Validation MAE: 0.0377155, Test MAE: 0.0384939, Time(min): 207.68
- Epoch: 017, Train MAE: 0.0909932, Validation MAE: 0.0371147, Test MAE: 0.0376020, Time(min): 219.96
- Epoch: 018, Train MAE: 0.0837356, Validation MAE: 0.0365435, Test MAE: 0.0369648, Time(min): 232.58
- Epoch: 019, Train MAE: 0.0797067, Validation MAE: 0.0355593, Test MAE: 0.0362273, Time(min): 245.40
- Epoch: 020, Train MAE: 0.0793033, Validation MAE: 0.0347298, Test MAE: 0.0349593, Time(min): 257.77
- Best Epoch: 19
- Best Test MAE: 0.03495934878829972