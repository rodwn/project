#이 저장소는 가상의 프로젝트이다.

## 최상위폴더구조
### /iconFont: 아이콘폰트 관련
### /guide: 디자인 가이드
### /lib: 각종 플러그인
### /src: 마크업 폴더

## src구조

### /img
- bg_*, sp_*, img_* 로만 네이밍된 .png, .svg의 이미지 파일
- /svg_sprite: svg스프라이트 이미지
- /sprite: 스프라이트 이미지
- /temp: 임시이미지

### /font
- iconFont에서 생성된 것들이 여기로 들어오게 됨.

### /css, /js
- 컴파일된 css 관리 폴더
- /lib: 라이브러리 관련 css

### /scss
- /common: 초기화 파일, 변수, 공통레이아웃
- /lib: 스프라이트 관련 라이브러리, 자동생성 파일
- /import: 임포트
- /component: 컴포넌트단위 scss

### /inc
- 인클루드 파일