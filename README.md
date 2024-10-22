[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/YFgwt0yY)
# MiniTorch Module 2

<img src="https://minitorch.github.io/minitorch.svg" width="50%">


* Docs: https://minitorch.github.io/

* Overview: https://minitorch.github.io/module2/module2/

This assignment requires the following files from the previous assignments. You can get these by running

```bash
python sync_previous_module.py previous-module-dir current-module-dir
```

The files that will be synced are:

        minitorch/operators.py minitorch/module.py minitorch/autodiff.py minitorch/scalar.py minitorch/scalar_functions.py minitorch/module.py project/run_manual.py project/run_scalar.py project/datasets.py



# Simple: Hidden Layers - 3, LR - 0.1
<img width="620" alt="Screen Shot 2024-10-22 at 11 51 17 AM" src="https://github.com/user-attachments/assets/f0875113-d60d-490e-9e46-a816239ed35b">
<img width="620" alt="Screen Shot 2024-10-22 at 11 51 33 AM" src="https://github.com/user-attachments/assets/94ca20bf-c62c-4d59-9609-a2c5d0ad073d">
Epoch: 0/500, loss: 0, correct: 0
Epoch: 0/500, loss: 0, correct: 0
Epoch: 10/500, loss: 33.90014186895832, correct: 30
Epoch: 20/500, loss: 32.87684706475986, correct: 30
Epoch: 30/500, loss: 31.139598952767376, correct: 33
Epoch: 40/500, loss: 29.182280799884836, correct: 44
Epoch: 50/500, loss: 27.34096822679483, correct: 45
Epoch: 60/500, loss: 25.292133641354656, correct: 46
Epoch: 70/500, loss: 23.001695531807677, correct: 47
Epoch: 80/500, loss: 20.524176621545855, correct: 47
Epoch: 90/500, loss: 18.095873460920245, correct: 48
Epoch: 100/500, loss: 15.903206872783626, correct: 48
Epoch: 110/500, loss: 13.983008762876374, correct: 48
Epoch: 120/500, loss: 12.362698193062657, correct: 48
Epoch: 130/500, loss: 11.009701337667092, correct: 48
Epoch: 140/500, loss: 9.887756824669028, correct: 48
Epoch: 150/500, loss: 8.95232266800934, correct: 48
Epoch: 160/500, loss: 8.165121376348484, correct: 48
Epoch: 170/500, loss: 7.498145070380774, correct: 48
Epoch: 180/500, loss: 6.930033697188108, correct: 48
Epoch: 190/500, loss: 6.4483645314020785, correct: 48
Epoch: 200/500, loss: 6.033093094461736, correct: 48
Epoch: 210/500, loss: 5.674423052960551, correct: 48
Epoch: 220/500, loss: 5.360661987905328, correct: 48
Epoch: 230/500, loss: 5.083655787344247, correct: 49
Epoch: 240/500, loss: 4.837527411218552, correct: 49
Epoch: 250/500, loss: 4.617605735448521, correct: 49
Epoch: 260/500, loss: 4.420415667645125, correct: 49
Epoch: 270/500, loss: 4.242968785777922, correct: 49
Epoch: 280/500, loss: 4.082206387905594, correct: 49
Epoch: 290/500, loss: 3.93590962231937, correct: 49
Epoch: 300/500, loss: 3.8022525112947476, correct: 49
Epoch: 310/500, loss: 3.6799729630627764, correct: 49
Epoch: 320/500, loss: 3.567354131251199, correct: 49
Epoch: 330/500, loss: 3.463441016483393, correct: 49
Epoch: 340/500, loss: 3.3671761264245514, correct: 49
Epoch: 350/500, loss: 3.2775692289011022, correct: 49
Epoch: 360/500, loss: 3.193904677435097, correct: 49
Epoch: 370/500, loss: 3.1155495120047445, correct: 49
Epoch: 380/500, loss: 3.0419416563307013, correct: 50
Epoch: 390/500, loss: 2.972617727407297, correct: 50
Epoch: 400/500, loss: 2.9071443505515084, correct: 50
Epoch: 410/500, loss: 2.8451524189431177, correct: 50
Epoch: 420/500, loss: 2.786321214032143, correct: 50
Epoch: 430/500, loss: 2.730368281722959, correct: 50
Epoch: 440/500, loss: 2.677044318894558, correct: 50
Epoch: 450/500, loss: 2.6264829038093014, correct: 50
Epoch: 460/500, loss: 2.578264917617907, correct: 50
Epoch: 470/500, loss: 2.5320373753670182, correct: 50
Epoch: 480/500, loss: 2.4876484887848043, correct: 50
Epoch: 490/500, loss: 2.444963022385433, correct: 50
Epoch: 500/500, loss: 2.4038601466912572, correct: 50


