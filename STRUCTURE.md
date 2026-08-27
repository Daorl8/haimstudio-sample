# STRUCTURE — 하임스튜디오 (haimstudio-sample)

## 파일
- `index.html` — 단일 페이지(인라인 CSS/JS). 약 33KB.
- `haim-hero.jpg` — 히어로.
- `haim-p01~p14.jpg` — 세로 화보 컷(스튜디오/야외/B&W).
- `haim-w01~w08.jpg` — 가로 화보/브레이크 컷.
- `logo-haim.png` — 블랙 세리프 워드마크(투명). `logo-haim-white.png` — 화이트 버전(다크 섹션·푸터·헤더 오버).
- `og-haim.jpg` — 1200×630 공유 썸네일.
- `.assetsignore` — .git/문서/img 원본 제외(Workers 배포용).
- `img/` — 원본 112장(배포 제외).

## 섹션 순서 (index.html)
1. Header(#hdr, `<div>`) — 로고 흑백 토글 + 카카오 CTA + 버거/드로어
2. Hero — haim-hero, 헤드라인+카카오 CTA
3. Statement(.state) — 텍스트 전용
4. Work: Studio Frames(#work) — mag 그리드 10컷
5. Bleed(B&W, haim-w05) — "Sculpted by light"
6. Work: Outdoor Archive — mag 그리드 10컷
7. Bleed(haim-w01) + Studios(#studios) — 4지점 그리드
8. Price(#price, 다크) — 프로필 3종 + 추가옵션
9. Contact(#contact) — 카카오톡/전화 CTA
10. Footer + 모바일 퀵바(.qbar)

## 교체 대상 (납품/확정 시)
- 폰트 CDN → self-host(Space Grotesk·Mulish·Pretendard subset).
- 도메인 `haimstudio.pages.dev` 5곳(og:image·og:url·twitter:image·canonical·JSON-LD url) → 확정 도메인.
- 카카오 채널 `pf.kakao.com/_fUtkK/chat` (6곳) — 실채널 확인.
- 히어로 `object-position` — 실기기서 인물 크롭 확인 후 조정.
- (옵션) 부천·부산 카카오맵/네이버 링크 추가 시 지점 카드에.

## 데이터 출처
- 지점·기구·주차·가격·전화: 사용자 제공 텍스트(IG @haimstudio_hanam bio·안내문).
- 사진: IG @haim_archive, @haimstudio_hanam.
