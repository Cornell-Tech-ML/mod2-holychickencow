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

# Xor: Hidden Layers - 15, LR - 0.1

<img width="582" alt="Screen Shot 2024-10-22 at 12 35 37 PM" src="https://github.com/user-attachments/assets/c8edd682-1ab6-4f27-b8ae-196e8e7fb27a">
<img width="629" alt="Screen Shot 2024-10-22 at 12 35 50 PM" src="https://github.com/user-attachments/assets/464f5e5d-b802-4a87-8c45-e24d4c528756">
Epoch: 0/1000, loss: 0, correct: 0
Epoch: 10/1000, loss: 30.718122741956442, correct: 35
Epoch: 20/1000, loss: 29.58108417940489, correct: 35
Epoch: 30/1000, loss: 28.991943140229996, correct: 35
Epoch: 40/1000, loss: 28.39932220664864, correct: 35
Epoch: 50/1000, loss: 27.777721252282426, correct: 35
Epoch: 60/1000, loss: 27.05864781436699, correct: 36
Epoch: 70/1000, loss: 26.465971759576657, correct: 36
Epoch: 80/1000, loss: 25.90120021261901, correct: 36
Epoch: 90/1000, loss: 25.34224821567426, correct: 37
Epoch: 100/1000, loss: 24.77355144482157, correct: 38
Epoch: 110/1000, loss: 24.230267838267917, correct: 39
Epoch: 120/1000, loss: 23.65940822272508, correct: 39
Epoch: 130/1000, loss: 23.074831371889044, correct: 40
Epoch: 140/1000, loss: 22.560976809260918, correct: 40
Epoch: 150/1000, loss: 22.08540073507439, correct: 40
Epoch: 160/1000, loss: 21.63058958739817, correct: 40
Epoch: 170/1000, loss: 21.171098413731944, correct: 40
Epoch: 180/1000, loss: 20.709876774919053, correct: 40
Epoch: 190/1000, loss: 20.245238161046974, correct: 41
Epoch: 200/1000, loss: 19.786364744922558, correct: 41
Epoch: 210/1000, loss: 19.321148999833554, correct: 41
Epoch: 220/1000, loss: 18.858486435124135, correct: 41
Epoch: 230/1000, loss: 18.37917927005598, correct: 42
Epoch: 240/1000, loss: 17.905763205712496, correct: 43
Epoch: 250/1000, loss: 17.428010565847224, correct: 43
Epoch: 260/1000, loss: 16.968039321156994, correct: 43
Epoch: 270/1000, loss: 16.497125132257374, correct: 43
Epoch: 280/1000, loss: 16.052898956690957, correct: 43
Epoch: 290/1000, loss: 15.629284600355124, correct: 43
Epoch: 300/1000, loss: 15.216530581375322, correct: 44
Epoch: 310/1000, loss: 14.811145312303074, correct: 45
Epoch: 320/1000, loss: 14.42032987510779, correct: 45
Epoch: 330/1000, loss: 14.040964744693149, correct: 45
Epoch: 340/1000, loss: 13.669371609954425, correct: 46
Epoch: 350/1000, loss: 13.30738268877866, correct: 46
Epoch: 360/1000, loss: 12.948491845611038, correct: 46
Epoch: 370/1000, loss: 12.583580935663484, correct: 46
Epoch: 380/1000, loss: 12.238221036659299, correct: 46
Epoch: 390/1000, loss: 11.903833655736268, correct: 46
Epoch: 400/1000, loss: 11.578102171598257, correct: 46
Epoch: 410/1000, loss: 11.265863593345411, correct: 46
Epoch: 420/1000, loss: 10.964319758443173, correct: 46
Epoch: 430/1000, loss: 10.670603426838746, correct: 46
Epoch: 440/1000, loss: 10.389392763446445, correct: 46
Epoch: 450/1000, loss: 10.110942413066354, correct: 46
Epoch: 460/1000, loss: 9.841735144465067, correct: 46
Epoch: 470/1000, loss: 9.578180092381714, correct: 46
Epoch: 480/1000, loss: 9.323523315298544, correct: 46
Epoch: 490/1000, loss: 9.075754300627532, correct: 48
Epoch: 500/1000, loss: 8.830210419191983, correct: 48
Epoch: 510/1000, loss: 8.595585300626468, correct: 48
Epoch: 520/1000, loss: 8.365813267820695, correct: 48
Epoch: 530/1000, loss: 8.139787385412404, correct: 48
Epoch: 540/1000, loss: 7.921838742638196, correct: 48
Epoch: 550/1000, loss: 7.707755741349636, correct: 48
Epoch: 560/1000, loss: 7.498946188688114, correct: 48
Epoch: 570/1000, loss: 7.299477140268256, correct: 48
Epoch: 580/1000, loss: 7.1002033661517014, correct: 49
Epoch: 590/1000, loss: 6.9116359451132805, correct: 49
Epoch: 600/1000, loss: 6.724578615918381, correct: 49
Epoch: 610/1000, loss: 6.541058577460731, correct: 49
Epoch: 620/1000, loss: 6.365325078170678, correct: 49
Epoch: 630/1000, loss: 6.195815400090943, correct: 49
Epoch: 640/1000, loss: 6.027554379687644, correct: 49
Epoch: 650/1000, loss: 5.8637112229039845, correct: 50
Epoch: 660/1000, loss: 5.704990511148598, correct: 50
Epoch: 670/1000, loss: 5.5506582222952465, correct: 50
Epoch: 680/1000, loss: 5.411516683183759, correct: 50
Epoch: 690/1000, loss: 5.2620632470897135, correct: 50
Epoch: 700/1000, loss: 5.120310100351985, correct: 50
Epoch: 710/1000, loss: 4.983619671163027, correct: 50
Epoch: 720/1000, loss: 4.806646859784154, correct: 50
Epoch: 730/1000, loss: 4.655392783839691, correct: 50
Epoch: 740/1000, loss: 4.517628093098161, correct: 50
Epoch: 750/1000, loss: 4.399386975715046, correct: 50
Epoch: 760/1000, loss: 4.269626223212867, correct: 50
Epoch: 770/1000, loss: 4.153182663986736, correct: 50
Epoch: 780/1000, loss: 4.03615701520391, correct: 50
Epoch: 790/1000, loss: 3.9235864445899766, correct: 50
Epoch: 800/1000, loss: 3.819007170932297, correct: 50
Epoch: 810/1000, loss: 3.7241409331850734, correct: 50
Epoch: 820/1000, loss: 3.6157663939800955, correct: 50
Epoch: 830/1000, loss: 3.52196474181172, correct: 50
Epoch: 840/1000, loss: 3.4297497591030552, correct: 50
Epoch: 850/1000, loss: 3.3408812279075972, correct: 50
Epoch: 860/1000, loss: 3.254926900114172, correct: 50
Epoch: 870/1000, loss: 3.1761624285053114, correct: 50
Epoch: 880/1000, loss: 3.101914032634445, correct: 50
Epoch: 890/1000, loss: 3.0212772401541352, correct: 50
Epoch: 900/1000, loss: 2.945827927965049, correct: 50
Epoch: 910/1000, loss: 2.8755607043262907, correct: 50
Epoch: 920/1000, loss: 2.8060613129820178, correct: 50
Epoch: 930/1000, loss: 2.7424632406293945, correct: 50
Epoch: 940/1000, loss: 2.6831660224936376, correct: 50
Epoch: 950/1000, loss: 2.6198487911289727, correct: 50
Epoch: 960/1000, loss: 2.5577405940439255, correct: 50
Epoch: 970/1000, loss: 2.5003444115883817, correct: 50
Epoch: 980/1000, loss: 2.451712551195084, correct: 50
Epoch: 990/1000, loss: 2.3965557589204187, correct: 50
Epoch: 1000/1000, loss: 2.341251228909602, correct: 50







