# Modularization
模块化：单独module可以单独编译运行


为什么使用模块化：

在APP开发的初期，代码了不大，业务量比较下，一个APP作为一个单独的模块进行开发，往往问题不大，而且还能加快开发效率但是随着APP的用户量越来越多，也越来越复杂，这种开发方式显得结构特别的臃肿，特别是多个开发人员进行开发维护一个项目的时候每个人的代码质量也不相同，容易会产生代码冲突的问题。同时随着业务的增多，代码变的越来越复杂，每个模块之间的代码耦合变得越来越严重，导致代码混乱，没法进行单元测试，bug修改往往会牵一发而动全身，改掉一个bug，有产生新的bug，同时编译时间也会越来越长，这时候解耦问题急需解决。APP模块化的目标是告别结构臃肿，让各个业务变得相对独立，业务模块在组件模式下可以独立开发，而在集成模式下又可以变为依赖包集成到“app壳工程”中，组成一个完整功能的APP。


模块化的优点：

1、团队可以并行工作

2、减少代码间耦合

3、加快编译速度