# Diag: Hidden Layers - 10, LR - 0.1
<img width="640" alt="Screen Shot 2024-10-22 at 11 58 48 AM" src="https://github.com/user-attachments/assets/b7c60bf5-bd1a-4269-9838-a0bf79041cf1">
<img width="622" alt="Screen Shot 2024-10-22 at 11 59 06 AM" src="https://github.com/user-attachments/assets/1f9e9d8c-dc5c-4a43-9e12-85fec250b82d">
Epoch: 0/500, loss: 0, correct: 0
Epoch: 0/500, loss: 0, correct: 0
Epoch: 0/500, loss: 0, correct: 0
Epoch: 10/500, loss: 16.786181592051236, correct: 41
Epoch: 20/500, loss: 13.08359065516649, correct: 41
Epoch: 30/500, loss: 10.605479745648282, correct: 47
Epoch: 40/500, loss: 8.958216124209097, correct: 48
Epoch: 50/500, loss: 7.729627782837035, correct: 49
Epoch: 60/500, loss: 6.760406095966336, correct: 50
Epoch: 70/500, loss: 5.983348211253961, correct: 50
Epoch: 80/500, loss: 5.345853978506023, correct: 50
Epoch: 90/500, loss: 4.813225919864256, correct: 50
Epoch: 100/500, loss: 4.362283225621026, correct: 50
Epoch: 110/500, loss: 3.975498636137551, correct: 50
Epoch: 120/500, loss: 3.641248743501012, correct: 50
Epoch: 130/500, loss: 3.351073112902617, correct: 50
Epoch: 140/500, loss: 3.0975608527416587, correct: 50
Epoch: 150/500, loss: 2.8734938580055194, correct: 50
Epoch: 160/500, loss: 2.6738252463508116, correct: 50
Epoch: 170/500, loss: 2.4955313050502888, correct: 50
Epoch: 180/500, loss: 2.3353127780210476, correct: 50
Epoch: 190/500, loss: 2.190810612209285, correct: 50
Epoch: 200/500, loss: 2.0600249143699756, correct: 50
Epoch: 210/500, loss: 1.9412504071477863, correct: 50
Epoch: 220/500, loss: 1.8328889620066777, correct: 50
Epoch: 230/500, loss: 1.7337223778440791, correct: 50
Epoch: 240/500, loss: 1.6427547519544408, correct: 50
Epoch: 250/500, loss: 1.5591268714585278, correct: 50
Epoch: 260/500, loss: 1.4818652228931515, correct: 50
Epoch: 270/500, loss: 1.4103055277041203, correct: 50
Epoch: 280/500, loss: 1.344074694189907, correct: 50
Epoch: 290/500, loss: 1.2822514728938335, correct: 50
Epoch: 300/500, loss: 1.2243671000870975, correct: 50
Epoch: 310/500, loss: 1.1704752171329875, correct: 50
Epoch: 320/500, loss: 1.1202266069465288, correct: 50
Epoch: 330/500, loss: 1.073296425938471, correct: 50
Epoch: 340/500, loss: 1.0294327993341115, correct: 50
Epoch: 350/500, loss: 0.9883599049059518, correct: 50
Epoch: 360/500, loss: 0.9498281937343959, correct: 50
Epoch: 370/500, loss: 0.9136346537319653, correct: 50
Epoch: 380/500, loss: 0.8795902395018171, correct: 50
Epoch: 390/500, loss: 0.8475990839123418, correct: 50
Epoch: 400/500, loss: 0.8175592526020736, correct: 50
Epoch: 410/500, loss: 0.7891903299017073, correct: 50
Epoch: 420/500, loss: 0.7623641268333302, correct: 50
Epoch: 430/500, loss: 0.7369565527713948, correct: 50
Epoch: 440/500, loss: 0.7128712752139067, correct: 50
Epoch: 450/500, loss: 0.6900542945942957, correct: 50
Epoch: 460/500, loss: 0.6684052348754834, correct: 50
Epoch: 470/500, loss: 0.647828373895168, correct: 50
Epoch: 480/500, loss: 0.628256326956907, correct: 50
Epoch: 490/500, loss: 0.6096239757023436, correct: 50
Epoch: 500/500, loss: 0.5918703636799213, correct: 50

