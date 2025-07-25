# 포트폴리오 웹사이트 만들기

> 고급웹프로그래밍 수업시간 기말과제<br>
> 나의 자기소개, 프로젝트, 경력을 정리한 React 기반 포트폴리오 웹사이트입니다.  

---

## 개요

- 제작 시기: 2023년 12월
- 주요 목적: 자기소개, 이력서, 프로젝트 정리 및 배포형 포트폴리오 구축
- 기술 스택: React.js, JSX, CSS 모듈

---

## 주요 구성

### 사이트 맵 구조
<img width="1125" height="483" alt="image" src="https://github.com/user-attachments/assets/61513a98-a567-47ec-adc9-77552e81bdac" />

<br>

> Component 구성

| 구분 | 파일명 | 설명 |
|------|--------|------|
| **Intro** | Resume, SelfIntro, Strength, Ability | 나의 소개 및 강점 |
| **Project** | JspProject, JavaProject, AndroidProject | 학부 시절 주요 프로젝트 |
| **Career** | WorkExperience, Charity | 아르바이트, 인턴, 봉사활동 |
| **공통** | Sidebar, Login, Index 등 | 기본 라우팅 및 UI 요소 |

<br>

> 스타일 구성 (CSS)

- 각 컴포넌트 별로 별도 CSS 파일 구성  
  예: `Ability.css`, `Career.css`, `Project.css`, `Resume.css` 등

- Sidebar 및 로그인, 소개 화면 등에 따로 스타일 적용

---

## 느낀 점

처음으로 **React를 활용해 실제 웹사이트 형태의 포트폴리오를 구현**해보면서,  
SPA 구조, 컴포넌트 단위 개발, 라우팅, 스타일링 등 실제 프론트엔드 개발에 필요한 전반적인 흐름을 익힐 수 있었다.
<br>
또한 자기소개서를 정리하며, **나의 기술 스택과 프로젝트를 어떻게 보여줄지 시각적으로 고민**해보는 계기가 되었고,  
추후에는 **이 사이트에 로그인 기능, 파일 다운로드 기능, 반응형 UI 개선** 등을 추가해보고 싶다.

---

## 배포 링크

[https://2yeonsong.github.io/](https://2yeonsong.github.io/)
