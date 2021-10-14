1.Define a Loss-Function of SVM

線性 SVM :對樣本進行分類時找到與決策邊界最近,邊界距離最大以及樣本距離最遠的狀況,線性SVM也稱為Large Margin Classifier

損失函數SVM:

![image-20211014155349403](C:\Users\ppall\AppData\Roaming\Typora\typora-user-images\image-20211014155349403.png)

當 y=1 時,用 θᵀx 來當作成本,所以可以判別說當 θᵀx 越來越小時,成本則會越來越高

所以從以上得知,損失會隨著θᵀx 而改變





2.Derivation of optimal vector W for a binary SVM

![SVM](C:\Users\ppall\Desktop\高科大\機器學習\HW_2\SVM.jpg)





3.Derivation of optimal vector W's for a 3-layer MLP





![MLP推導](C:\Users\ppall\Desktop\高科大\機器學習\HW_2\MLP推導.jpg)