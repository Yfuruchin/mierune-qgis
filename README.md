# MIERUNE地図 - QGIS

<br>

## Getting Started

### MIERUNE地図表示 -「Free」プラン

![MIERUNE地図表示 -「Free」プラン](./img/img_001.gif)

example path
```
./src/MIERUNE_Color.tsv
./src/MIERUNE_MONO.tsv
```

<br>

---

<br>

### MIERUNE地図表示 -「Standard, Premium, Global Scale」プラン

![MIERUNE地図表示 -「Standard, Premium, Global Scale」プラン](./img/img_002.gif)

example path
```
./src/MIERUNE Normal.tsv
./src/MIERUNE Bright.tsv
./src/MIERUNE Gray.tsv
./src/MIERUNE Warm.tsv
./src/MIERUNE Blue.tsv
./src/MIERUNE Color+.tsv
```
- tsvファイルにapikeyを追加  
![README05](./img/README05.png)

<br>

---

<br>

### 使用方法
1. QGISを起動  

<br>

2. TileLayerPluginをインストール  
![README01](./img/README01.png)
 
<br>

3. MIERUNE地図のtsvファイルをダウンロード  

<br>
 
4. 下記ディレクトリにtsvファイルをコピー    
```
/Users/ユーザー名/.qgis2/python/plugins/TileLayerPlugin/layers/  
```

<br>

5. TileLayerPluginを実行  
![README02](./img/README02.png)

<br>
  
6. コピーしたtsvファイルが表示されているか確認  
![README03](./img/README03.png)
  
<br>

7. 表示したい地図を選択するとMIERUNE地図が表示
![README04](./img/README04.png)
