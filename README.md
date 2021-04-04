TSX Arrow Function Go To Definition
===

<small>VSCode marketplace unique identifier: `vscode-tsx-arrow-definition`</small>

## Feature

* Remove react definition of arrow function

## Before

![before](https://raw.githubusercontent.com/Miaonster/typescript-react-go-to-definition-plugin/master/document/before.jpg)

## After

![before](https://raw.githubusercontent.com/Miaonster/typescript-react-go-to-definition-plugin/master/document/after.png)


## Install

[https://marketplace.visualstudio.com/items?itemName=miaonster.vscode-tsx-arrow-definition](https://marketplace.visualstudio.com/items?itemName=miaonster.vscode-tsx-arrow-definition)

or search extension marketplace:

```
vscode-tsx-arrow-definition
```

## Motivation

Due to this [issue](https://github.com/microsoft/TypeScript/issues/37816), Cmd+click of JSX component will show 2 definitions. One of the definition is `FunctionComponent` of react. This behavior is not desired. So let's remove that definition, just remain the correct one.

Before this extension, I created a tsserver plugin,  [typescript-react-go-to-definition-plugin](https://github.com/Miaonster/typescript-react-go-to-definition-plugin), for normal extension can only add additional definition. Only [`typescriptServerPlugins`](https://code.visualstudio.com/api/references/contribution-points#contributes.typescriptServerPlugins) can modify the behavior of tsserver.
