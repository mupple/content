---
title: AbsoluteOrientationSensor()
slug: Web/API/AbsoluteOrientationSensor/AbsoluteOrientationSensor
page-type: web-api-constructor
tags:
  - API
  - AbsoluteOrientationSensor
  - Constructor
  - Generic Sensor API
  - Orientation Sensor API
  - Reference
  - Sensor
  - Sensor APIs
  - Sensors
browser-compat: api.AbsoluteOrientationSensor.AbsoluteOrientationSensor
---

{{APIRef("Sensor API")}}

The **`AbsoluteOrientationSensor()`** constructor creates a new {{domxref("AbsoluteOrientationSensor")}} object which describes the device's physical orientation in relation to the Earth's reference coordinate system.

If a feature policy blocks use of a feature it is because your code is inconsistent with the policies set on your server. This is not something that would ever be shown to a user. The {{httpheader('Feature-Policy')}} HTTP header article contains implementation instructions.

## Syntax

```js
new AbsoluteOrientationSensor()
new AbsoluteOrientationSensor(options)
```

### Parameters

- `options` {{optional_inline}}

  - : Options are as follows:

    - `frequency`
      - : The desired number of times per second a sample should be taken, meaning the number of times per second that the {{domxref('sensor.reading_event', 'reading')}} event will be called. A whole number or decimal may be used, the latter for frequencies less than a second. The actual reading frequency depends on the device hardware and consequently may be less than requested.
    - `referenceFrame`
      - : Either `'device'` or `'screen'`. The default is `'device'`.

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}

## See also

- {{domxref('sensor.reading_event', 'reading')}} event
