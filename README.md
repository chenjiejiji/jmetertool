## 功能
根据errocode的返回值设计接口用例集，检查接口的容错性。

## 依赖

 apache-jmeter-xx
 apache-ant-xx

windows下
直接运行 install.bat 安装依赖

##有问题反馈
在使用中有任何问题，欢迎反馈给我，可以用以下联系方式跟我交流

* 邮件(chenjiejiji#gmail.com, 把#换成@)
* QQ: 539901741
* 作者:bob_jie

##结构
```javascript
	-jmeterTest
	--resultLog ---html(报告存放位置)
				---jtl （jmeter脚本运行后jtl文件存放位置）
	--script  	---test.jmx （jmeter脚本存放位置）
	--build.xml（ant所需build.xml的文件）
```

##启动
移动到当前文件夹下执行ant
  