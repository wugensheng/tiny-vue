## setup环境——集成ts和jest单元测试
1. 创建测试用例——检测测试环境是否正常
src/reactivity/tests：存放所有测试文件
需要注意的问题：
    - 安装typescript，并创建tsconfig.json文件 否则编辑器无法识别jest类型
    - 安装@types/jest，即安装jest框架等一系列依赖
    - 这样在没有其他模块导入情况下，测试是正常的
    - 利用es模块规范导入测试函数的时候，需要利用babel进行编译转换 