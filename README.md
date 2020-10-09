# CDN

## Github + jsDelivr


> ### cdn 优化的代码文件需压缩从而达到最佳效果	  


### eg.

#### jsDelivr路径写法： `https://cdn.jsdelivr.net/gh/user/repo@version/file`   

#### 在github通过Url引用: `https://raw.githubusercontent.com/NidhoggDJoking/CDN/master/img/Egoist.jpg`


#### 通过jsDelivr引用资源:  `https://cdn.jsdelivr.net/gh/nidhoggdjoking/CDN@1.0/img/Egoist.jpg`

- ##### 使用github链接有明显有的加载延迟

- ##### 而通过jsDelivr引用资源达到秒开无延迟

####  `master` 分支控制`1.0`版本  
   
   

#### `1.1`分支控制`1.1`版本   


#### `https://www.jsdelivr.com/package/gh/nidhoggdjoking/CDN`   

### 标签删除

```
git tag

git tag -d 1.1

git push origin --delete 1.1
```

