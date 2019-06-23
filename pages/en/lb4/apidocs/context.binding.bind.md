---
lang: en
title: 'API docs: context.binding.bind'
keywords: LoopBack 4.0, LoopBack 4
sidebar: lb4_sidebar
permalink: /doc/en/lb4/apidocs.context.binding.bind.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/context](./context.md) &gt; [Binding](./context.binding.md) &gt; [bind](./context.binding.bind.md)

## Binding.bind() method

A static method to create a binding so that we can do `Binding.bind('foo').to('bar');` as `new Binding('foo').to('bar')` is not easy to read.

<b>Signature:</b>

```typescript
static bind<T = unknown>(key: BindingAddress<T>): Binding<T>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  key | <code>BindingAddress&lt;T&gt;</code> | Binding key |

<b>Returns:</b>

`Binding<T>`

