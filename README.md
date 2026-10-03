# Physics 2: Interactive Demos
**경상국립대학교 수학물리학부 1학년 물리학2 교과목 보조자료**

Landing page for the interactive web demos that accompany *Physics 2* (물리학2), a first-year course in the School of Mathematics and Physics, Gyeongsang National University. Every demo comes in both English and Korean.

**Live page:** https://lshlj82.github.io/physics-2/

Created by Claude Opus 5.5, based on the lecture notes by Prof. Sang Hoon Lee.
이상훈 교수의 강의노트를 바탕으로 Claude Opus 5.5가 만들었습니다.

## Demos · 데모 목록

| # | Demo | 데모 | Links |
|---|------|------|-------|
| 1 | Electric charge, field and potential, step by step | 전하, 전기장, 전기 퍼텐셜을 차근차근 알아보자 | [English](https://lshlj82.github.io/electrostatics-basic/index.html) · [한국어](https://lshlj82.github.io/electrostatics-basic/index_ko.html) · [source](https://github.com/lshlj82/electrostatics-basic) |
| 2 | Gauss's law and electric potential | 가우스 법칙과 전기 퍼텐셜 | [English](https://lshlj82.github.io/Gauss-law-and-potential/gauss-en.html) · [한국어](https://lshlj82.github.io/Gauss-law-and-potential/gauss-ko.html) · [source](https://github.com/lshlj82/Gauss-law-and-potential) |
| 3 | Capacitance | 전기용량 | [English](https://lshlj82.github.io/capacitance/capacitance.html) · [한국어](https://lshlj82.github.io/capacitance/capacitance_ko.html) · [source](https://github.com/lshlj82/capacitance) |
| 4 | Electric circuits | 전기회로 | [English](https://lshlj82.github.io/electric-circuit/circuits-en.html) · [한국어](https://lshlj82.github.io/electric-circuit/circuits-ko.html) · [source](https://github.com/lshlj82/electric-circuit) |
| 5 | RC circuit | RC회로 | [English](https://lshlj82.github.io/RC-circuit/rc-en.html) · [한국어](https://lshlj82.github.io/RC-circuit/rc-ko.html) · [source](https://github.com/lshlj82/RC-circuit) |
| 6 | Moving charges and magnetic fields | 움직이는 전하와 자기장 | [English](https://lshlj82.github.io/magnetism-basics/magnetism-en.html) · [한국어](https://lshlj82.github.io/magnetism-basics/magnetism-ko.html) · [source](https://github.com/lshlj82/magnetism-basics) |
| 7 | Electromagnetic induction and alternating current | 전자기 유도와 교류 | [English](https://lshlj82.github.io/EM-induction-AC/induction-en.html) · [한국어](https://lshlj82.github.io/EM-induction-AC/induction-ko.html) · [source](https://github.com/lshlj82/EM-induction-AC) |
| 8 | Maxwell's equations and light | 맥스웰 방정식과 빛 | [English](https://lshlj82.github.io/Maxwell-equations-light/maxwell-en.html) · [한국어](https://lshlj82.github.io/Maxwell-equations-light/maxwell-ko.html) · [source](https://github.com/lshlj82/Maxwell-equations-light) |

## About the page · 페이지 소개

The page is a single self-contained `index.html` with no build step. Its header runs a live version of demo 7: a bar magnet moves back and forth near a wire loop connected to a galvanometer, while plots show the flux through the loop and the induced emf ℰ = −*N* d*Φ*<sub>*B*</sub>/d*t* over the last 6 seconds. Arrows show the induced current and its field **B**<sub>ind</sub>, which always oppose the change (Lenz's law).

The page supports light and dark mode and adapts to phone screens. For visitors who have reduced motion turned on, it shows a still frame instead of the animation.

페이지는 빌드 과정 없이 `index.html` 파일 하나로 이루어져 있습니다. 상단에서는 데모 7을 실시간으로 실행합니다. 막대자석이 검류계에 연결된 고리 근처에서 왕복 운동하고, 그래프는 최근 6초 동안의 자기 선속과 유도 기전력을 보여줍니다. 화살표는 유도 전류와 그 전류가 만드는 자기장 **B**<sub>ind</sub>를 나타내며, 이 자기장은 언제나 변화를 거스릅니다(렌츠 법칙).

## Running locally · 로컬에서 실행

Open `index.html` in any modern browser. Fonts load from Google Fonts when online and fall back to system fonts otherwise.

## Deploying · 배포

1. Put `index.html` and this `README.md` at the root of the repository.
2. In **Settings → Pages**, set the source to the `main` branch, root folder.
3. The page will be served at `https://lshlj82.github.io/<repository-name>/`.

## References · 참고문헌

- Prof. Sang Hoon Lee, lecture notes for Physics 2. (이상훈 교수, 물리학2 강의노트)
