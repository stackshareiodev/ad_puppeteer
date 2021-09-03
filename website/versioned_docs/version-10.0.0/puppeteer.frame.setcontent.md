<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [puppeteer](./puppeteer.md) &gt; [Frame](./puppeteer.frame.md) &gt; [setContent](./puppeteer.frame.setcontent.md)

## Frame.setContent() method

Set the content of the frame.

<b>Signature:</b>

```typescript
setContent(html: string, options?: {
        timeout?: number;
        waitUntil?: PuppeteerLifeCycleEvent | PuppeteerLifeCycleEvent[];
    }): Promise<void>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  html | string | HTML markup to assign to the page. |
|  options | { timeout?: number; waitUntil?: [PuppeteerLifeCycleEvent](./puppeteer.puppeteerlifecycleevent.md) \| [PuppeteerLifeCycleEvent](./puppeteer.puppeteerlifecycleevent.md)\[\]; } | options to configure how long before timing out and at what point to consider the content setting successful. |

<b>Returns:</b>

Promise&lt;void&gt;
