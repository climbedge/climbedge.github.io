# ClimbEdge Blog

https://climbedge.github.io — Send harder. Train wiser.

여러 클라이머·코치의 영상과 자료를 **주제별로 교차 분석**해 정리하는 블로그. 글이 원본이고, 글을 바탕으로 YouTube(@climbedge) 영상을 만든다.

## 운영 흐름: 글 → 영상
1. **주제 선정**: 한 주제(예: 오픈그립)를 정하고 관련 영상을 여러 채널에서 모은다(영어 자막 우선, 영상 파일은 받지 않음).
2. **교차 분석**: 공통점, 차이점, 근거 수준을 비교표로 정리한다.
3. **글 작성**: `templates/post-template.md`를 복사해 `_drafts/slug.md`에 작성한다.
4. **발행**: 완성되면 `_posts/YYYY-MM-DD-slug.md`로 옮겨 push한다. GitHub Pages가 자동으로 배포한다.
5. **영상화**: 글의 '한눈에 보기 → 비교표 → 갈리는 지점 → 적용' 순서를 대본 뼈대로 쓴다. 업로드 후 front matter의 `video.youtube`에 영상 ID를 넣으면 글 상단에 영상이 임베드된다.

## Front matter
- `axis`: `physical` | `technical`
- `topic`: 주제 묶음 이름. 주제 페이지에서 그룹핑된다.
- `sources`: 출처 목록. 글 하단에 자동으로 렌더링된다.
- `video.status`: `planned` → `scripted` → `recorded` → `published`

## 원칙
- 모든 출처를 표기한다. 원본 영상 화면은 허락 없이 쓰지 않는다.
- 단일 영상을 번역하는 대신 여러 관점을 종합한다.
- 부상 관련 내용은 의학적 조언이 아니다.
