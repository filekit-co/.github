## Hi there 👋

- https://filekit.co
- https://youtubetomp3.pages.dev

# July
## plan
- [ ] QR code (8월 delay)
- [ ] text Emoji
- [ ] Youtube 실시간 / 구글 실시간 검색어 = (나라 5곳) * 10개 * (36개국 언어로 번역) = 1800개 기사를 작성
  1. Chron job (일정 시간 스케쥴링되서 동작하는 task) 서버
    1. youtube api list get (실시간 인기 순위)
    2. transcript 뽑아내기
    3. gpt api (text -> 기사 markdown)
    4. cronjob server -> github markdown push -> svelte ci/cd publish
    5. svelte public/ 에 저장
    6. svelte static에서 보여주기 (36개국 언어로 번역)


## Role
- 효범 : text emoji 또는 끌리는 것
- 민욱 : 구글 실시간 cronjob 서버 -> 크롤링 -> gpt 만드는 서버 
- 세현 : elder.js 참고해서 sveltekit static blog 만들기 (레퍼런스 찾아보기) => markdown to html (ex. github.io)
  refs: https://joyofcode.xyz/sveltekit-markdown-blog
  refs: https://mdsvex.pngwn.io/
  

## 18
- minkj1992
  - [x] tiktok page
  - [x] features
  - [ ] getemoji
- seilylook
  - i18n
  - site 등록
  - 구글 애널리틱스
  - 구글 애드센스
  - tiktok page 추가
## 19
- minkj1992
  - [x] canonical csr로 바꾸기
  - [x] get emoji 작업
- seilylook
  - i18n 완료
  - site 등록
  - 구글 애널리틱스
  - 구글 애드센스
## 20
- mink1992
  - [ ] 다음 프로젝트 관련 search
  - [ ] gpt 서버
- seilylook
  - [x] i18n 완전히 무조건 끝내기
  - [x] 구글 애널리틱스, 애드센스 등록
  - [ ] QR code - 보류
## 24일
- minwk1992
  - [ ] 실시간 인기순위 transcript로 뽑아내는 서버 만들기
- seilylook
  - [ ] 테스트 데이터로 실제 페이지 만들어서 공유
  - [ ] seo structed data 조사 및 적용 검토
  - refs) https://developers.google.com/search/docs/appearance/structured-data/intro-structured-data?hl=ko
  - refs) https://json-ld.org/
  - refs) https://navillus.dev/blog/json-ld-in-sveltekit
## 26일
- mink1992
  - [ ] 서버 배포
  - [ ] 번역
- seilylook
  - [ ] seo structed data 조사 및 적용 검토
  - refs) https://developers.google.com/search/docs/appearance/structured-data/intro-structured-data?hl=ko
  - refs) https://json-ld.org/
  - refs) https://navillus.dev/blog/json-ld-in-sveltekit
