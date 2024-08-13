# Wikidata

## Wikidata 飯店檢索

### 標示飯店

1. [台中金典綠園道商旅](https://www.wikidata.org/wiki/Q115967213)
2. [高雄文賓大飯店](https://www.wikidata.org/wiki/Q115966993)
3. [台南遠東香格里拉](https://www.wikidata.org/wiki/Q115967130)
4. [昇財麗禧酒店](https://www.wikidata.org/wiki/Q115966980)
5. [高雄喜悅酒店](https://www.wikidata.org/wiki/Q115966991)
6. [漁人碼頭休閒旅館](https://www.wikidata.org/wiki/Q115966981)
7. [天閣酒店南西館](https://www.wikidata.org/wiki/Q115967162)
8. [台北老爺酒店](https://www.wikidata.org/wiki/Q115967412)
9. [金來商旅](https://www.wikidata.org/wiki/Q115967168)
10. [君品酒店](https://www.wikidata.org/wiki/Q115967208)

### 標示紀錄

![Description of the image](myimage_3.png)

## Wikidata 檢索使用
想要找尋台灣的魚種，以下為檢索過程。
### 1. 無法直接用國家來過濾
![Description of the image](myimage_4.png)
:::info
只使用「fish」來過濾的話會有22筆資訊，但是加入「國家」的選項則無任何結果。
:::

### 2. 利用「臺灣物種名錄物種編號（舊版）」這個 Identifier 篩選出台灣物種
![Description of the image](myimage_5.png)
:::info
只顯示「臺灣物種名錄物種編號（舊版）」當中有 value 的項目，篩選結果只有3筆符合，比預期還來的少許多。
:::

### 3. 試著自行在 Statement 中新增 fish
![Description of the image](myimage_6.png)
:::info
在尖吻鱸（俗名：鱸魚）的 Statement 中新增 fish ，來方便台灣魚種的搜尋。
:::
![Description of the image](myimage_7.png)
:::info
重新檢索後有確認新增的項目有被搜尋到。
:::
### 4. 結論

過程中，想要搜出台灣的物種並不是一件困難的事情，大多數的物種皆有標記「臺灣物種名錄物種編號（舊版）」。但是想要從台灣物種當中，單純篩出魚種是一件很麻煩的事情，光是全世界所有魚種當中就只有22個魚種有 fish 這個 Statement 。另外 Wikidata 在分類學上面的「界門綱目科屬種」分的非常清楚，我一度有嘗試使用分類學來一層一層過濾，但是目標是針對所有魚類的話，到達脊索動物門之後就無法在切割下去，魚類各個都分散在不同「綱」，導致要篩出魚類，得先手動找出所有的魚類「綱」，是個很費時的方法。我目前的方式僅能篩出非常少數的台灣魚種，不確定還有沒有其他更有效的方式。