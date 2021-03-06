<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [puppeteer](./puppeteer.md) &gt; [Protocol](./puppeteer.protocol.md) &gt; [Runtime](./puppeteer.protocol.runtime.md) &gt; [CallFunctionOnRequest](./puppeteer.protocol.runtime.callfunctiononrequest.md)

## Protocol.Runtime.CallFunctionOnRequest interface

<b>Signature:</b>

```typescript
export interface CallFunctionOnRequest 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [arguments](./puppeteer.protocol.runtime.callfunctiononrequest.arguments.md) | [CallArgument](./puppeteer.protocol.runtime.callargument.md)<!-- -->\[\] | Call arguments. All call arguments must belong to the same JavaScript world as the target object. |
|  [awaitPromise](./puppeteer.protocol.runtime.callfunctiononrequest.awaitpromise.md) | boolean | Whether execution should <code>await</code> for resulting value and return once awaited promise is resolved. |
|  [executionContextId](./puppeteer.protocol.runtime.callfunctiononrequest.executioncontextid.md) | [ExecutionContextId](./puppeteer.protocol.runtime.executioncontextid.md) | Specifies execution context which global object will be used to call function on. Either executionContextId or objectId should be specified. |
|  [functionDeclaration](./puppeteer.protocol.runtime.callfunctiononrequest.functiondeclaration.md) | string | Declaration of the function to call. |
|  [generatePreview](./puppeteer.protocol.runtime.callfunctiononrequest.generatepreview.md) | boolean | Whether preview should be generated for the result. |
|  [objectGroup](./puppeteer.protocol.runtime.callfunctiononrequest.objectgroup.md) | string | Symbolic group name that can be used to release multiple objects. If objectGroup is not specified and objectId is, objectGroup will be inherited from object. |
|  [objectId](./puppeteer.protocol.runtime.callfunctiononrequest.objectid.md) | [RemoteObjectId](./puppeteer.protocol.runtime.remoteobjectid.md) | Identifier of the object to call function on. Either objectId or executionContextId should be specified. |
|  [returnByValue](./puppeteer.protocol.runtime.callfunctiononrequest.returnbyvalue.md) | boolean | Whether the result is expected to be a JSON object which should be sent by value. |
|  [silent](./puppeteer.protocol.runtime.callfunctiononrequest.silent.md) | boolean | In silent mode exceptions thrown during evaluation are not reported and do not pause execution. Overrides <code>setPauseOnException</code> state. |
|  [userGesture](./puppeteer.protocol.runtime.callfunctiononrequest.usergesture.md) | boolean | Whether execution should be treated as initiated by user in the UI. |

