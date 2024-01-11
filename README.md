# Vue Signature Pad Trim
基于vue-signature-pad的签名组件，支持trim功能
## 新增功能
### Methods

| Name                                   | Argument Type                | Description                                                                 |
| :------------------------------------- | :--------------------------- | --------------------------------------------------------------------------- |
| `saveSignatureTrim(type, encoderOptions)`  | `(String, Number)`           | 同`saveSignature`,不过返回的值是经过trim的，data只返回签名区域                          |
