[yyl-config-types](../README.md) / [Exports](../modules.md) / Env

# Interface: Env

yyl cli 传入 env

## Hierarchy

* **Env**

## Indexable

▪ [key: *string*]: *any*

自定义变量

## Table of contents

### Properties

- [NODE\_ENV](env.md#node_env)
- [config](env.md#config)
- [hmr](env.md#hmr)
- [https](env.md#https)
- [isCommit](env.md#iscommit)
- [livereload](env.md#livereload)
- [logLevel](env.md#loglevel)
- [name](env.md#name)
- [path](env.md#path)
- [port](env.md#port)
- [proxy](env.md#proxy)
- [remote](env.md#remote)
- [seed](env.md#seed)
- [silent](env.md#silent)
- [tips](env.md#tips)
- [useHotPlugin](env.md#usehotplugin)
- [ver](env.md#ver)
- [workflow](env.md#workflow)
- [writeToDisk](env.md#writetodisk)

## Properties

### NODE\_ENV

• `Optional` **NODE\_ENV**: *string*

参数配置

Defined in: [index.ts:122](https://github.com/jackness1208/yyl-config-types/blob/2c73d01/index.ts#L122)

___

### config

• `Optional` **config**: *string*

yyl.conig 路径

Defined in: [index.ts:98](https://github.com/jackness1208/yyl-config-types/blob/2c73d01/index.ts#L98)

___

### hmr

• `Optional` **hmr**: *boolean*

启动热更新 (适用于 webpack)

Defined in: [index.ts:135](https://github.com/jackness1208/yyl-config-types/blob/2c73d01/index.ts#L135)

___

### https

• `Optional` **https**: *boolean*

开启 https 代理

Defined in: [index.ts:117](https://github.com/jackness1208/yyl-config-types/blob/2c73d01/index.ts#L117)

___

### isCommit

• `Optional` **isCommit**: *boolean*

开启打包模式

Defined in: [index.ts:100](https://github.com/jackness1208/yyl-config-types/blob/2c73d01/index.ts#L100)

___

### livereload

• `Optional` **livereload**: *boolean*

启动刷新更新 (适用于 webpack)

Defined in: [index.ts:133](https://github.com/jackness1208/yyl-config-types/blob/2c73d01/index.ts#L133)

___

### logLevel

• `Optional` **logLevel**: [*LogLevel*](../modules.md#loglevel)

日志等级

Defined in: [index.ts:104](https://github.com/jackness1208/yyl-config-types/blob/2c73d01/index.ts#L104)

___

### name

• `Optional` **name**: *string*

配置名称

Defined in: [index.ts:94](https://github.com/jackness1208/yyl-config-types/blob/2c73d01/index.ts#L94)

___

### path

• `Optional` **path**: *string*

代理根目录 server cli 适用

Defined in: [index.ts:109](https://github.com/jackness1208/yyl-config-types/blob/2c73d01/index.ts#L109)

___

### port

• `Optional` **port**: *number*

本地代理端口

Defined in: [index.ts:113](https://github.com/jackness1208/yyl-config-types/blob/2c73d01/index.ts#L113)

___

### proxy

• `Optional` **proxy**: *number* \| *boolean*

开启反向映射模式

Defined in: [index.ts:115](https://github.com/jackness1208/yyl-config-types/blob/2c73d01/index.ts#L115)

___

### remote

• `Optional` **remote**: *boolean*

开启线上映射模式

Defined in: [index.ts:111](https://github.com/jackness1208/yyl-config-types/blob/2c73d01/index.ts#L111)

___

### seed

• `Optional` **seed**: [*SeedType*](../modules.md#seedtype)

二级 seed 名称

Defined in: [index.ts:127](https://github.com/jackness1208/yyl-config-types/blob/2c73d01/index.ts#L127)

___

### silent

• `Optional` **silent**: *boolean*

开启静默模式

Defined in: [index.ts:102](https://github.com/jackness1208/yyl-config-types/blob/2c73d01/index.ts#L102)

___

### tips

• `Optional` **tips**: *boolean*

显示代理 toast (适用于 webpack)

Defined in: [index.ts:131](https://github.com/jackness1208/yyl-config-types/blob/2c73d01/index.ts#L131)

___

### useHotPlugin

• `Optional` **useHotPlugin**: *boolean*

使用 hot plugin

Defined in: [index.ts:138](https://github.com/jackness1208/yyl-config-types/blob/2c73d01/index.ts#L138)

___

### ver

• `Optional` **ver**: *remote*

已由 --remote 代替，不建议使用

Defined in: [index.ts:119](https://github.com/jackness1208/yyl-config-types/blob/2c73d01/index.ts#L119)

___

### workflow

• `Optional` **workflow**: [*WorkflowType*](../modules.md#workflowtype)

开发内部使用

Defined in: [index.ts:96](https://github.com/jackness1208/yyl-config-types/blob/2c73d01/index.ts#L96)

___

### writeToDisk

• `Optional` **writeToDisk**: *boolean*

是否写入 dist (适用于 webpack)

Defined in: [index.ts:129](https://github.com/jackness1208/yyl-config-types/blob/2c73d01/index.ts#L129)
