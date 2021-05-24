
## 扩展库

#### 如何使用

```js
// 安装扩展库
_IMPORTURL["库名称"] = "库链接"
import 库名称; //导入刚安装的扩展库

// 调用示例--github
_IMPORTURL["memcache"] = "https://github.com/973432436/aardio-lib/raw/main/released/memcache.tar.lzma"
import memcache;

// 调用示例--gitee
_IMPORTURL["memcache"] = "https://gitee.com/fancanjie/aardio-lib/raw/main/released/memcache.tar.lzma"
import memcache;
```

### 目录结构
```js
/src			存储库源码，仅用于开发/查看
/released		存储打包发布后的库文件，调用时候调用此目录下对应压缩包即可
```

### 仓库地址
https://github.com/973432436/aardio-lib		（国际用户）
https://gitee.com/fancanjie/aardio-lib		（中国用户，特殊时期gitee可能会进行代码内容审核无法访问）
