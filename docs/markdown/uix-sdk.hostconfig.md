<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@adobe/uix-sdk](./uix-sdk.md) &gt; [HostConfig](./uix-sdk.hostconfig.md)

## HostConfig interface


<b>Signature:</b>

```typescript
export interface HostConfig 
```

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [debug?](./uix-sdk.hostconfig.debug.md) |  | boolean | <i>(Optional)</i> Copiously log lifecycle events. |
|  [guestOptions?](./uix-sdk.hostconfig.guestoptions.md) |  | [PortOptions](./uix-sdk.portoptions.md) | <p><i>(Optional)</i> Default options to use for every guest guestPort.</p><p>If <code>config.debug</code> is true, then the guest options will have <code>debug: true</code> unless <code>debug: false</code> is explicitly passed in <code>guestOptions</code>.</p> |
|  [rootName](./uix-sdk.hostconfig.rootname.md) |  | string | Human-readable "slug" name of the extensible area--often an entire app. This string serves as a namespace for extension points within the area. |
|  [runtimeContainer?](./uix-sdk.hostconfig.runtimecontainer.md) |  | HTMLElement | <i>(Optional)</i> A DOM element \_outside\_ of the React root. This is necessary to preserve the lifetime of the iframes which are running extension objects; if they live inside the React root, then React could unexpectedly re-render the iframe tags themselves at any time, causing a reload of the frame. |
