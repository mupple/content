---
title: HIDInputReportEvent.data
slug: Web/API/HIDInputReportEvent/data
page-type: web-api-instance-property
tags:
  - API
  - Property
  - Reference
  - data
  - HIDInputReportEvent
  - Experimental
browser-compat: api.HIDInputReportEvent.data
---

{{securecontext_header}}{{APIRef("WebHID API")}}{{SeeCompatTable}}

The **`data`**  property of the {{domxref("HIDInputReportEvent")}} interface returns a {{jsxref("DataView")}} containing the data from the input report, excluding the `reportId` if the HID interface uses report IDs.

## Value

A {{jsxref("DataView")}}.

## Examples

In the following example the returned `data` is logged to the console.

```js
device.addEventListener("inputreport", (event) => {
  const { data, device, reportId } = event;
  console.log(data);
});
```

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}
