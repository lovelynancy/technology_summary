## 常用开发利器

1）sql2go：将sql语句转换为golang的struct，使用ddl语句即可

如show create table ***,将输出的语句，直接复制粘贴

http://stming.cn/tool/sql2go.html

2）toml2go: 将编码后的toml文件转换为golang的struct

https://xuri.me/toml-to-go/

3）curl2go将curl命令转换为具体的golang代码

https://mholt.github.io/curl-to-go/

4）json2go将json文本转换为struct

https://mholt.github.io/json-to-go/

5）mysql转es工具

http://www.ischoolbar.com/EsParser/

6）golang模拟模版的工具，在支持泛型前可以使用

https://github.com/cheekybits/genny

7）查看某一个库的依赖情况，类似go list功能

https://github.com/KyleBanks/depth

8) 一个好用的文件压缩和解压工具,集成了zip,tar等多种功能,主要还有跨平台.

https://github.com/mholt/archiver

9)go 内置命令.

go list 可以查看某一个包的依赖关系.

go vet 可以检查代码不符合golang规范的地方.

10)热编译工具.

https://github.com/silenceper/gowatch

11）golang代码质量检测工具 revive.

https://github.com/mgechev/revive

12）golang的代码调用链图工具. Go Callvis

https://github.com/TrueFurby/go-callvis

13）开发流程改进工具 Realize

https://github.com/oxequa/realize

14）自动生成测试用例工具,Gotests.

https://github.com/cweill/gotests



## 日常开发工具

**日志**

https://github.com/Sirupsen/logrus

https://github.com/uber-go/zap

 

**配置**

兼容json,toml,yaml,hcl等格式的日志库.

https://github.com/spf13/viper

 

**存储**

mysql https://github.com/go-xorm/xorm

es  https://github.com/elastic/elasticsearch

redis  https://github.com/gomodule/redigo

mongo https://github.com/mongodb/mongo-go-driver

kafka  https://github.com/Shopify/sarama

 

**数据结构**

https://github.com/emirpasic/gods

 

**命令行**

https://github.com/spf13/cobra

 

**框架**

https://github.com/grpc/grpc-go

https://github.com/gin-gonic/gin

 

**并发**

https://github.com/Jeffail/tunny

https://github.com/benmanns/goworker

现在我们框架在用的,虽然star不多,但是确实好用,当然还可以更好用.

https://github.com/rafaeldias/async

 

**工具**

定义了实用的判定类,以及针对结构体的校验逻辑,避免业务侧写复杂的代码.

https://github.com/asaskevich/govalidator

https://github.com/bytedance/go-tagexpr

 

protobuf文件动态解析的接口,可以实现反射相关的能力.

https://github.com/jhump/protoreflect

 

表达式引擎工具:

https://github.com/Knetic/govaluate

https://github.com/google/cel-go

 

字符串处理:

https://github.com/huandu/xstrings

