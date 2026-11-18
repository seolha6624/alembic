# 향의 장부 · 발디니의 증류기

TripoSplat(이미지 1장 → 3D 가우시안 스플랫)으로 만든 구리 증류기를 웹에서 보는 페이지.

- `alembic.ply` : TripoSplat 결과 (262,144개 가우시안)
- `index.html` : 뷰어 (three.js + Spark), 1-bit 디더 화면, 증류 슬라이더(스플랫이 호박색 향 입자로 증발), 떠다니는 향 입자
- `lib/` : three.js, Spark 라이브러리 (MIT)

사진: "Copper still from Meyer Brothers Pharmacy, St. Louis", Missouri History Museum, 퍼블릭 도메인
https://commons.wikimedia.org/wiki/File:Copper_still_from_Meyer_Brothers_Pharmacy,_St._Louis.jpg

로컬 실행: 이 폴더에서 `python -m http.server 8000` → http://localhost:8000
