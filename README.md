# Vue3-Qrcode

## Demo

[url-Qrcode](https://github.com/melodyPyw/url-qrcode)

## Usage

```javascript
<template>
  <vue-qrcode value="https://www.google.com/" />
</template>
<script>
import VueQrcode from 'vue3-qrcode'

export default {
  components: {
    VueQrcode,
  },
}
</script>
```

## Available Props

| prop                   | type (range)                                                       | default value                               |
| ---------------------- | ------------------------------------------------------------------ | ------------------------------------------- |
| `version`              | `number` (1-40)                                                    | N/A                                         |
| `errorCorrectionLevel` | `String` ('low', 'medium', 'quartile', 'high', 'L', 'M', 'Q', 'H') | `'M'`                                       |
| `maskPattern`          | `number` (0-7)                                                     | N/A                                         |
| `toSJISFunc`           | `Function`                                                         | N/A                                         |
| `margin`               | `number`                                                           | `4`                                         |
| `scale`                | `number`                                                           | `4`                                         |
| `width`                | `number`                                                           | N/A                                         |
| `color`                | `{ dark: string; light:string }`                                   | `{ dark: '#000000ff', light: '#ffffffff' }` |
| `type`                 | `string` ('image/png', 'image/jpeg', 'image/webp')                 | `'image/png'`                               |
| `quality`              | `number`(0-1)                                                      | `0.92`                                      |
| `value`                | `string | Array<{ data: string; mode?: string }>`                  | N/A                                         |
