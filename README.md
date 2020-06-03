# Study Storybook tutorial

- [Velopert Storybook Tutorial blog](https://velog.io/@velopert/design-system-using-typescript-and-storybook)
- [Velopert Storybook Tutorial repo](https://github.com/velopert/storybook-tutorial-code.git)

컴퍼넌트 기반으로 디자인 시스템을 구축한다. 스토리북을 활용하면 샘플로 만들어서 테스트 하던 페이지들을 문서화시킬 수 있다.
사용해본 경험으로는 손이 좀 많이 가긴 하는 것 같다. 샘플이 없으면 돌려보기 힘들었던 문제는 해소될 것 같다. 다만.. 시간이 있냐는게 문제.
타입스크립트도 그랬지만 적용하면 참 좋은데 쏟아부을 시간이..부족하다.

## Tech stack

- Storybook: UI Component API 같은 느낌으로 공유할 수 있음
- Typescript: JS에 타입을 추가. 코드에서 사용할 때 코드 인텔리센스등의 지원을 받을 수 있음
- emotion: CSS in JS 라이브러리. Styled-Component 처럼 활용할 수 도 있고, CSS 클래스 형태로도 사용할 수 있다.
- rollup: WebPack같은 번들링 툴. WebPack은 ES Module 형태로 번들할 수 없다. WebPack은 commonJS 형태로 번들링이 되는데, Tree-Shaking이 지원되지 않는다. 따라서 해당 프로젝트에서는 Rollup으로 번들링을 진행한다.
