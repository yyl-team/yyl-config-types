[yyl-config-types](README.md) / Exports

# yyl-config-types

## Table of contents

### Interfaces

- [AddressMap](interfaces/addressmap.md)
- [CommitConfig](interfaces/commitconfig.md)
- [ConcatConfig](interfaces/concatconfig.md)
- [DestConfig](interfaces/destconfig.md)
- [Env](interfaces/env.md)
- [LocalserverConfig](interfaces/localserverconfig.md)
- [ProxyConfig](interfaces/proxyconfig.md)
- [ResourceConfig](interfaces/resourceconfig.md)
- [YylConfig](interfaces/yylconfig.md)
- [YylConfigAlias](interfaces/yylconfigalias.md)

### Type aliases

- [LogLevel](modules.md#loglevel)
- [PlatformType](modules.md#platformtype)
- [ScriptsFn](modules.md#scriptsfn)
- [ScriptsHandler](modules.md#scriptshandler)
- [SeedType](modules.md#seedtype)
- [WorkflowType](modules.md#workflowtype)

## Type aliases

### LogLevel

Ƭ **LogLevel**: *1* \| *2* \| *0*

日志等级

Defined in: [index.ts:11](https://github.com/jackness1208/yyl-config-types/blob/2c73d01/index.ts#L11)

___

### PlatformType

Ƭ **PlatformType**: *pc* \| *mobile*

平台类型

Defined in: [index.ts:2](https://github.com/jackness1208/yyl-config-types/blob/2c73d01/index.ts#L2)

___

### ScriptsFn

Ƭ **ScriptsFn**: (`{ env: Env, config: YylConfig }`: *any*) => *Promise*<*unknown*\>

Defined in: [index.ts:144](https://github.com/jackness1208/yyl-config-types/blob/2c73d01/index.ts#L144)

___

### ScriptsHandler

Ƭ **ScriptsHandler**: *string* \| [*ScriptsFn*](modules.md#scriptsfn)

Defined in: [index.ts:145](https://github.com/jackness1208/yyl-config-types/blob/2c73d01/index.ts#L145)

___

### SeedType

Ƭ **SeedType**: *react-ts* \| *vue2* \| *vue2-ts* \| *base*

seed 二级类型, 当 workflow = webpack 时适用

Defined in: [index.ts:8](https://github.com/jackness1208/yyl-config-types/blob/2c73d01/index.ts#L8)

___

### WorkflowType

Ƭ **WorkflowType**: *webpack* \| *gulp-requirejs* \| *other*

seed 类型

Defined in: [index.ts:5](https://github.com/jackness1208/yyl-config-types/blob/2c73d01/index.ts#L5)
