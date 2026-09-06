# BASEKIT

사업의 시작과 성장에 필요한 브랜드, 웹, IR, 제품 디자인, 운영 시스템을 단계별 패키지로 제공하는 서비스 웹사이트입니다.

## Packages

- **BASE 500 · START** — 네이밍, 로고, 브랜드 가이드, 브랜드북, 회사소개서, 명함, 원페이지 랜딩페이지
- **BASE 1000 · LAUNCH** — 브랜드 구축, 회사소개서, IR 리뉴얼, 명함, 기능형 홈페이지, 패키지 디자인, 상세페이지
- **BASE 2000 · SCALE** — 10인 이상 기업 대상 CI, 기업 홈페이지, 기업 관리 시스템, 회사소개서/IR 상세 구축 및 기업 운영 디자인

## Structure

```text
index.html   # 메인 랜딩페이지
styles.css   # Design Token / Component / Pattern / Responsive CSS
script.js    # 모바일 메뉴 및 기본 인터랙션
```

## Design system

- Mobile First
- Desktop 12-column grid concept
- Content max-width 1040px / wide max-width 1280px
- Spacing token scale 기반
- Typography semantic hierarchy
- Button / Card / Navigation / Accordion 공통 규칙
- 제한적인 radius와 shadow
- 접근성 focus state 및 reduced motion 대응
- BASEKIT brand color: Orange + White + Neutral

## Brand tokens

```css
--brand: #ff6422;
--brand-hover: #e95618;
--brand-soft: #fff1e9;
--background: #ffffff;
--surface: #f7f7f5;
--text-primary: #111111;
--text-secondary: #666663;
--border: #e8e8e4;
```

## Development direction

`Design Token → Component → Pattern → Page` 순서로 확장합니다. 상세 패키지 페이지, 상담 폼, 고객 대시보드, 관리자 시스템을 추가할 때도 동일한 토큰과 컴포넌트 규칙을 유지합니다.
