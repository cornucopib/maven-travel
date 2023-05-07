# maven研究项目

### 一.利用maven+profiles+maven-assembly-plugin实现指定文件，打jar包。

#### 1. 只打包A.java和a.json
```
maven clean package -P profile-a 
```
#### 2. 只打包B.java和b.json
```
maven clean package -P profile-b
```