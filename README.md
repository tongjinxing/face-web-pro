## FACE-WEB
---
face-web It is a tool that enables web/pc browser cameras to capture real-time face (front) screenshots

### Characteristic
- Easy to call Web / PC browser camera
- Integration of Face Recognition (Front/Plane) Algorithms
- Generating real-time screenshots of Base64


### Install

```
1、cnpm install
```

```
2、cnpm start
```

### NPM
you can also use [npm-package](https://www.npmjs.com/package/face-web)

```
npm install face-web --save
```

```
import { FaceWeb } from 'face-web';

<FaceWeb
  onChange={base64 => {}}
/>
```

### API

|  field   | type  | remark |
|  ----  | ----  | ---- |
| onChange  | func | cb base64 |
| className  | String | cover style |
| debounceTime  | Number | output rate |

### Demo Gif

![](https://pan.baidu.com/s/1Mpf2eUkS4SqZCjDk7ZsO6Q)
