#fis-parser-template 

[template.js](https://github.com/xurui3762791/template.js)的fis编译插件——一款javascript模板引擎。

##安装

	$ npm install -g fis-parser-template

##配置

    //设置编译器
    fis.config.merge({
        modules: {
            parser: {
                tmpl: 'template' // tmpl后缀的使用fis-parser-template处理
            }
        }
    });
	
	//自定义参数
    fis.config.merge({
        settings: {
            parser: {
                template: {
                    sTag: '<%',
                    eTag: '%>'
                }
            }
        }
    });

##报告问题

- [Issues](https://github.com/xurui3762791/fis-parser-template/issues "report question")


##更新日志

[更新日志](CHANGELOG.md)

##相关链接

- [fis](http://fis.baidu.com/)