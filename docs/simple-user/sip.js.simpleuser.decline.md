<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [sip.js](./sip.js.md) &gt; [SimpleUser](./sip.js.simpleuser.md) &gt; [decline](./sip.js.simpleuser.decline.md)

## SimpleUser.decline() method

Decline an incoming call.

<b>Signature:</b>

```typescript
decline(): Promise<void>;
```
<b>Returns:</b>

Promise&lt;void&gt;

## Remarks

Reject an incoming INVITE request. Resolves with the response is sent, otherwise rejects. Use `onCallTerminated` delegate method to determine if and when call is ended.

