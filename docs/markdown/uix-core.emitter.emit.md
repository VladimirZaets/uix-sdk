<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@adobe/uix-core](./uix-core.md) &gt; [Emitter](./uix-core.emitter.md) &gt; [emit](./uix-core.emitter.emit.md)

## Emitter.emit() method

Convenience method to construct and dispatch custom events.

<b>Signature:</b>

```typescript
protected emit<Event extends Events>(type: Event["type"], detail: Event["detail"]): void;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  type | Event\["type"\] | Name of one of the allowed events this can emit |
|  detail | Event\["detail"\] | Object to expose in the [CustomEvent\#detail](https://developer.mozilla.org/en-US/docs/Web/API/CustomEvent/detail) property. |

<b>Returns:</b>

void
