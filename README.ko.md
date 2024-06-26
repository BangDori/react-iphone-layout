# React-iPhone-Layout

![iphone_image](https://github.com/BangDori/react-iphone-layout/assets/44726494/9015f4fb-caf3-4c4f-b660-46c9f94c8f81)

## 설치

```shell
$ npm install react-iphone-layout --save-dev

$ yarn add react-iphone-layout --dev
```

## 기능

- **웹 앱 호환성**: iPhone 레이아웃을 쉽게 웹 애플리케이션에 통합할 수 있습니다.
- **웹 뷰 지원**: iPhone을 웹에 최적화하여 원활한 웹 뷰를 제공합니다.
- **동적 iPhone 뷰 크기 조정**: iPhone 뷰의 크기를 동적으로 조정할 수 있습니다.
- **실시간 보기 전환**: 제어 박스를 통해 iPhone 뷰와 노트북 뷰를 실시간으로 확인하여 다양한 장치에서 레이아웃을 원활하게 테스트하고 최적화할 수 있습니다.
- **회전 기능**: iPhone 화면의 회전 기능을 제공합니다. (내부 콘텐츠는 회전되지 않습니다)

## 시작하기

```jsx
import { IPhoneLayout } from "react-iphone-layout";
import "react-iphone-layout/dist/ReactIPhoneLayout.css"; // ✨

function App() {
  return (
    <IPhoneLayout>
      <p>this is iPhone layout!!!</p>
    </IPhoneLayout>
  );
}
```

## 속성 (Props)

| **Props**   | **Type**                           | **Default** |
| :---------- | :--------------------------------- | :---------- |
| isStatusBar | boolean                            | true        |
| position    | `"top", "right", "bottom", "left"` | "right"     |
| mode        | `"iPhone", "laptop"`               | "iPhone"    |
| minSize     | number                             | 60          |
| defaultSize | number                             | 75          |
| maxSize     | number                             | 100         |

## 데모

- **CodeSandbox**: 온라인 편집기에서 react-iphone-layout 라이브러리를 사용해보세요. [데모를 보려면 여기를 클릭하세요.](https://codesandbox.io/p/devbox/react-iphone-layout-y3mcl7)

## 라이선스

MIT