# Split: Hidden Layers - 14, LR - 0.1
<img width="652" alt="Screen Shot 2024-10-22 at 12 06 44 PM" src="https://github.com/user-attachments/assets/367cfbb1-f4b0-4527-bda3-27f3158b56b2">
<img width="641" alt="Screen Shot 2024-10-22 at 12 07 27 PM" src="https://github.com/user-attachments/assets/36e8af69-010a-45fc-8013-f57faa4baafe">
Epoch: 0/500, loss: 0, correct: 0
Epoch: 0/500, loss: 0, correct: 0
Epoch: 0/500, loss: 0, correct: 0
Epoch: 10/500, loss: 33.497695435283525, correct: 35
Epoch: 20/500, loss: 32.9493945630666, correct: 32
Epoch: 30/500, loss: 32.384658138413116, correct: 30
Epoch: 40/500, loss: 31.961029396725017, correct: 29
Epoch: 50/500, loss: 31.51583115952465, correct: 31
Epoch: 60/500, loss: 31.07438827731796, correct: 33
Epoch: 70/500, loss: 30.64346813871073, correct: 32
Epoch: 80/500, loss: 30.184693110358893, correct: 33
Epoch: 90/500, loss: 29.706114718161125, correct: 35
Epoch: 100/500, loss: 29.203775804535535, correct: 35
Epoch: 110/500, loss: 28.6664863444121, correct: 35
Epoch: 120/500, loss: 28.090035067553817, correct: 37
Epoch: 130/500, loss: 27.485221630053836, correct: 39
Epoch: 140/500, loss: 26.84677297870359, correct: 40
Epoch: 150/500, loss: 26.1972915702961, correct: 40
Epoch: 160/500, loss: 25.53083295498568, correct: 40
Epoch: 170/500, loss: 24.8390613217122, correct: 40
Epoch: 180/500, loss: 23.792909939626664, correct: 41
Epoch: 190/500, loss: 22.94053781337004, correct: 41
Epoch: 200/500, loss: 22.11246813183605, correct: 42
Epoch: 210/500, loss: 21.28687697670251, correct: 43
Epoch: 220/500, loss: 20.46980081594766, correct: 45
Epoch: 230/500, loss: 19.655025283379505, correct: 46
Epoch: 240/500, loss: 18.854993844018885, correct: 47
Epoch: 250/500, loss: 18.076963721244542, correct: 48
Epoch: 260/500, loss: 17.312984045003525, correct: 48
Epoch: 270/500, loss: 16.57919927529208, correct: 48
Epoch: 280/500, loss: 15.86836370548994, correct: 48
Epoch: 290/500, loss: 15.198187841337761, correct: 48
Epoch: 300/500, loss: 14.567653727442561, correct: 48
Epoch: 310/500, loss: 13.975122617351126, correct: 48
Epoch: 320/500, loss: 13.417444612557542, correct: 48
Epoch: 330/500, loss: 12.893042271222876, correct: 48
Epoch: 340/500, loss: 12.401495116938458, correct: 49
Epoch: 350/500, loss: 11.939081101686357, correct: 49
Epoch: 360/500, loss: 11.503033007978, correct: 49
Epoch: 370/500, loss: 11.092612245383961, correct: 49
Epoch: 380/500, loss: 10.706182345458403, correct: 49
Epoch: 390/500, loss: 10.342605968573553, correct: 49
Epoch: 400/500, loss: 10.001275074174817, correct: 50
Epoch: 410/500, loss: 9.68311119354779, correct: 50
Epoch: 420/500, loss: 9.382479428978518, correct: 50
Epoch: 430/500, loss: 9.095457499261078, correct: 50
Epoch: 440/500, loss: 8.823824681353344, correct: 50
Epoch: 450/500, loss: 8.567983049018949, correct: 50
Epoch: 460/500, loss: 8.325055054295973, correct: 50
Epoch: 470/500, loss: 8.094274486850383, correct: 50
Epoch: 480/500, loss: 7.874674678218416, correct: 50
Epoch: 490/500, loss: 7.666649725141967, correct: 50
Epoch: 500/500, loss: 7.469857253359352, correct: 50


