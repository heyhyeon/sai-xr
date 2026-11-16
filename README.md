# 사이 SAI — 시네마틱 XR 기획 홈페이지

사용자가 선택한 **사이 / SAI**를 상단 워드마크와 티켓에 적용한 버전입니다. 기존 큰 기차 창문, Seedance 영상 6편, AI 탑승, 브라우저 내 티켓 보관함을 유지합니다.

## 배포 (GitHub Pages · Netlify)

배포용 ZIP을 풀고 `index.html`과 `assets/` 폴더를 동일한 루트에 업로드합니다. `index.html`이 최상위에 있습니다. `/assets/video`에는 원본 Seedance 영상이 아닌 네트워크 실패 시 쓰는 간이 루프가 포함되어 있습니다.

외부 Seedance 영상 6편은 홈페이지에 URL로 연결되어 있습니다. 원본 URL이 차단되거나 접근 불가하면 간이 루프나 정지 이미지를 표시합니다. 장기간 안정적인 배포가 필요하면 Seedance 원본 MP4를 확보해 직접 호스팅해야 합니다.

기존 방문자의 저장 데이터를 보존하기 위해 내부 localStorage 키와 일부 개발용 식별자는 변경하지 않았습니다. 새 호스트에서는 호스트별로 저장 데이터가 독립적입니다.

`SAI_Cinematic_Homepage_Standalone.html`은 미리보기용 단일 파일입니다. 배포에는 폴더/ZIP 버전을 권장합니다.
