# CHANGELOG — 하임스튜디오 (haimstudio-sample)

## v0.1 (2026-08-27) 최초 빌드 — 화보 중심 미니멀 에디토리얼
- **업종/컨셉**: 필라테스·바디프로필·요가 촬영 전문 스튜디오. B&W 모던(화이트/그레이/블랙) + 자연광 그라데이션. 잡지·화보 톤, UI 절제, 사진 풀블리드.
- **구성**: 헤더(투명→스크롤 시 화이트) → 히어로(풀블리드+자연광 스크림) → 스테이트먼트(텍스트) → Studio Frames 갤러리(10컷) → B&W 브레이크 bleed → Outdoor Archive 갤러리(10컷) → Studios 인트로 bleed + 4지점 그리드 → Pricing(다크) → Contact(카카오톡 CTA) → 푸터 + 모바일 퀵바.
- **폰트**: 제목=Space Grotesk(Tesseract Display 계열 무료 대체), 본문=Mulish(라틴, GHEA 계열)+Pretendard(한글). CDN(빌드), 납품 시 self-host 예정. ⚠️브랜드 로고·오버레이는 고대비 세리프 → 제목 세리프 디스플레이(Fraunces/Bodoni)로 전환 옵션 있음(사용자 확인).
- **CTA**: 카카오톡 채널 `pf.kakao.com/_fUtkK/chat`(메인, 퀵바 일치) + 전화 010-4546-2019(보조). 예약 동선=IG 컷 캡처 → 카톡 문의.
- **지점(실데이터)**: 하남 미사(대표, 미사강변한강로 135 스카이폴리스 나동 617호, 카카오맵 place 1475352278) · 부천(계남로263번길 31 3층) · 부산(용소로 13 경운빌딩 9층) · 야외(양평·부산·제주). 기구=캐딜락·리포머·체어·라더베럴.
- **가격(핵심)**: 필라/바디/요가 프로필 2컨셉 각 400,000 / 1컨셉 추가 +100,000 / 반컨셉 +50,000. 영상·헤메·야외는 "상담 안내"로 축약(미니멀).
- **이미지**: haim_archive·haimstudio_hanam 제공 112장 중 23컷 선별·최적화(1440/1680px q82, ~2.9MB), 슬러그 haim-hero/p01~p14/w01~w08. 로고 흑(logo-haim)·백(logo-haim-white) 2종. og-haim.jpg(1200×630, w02+로고 합성).
- **마감/안전**: color-scheme light·text-size-adjust·keep-all·overflow-x hidden·min-width:0, 폼 없음(문의=카톡), 고정바는 `<div>`(nav 상속 회피), 100svh 히어로, backdrop-blur 미사용(불투명), 리빌=데스크톱 전용+2.2s 안전망, noscript 폴백, 앵커 rAF 스무스(reduced-motion에도 강제), a11y(aria-expanded·focus-visible), 모바일 퀵바 safe-area.
- ⚠️미결(납품 시): 폰트 self-host, 도메인 확정 후 og/canonical/JSON-LD 치환, 히어로 크롭(object-position) 실기기 확인, 라이브 렌더 육안 검증.
