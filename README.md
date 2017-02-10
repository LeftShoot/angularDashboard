# angularDashboard
a dashboard project develop by Angular

#typeScript 开发手册
 基础类型
 变量声明
 接口
 类
 函数
 泛型
 枚举
 类型推论
 类型兼容性
 高级类型 （交叉类型、联合类型、类型保护、区分类型、类型别名、字符串字面量类型、可辨识联合、多态的this类型）
 Symbols  （Es6增加的原生类型，定义不可改变且唯一的值）
 迭代器和生成器
 模块 （“外部模块”现在则简称为“模块”）
 命名空间  （“内部模块”现在称做“命名空间”）
 命名空间和模块 (使用命名空间和模块，并注意使用他们的陷阱)
 模块解析 （相对 vs. 非相对模块导入、 模块解析策略）
 声明合并  （多个相同声明合并成一个的机制）
 JSX  （支持内嵌JSX）
 装饰器 （类装饰器、属性装饰器、访问器装饰器、方法装饰器、参数装饰器、元数据）
 Mixins （混入，通过可重用组件创建类的方式）
 三斜线指令 (包含单个XML标签的单行注释)
 错误信息列表 (报错信息查阅 https://www.tslang.cn/docs/handbook/error.html)

#项目文件说明
angular-cli.json --- angular-cli的配置文件
karma.conf.js --- 测试配置文件
protractor.conf.js --- typescript的lint配置文件，端到端的测试配置文件
polyfills.ts --- 导入es6模块的配置文件
main.ts --- 引导启动文件
style.css --- 全局样式
ts.config.json --- typescript配置文件
typings.d.ts --- typescript的声明文件