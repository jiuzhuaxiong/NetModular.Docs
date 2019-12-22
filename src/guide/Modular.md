# 我的模块化(开发平台)

## 概念说明

**模块：** 按照业务或者功能的不同拆分的块，比如：权限管理模块`Admin`、任务调度模块`Quartz`、人事档案模块`PersonnelFiles`等

**项目：** 项目可以理解为一个完整的产品，它是由至少一个模块组合而成的，比如：xxxOA 系统(包含权限管理模块`Admin`、任务调度模块`Quartz`、人事档案模块`PersonnelFiles`等模块)、xxx CMS 系统(包含权限管理模块`Admin`、任务调度模块`Quartz`、新闻管理模块`News`等模块组成)

## 模块化与微服务

很多人在初看本框架时，往往会与微服务作比较，我个人觉得，微服务其实也是一种模块化，但是本框架与微服务有个比较大的区别，微服务的各个服务都是独立部署的，服务之间通过 http 或者 rpc 等方式进行连接，而本框架则是强调集成，及将多个模块集成为一个项目打包部署，它是在开发阶段就已经进行集成了。

## 模块化示意图

## 我想要的模块化

模块化这个概念很好理解，无非就是根据业务领域(_`可以理解为领域驱动中的领域`_)，将业务拆分成不同的模块，以此降低软件的复杂度，提高代码的复用等等。

对于我想要的模块化，应该说不仅仅是一个框架，更是一个完整的 **开发平台**，这个平台包括以下特点：

> 1、约定：每个模块都需遵守统一的约定和规则

> 2、独立：每个模块要尽量做到独立，模块之间尽量避免强依赖，尽量通过设计模式来解决依赖

> 3、灵活：任意个模块可灵活的集成打包部署

> 4、便捷：模块集成、打包、升级，要做到简单、方便、傻瓜式

> 5、全面：不仅仅后端模块化，前端也要模块化

> 6、维护：每个模块的代码需要单独的仓库维护，且要能够方便的管理

> 7、专注：开发人员只需关心自己所负责的模块

以上就是我想要的模块化开发平台所包含要求的简单描述，下面我们来详细说明。

### 1、约定

::: tip
所谓约定，是指模块需遵守统一的约定与规则。
:::

有一种软件设计范式，叫`约定优于配置（convention over configuration）`，也称作按约定编程，旨在减少软件开发人员需做决定的数量，获得简单的好处，而又不失灵活性。

### 2、独立

### 3、灵活

### 4、便捷

### 5、全面

### 6、维护

### 7、专注