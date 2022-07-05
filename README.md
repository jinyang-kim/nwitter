# Nomadcoders Clone Coding - Nwitter

## Firebase V9 업데이트 되면서, 이슈가 발생하여 코드의 큰 변경 없이 버전 9.0을 사용하기 위해서 Firebase의 'compat' 호환 버전 사용을 권장합니다.
## 또한 React Router DOM이 버전 6으로 업데이트 되었습니다. 따라서 수강하시는 동안 버전 6으로 업그레이드 하지 말고, 버전 5 유지를 권장합니다.

```javascript
1. firebase 설치
npm i firebase@9.6.1

2. React Router DOM 설치
npm i react-router-dom@5.3.0

소스상에서 Firebase를 import할 때, 아래와 같이 입력하세요.
import firebase from "firebase/compat/app";
import "firebase/compat/auth";
import "firebase/compat/firestore";
import "firebase/compat/storage";
```