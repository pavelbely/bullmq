<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [bullmq](./bullmq.md) &gt; [QueueSchedulerListener](./bullmq.queueschedulerlistener.md)

## QueueSchedulerListener interface

<b>Signature:</b>

```typescript
export interface QueueSchedulerListener 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [failed](./bullmq.queueschedulerlistener.failed.md) | (jobId: string, failedReason: Error, prev: string) =&gt; void | Listen to 'failed' event.<!-- -->This event is triggered when a job has thrown an exception. |
|  [stalled](./bullmq.queueschedulerlistener.stalled.md) | (jobId: string, prev: string) =&gt; void | Listen to 'stalled' event.<!-- -->This event is triggered when a job gets stalled. |
