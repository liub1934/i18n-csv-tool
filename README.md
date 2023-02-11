# 使用 CSV 管理 i18n 多语言

项目中使用 CSV 文件将多语言集中在一起，方便同时对一个 Key 进行修改。  
通过一个可执行的文件`icotjo`，将 CSV 转换成各语言的 JSON 文件。  
`icotjo`是一个 Go 写的工具，源码可在[https://github.com/wonsikin/icotjo](https://github.com/wonsikin/icotjo)查看。具体说明参考：[点击前往](https://liubing.me/article/i18n/gracefully-manage-i18n-using-csv-in-vue.html)。

> Linux 或 Mac 执行文件提示没权限的话可以使用 chmod 修改文件权限

```sh
chmod 0755 icotjo
chmod 0755 icotjoForMac
```

![image](https://image.liubing.me/2023/02/11/8a782f7f97a35.gif)
