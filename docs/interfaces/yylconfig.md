[yyl-config-types](../README.md) / [Exports](../modules.md) / YylConfig

# Interface: YylConfig

yyl 配置

## Hierarchy

* **YylConfig**

## Table of contents

### Properties

- [alias](yylconfig.md#alias)
- [all](yylconfig.md#all)
- [babelLoaderIncludes](yylconfig.md#babelloaderincludes)
- [base64Limit](yylconfig.md#base64limit)
- [commit](yylconfig.md#commit)
- [concat](yylconfig.md#concat)
- [dest](yylconfig.md#dest)
- [localserver](yylconfig.md#localserver)
- [name](yylconfig.md#name)
- [platform](yylconfig.md#platform)
- [plugins](yylconfig.md#plugins)
- [proxy](yylconfig.md#proxy)
- [px2rem](yylconfig.md#px2rem)
- [resolveModule](yylconfig.md#resolvemodule)
- [resource](yylconfig.md#resource)
- [seed](yylconfig.md#seed)
- [urlLoaderMatch](yylconfig.md#urlloadermatch)
- [version](yylconfig.md#version)
- [watch](yylconfig.md#watch)
- [webpackConfigPath](yylconfig.md#webpackconfigpath)
- [workflow](yylconfig.md#workflow)
- [yarn](yylconfig.md#yarn)

## Properties

### alias

• `Optional` **alias**: [*YylConfigAlias*](yylconfigalias.md)

webpack.resolve.alias 配置

Defined in: [index.ts:203](https://github.com/jackness1208/yyl-config-types/blob/2c73d01/index.ts#L203)

___

### all

• `Optional` **all**: { `afterScripts?`: [*ScriptsHandler*](../modules.md#scriptshandler) ; `beforeScripts?`: [*ScriptsHandler*](../modules.md#scriptshandler)  }

all 相关配置

#### Type declaration:

Name | Type | Description |
------ | ------ | ------ |
`afterScripts?` | [*ScriptsHandler*](../modules.md#scriptshandler) | 配置构建执行前运行脚本   |
`beforeScripts?` | [*ScriptsHandler*](../modules.md#scriptshandler) | 配置构建执行前运行脚本   |

Defined in: [index.ts:205](https://github.com/jackness1208/yyl-config-types/blob/2c73d01/index.ts#L205)

___

### babelLoaderIncludes

• `Optional` **babelLoaderIncludes**: *string*[]

配置加入 babel 的插件 (适用于 webpack)

Defined in: [index.ts:226](https://github.com/jackness1208/yyl-config-types/blob/2c73d01/index.ts#L226)

___

### base64Limit

• `Optional` **base64Limit**: *number*

url-loader limit值配置 (适用于 webpack)

Defined in: [index.ts:228](https://github.com/jackness1208/yyl-config-types/blob/2c73d01/index.ts#L228)

___

### commit

• `Optional` **commit**: [*CommitConfig*](commitconfig.md)

打包配置

Defined in: [index.ts:193](https://github.com/jackness1208/yyl-config-types/blob/2c73d01/index.ts#L193)

___

### concat

• `Optional` **concat**: [*ConcatConfig*](concatconfig.md)

合并配置

Defined in: [index.ts:195](https://github.com/jackness1208/yyl-config-types/blob/2c73d01/index.ts#L195)

___

### dest

• `Optional` **dest**: [*DestConfig*](destconfig.md)

输出配置

Defined in: [index.ts:191](https://github.com/jackness1208/yyl-config-types/blob/2c73d01/index.ts#L191)

___

### localserver

• `Optional` **localserver**: [*LocalserverConfig*](localserverconfig.md)

本地服务配置

Defined in: [index.ts:187](https://github.com/jackness1208/yyl-config-types/blob/2c73d01/index.ts#L187)

___

### name

• `Optional` **name**: *string*

项目名称

Defined in: [index.ts:177](https://github.com/jackness1208/yyl-config-types/blob/2c73d01/index.ts#L177)

___

### platform

• `Optional` **platform**: [*PlatformType*](../modules.md#platformtype)

平台

Defined in: [index.ts:183](https://github.com/jackness1208/yyl-config-types/blob/2c73d01/index.ts#L183)

___

### plugins

• `Optional` **plugins**: *string*[]

插件配置(不建议使用)

Defined in: [index.ts:199](https://github.com/jackness1208/yyl-config-types/blob/2c73d01/index.ts#L199)

___

### proxy

• `Optional` **proxy**: [*ProxyConfig*](proxyconfig.md)

代理配置

Defined in: [index.ts:185](https://github.com/jackness1208/yyl-config-types/blob/2c73d01/index.ts#L185)

___

### px2rem

• `Optional` **px2rem**: *boolean*

是否自动 px 转 rem (适用于 webpack)

Defined in: [index.ts:222](https://github.com/jackness1208/yyl-config-types/blob/2c73d01/index.ts#L222)

___

### resolveModule

• `Optional` **resolveModule**: *string*

补充 webpack.resolveModule 路径 (适用于 webpack)

Defined in: [index.ts:224](https://github.com/jackness1208/yyl-config-types/blob/2c73d01/index.ts#L224)

___

### resource

• `Optional` **resource**: [*ResourceConfig*](resourceconfig.md)

copy配置

Defined in: [index.ts:197](https://github.com/jackness1208/yyl-config-types/blob/2c73d01/index.ts#L197)

___

### seed

• `Optional` **seed**: [*SeedType*](../modules.md#seedtype)

seed sub name (适用于 webpack)

Defined in: [index.ts:220](https://github.com/jackness1208/yyl-config-types/blob/2c73d01/index.ts#L220)

___

### urlLoaderMatch

• `Optional` **urlLoaderMatch**: *RegExp*

url-loader 命中 test 追加

Defined in: [index.ts:230](https://github.com/jackness1208/yyl-config-types/blob/2c73d01/index.ts#L230)

___

### version

• `Optional` **version**: *string*

yyl 版本

Defined in: [index.ts:181](https://github.com/jackness1208/yyl-config-types/blob/2c73d01/index.ts#L181)

___

### watch

• **watch**: { `afterScripts?`: [*ScriptsHandler*](../modules.md#scriptshandler) ; `beforeScripts?`: [*ScriptsHandler*](../modules.md#scriptshandler)  }

watch 相关配置

#### Type declaration:

Name | Type | Description |
------ | ------ | ------ |
`afterScripts?` | [*ScriptsHandler*](../modules.md#scriptshandler) | 配置构建执行前运行脚本   |
`beforeScripts?` | [*ScriptsHandler*](../modules.md#scriptshandler) | 配置构建执行前运行脚本   |

Defined in: [index.ts:212](https://github.com/jackness1208/yyl-config-types/blob/2c73d01/index.ts#L212)

___

### webpackConfigPath

• `Optional` **webpackConfigPath**: *string*

webpack 文件路径配置

Defined in: [index.ts:201](https://github.com/jackness1208/yyl-config-types/blob/2c73d01/index.ts#L201)

___

### workflow

• `Optional` **workflow**: [*WorkflowType*](../modules.md#workflowtype)

seed 包名称

Defined in: [index.ts:179](https://github.com/jackness1208/yyl-config-types/blob/2c73d01/index.ts#L179)

___

### yarn

• `Optional` **yarn**: *boolean*

是否使用 yarn

Defined in: [index.ts:189](https://github.com/jackness1208/yyl-config-types/blob/2c73d01/index.ts#L189)
