# Binary Search Tree

###  [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

1. adım

![pic1](https://camo.githubusercontent.com/974d04b3c3c1a71a1f74bc069723c68eec60ac5fb43b75c1bc26b1ecae9ed1ce/68747470733a2f2f7777772e6c696e6b706963747572652e636f6d2f712f315f313534352e706e67)

Root 7, 5 7'den küçük; 7'nin soluna

2. adım

![pic2](https://camo.githubusercontent.com/1aa9bbba6ee327231b7f382a5930d0d1057ba8c9d00005b039411c6b1c6ae204/68747470733a2f2f7777772e6c696e6b706963747572652e636f6d2f712f325f323234332e706e67)

1, 7 ve 5'ten küçük olduğu için 5'in solunda bulunur.

3. adım

![pic3](https://camo.githubusercontent.com/6a75aa99396a360ecc5f482d9d039363a206f5261db50444060e8dc48649a2ef/68747470733a2f2f7777772e6c696e6b706963747572652e636f6d2f712f335f313431382e706e67)

8 7'den büyük olduğu için 7'nin sağında bulunur.

4. adım

![pic4](https://camo.githubusercontent.com/a53f6b1112e2f3e690d30e597506f434704af2fb9c5a7e9f7ee452db75f0cb97/68747470733a2f2f7777772e6c696e6b706963747572652e636f6d2f712f345f313130322e706e67)

3, 7 ve 5 ten küçük 1'den büyük olduğu için 1'in sağında bulunur.

5. adım

![pic5](https://camo.githubusercontent.com/64be4f8e49e13e7578bd8fcdab466b2a071b905c4e5d6ca85008ceaa94d733d8/68747470733a2f2f7777772e6c696e6b706963747572652e636f6d2f712f355f3235342e706e67)

6 7'den küçük olduğu için sol tarafta 5'ten büyük olduğu için 5'in sağında bulunur.

6. adım

![pic6](https://camo.githubusercontent.com/97a40b4285b9729145953dba36d8f19214729dca30bb62850b5f4a4a82bc3801/68747470733a2f2f7777772e6c696e6b706963747572652e636f6d2f712f365f3638312e706e67)

0 tüm sayılardan küçük olduğu için 1'in solunda bulunur.

7. adım

![pic7](https://camo.githubusercontent.com/51bbe07c45070d06adb414d6287fe174cc7842de4340b9c28d5023091114c518/68747470733a2f2f7777772e6c696e6b706963747572652e636f6d2f712f375f3435372e706e67)

9, 7 ve 8'den büyük olduğu için 8'in sağında bulunur.

8. adım

![pic8](https://user-images.githubusercontent.com/89038324/182029610-5f2887f5-07d8-486b-a08d-ba81cabb3025.png)

4, 7 ve 5'ten küçük olduğu için solda, 1'den ve 3'ten büyük olduğu için 3'ün sağında bulunur.

9. adım

![pic9](https://user-images.githubusercontent.com/89038324/182029654-31b444d8-687b-4a4b-9db8-01bec5ca610f.png)

Son olarak 2 ağaca eklenir. 2, 5 ve 7'den küçük olduğu için solda, 3'ten küçük olduğu için de 3'ün solunda bulunur.


