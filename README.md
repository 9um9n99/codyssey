# 피우미 브랜드 광고 캠페인

창원특례시 공식 마스코트 **피우미**를 활용한 10초 이내 감성 브랜드 광고 제작 프로젝트.
Codyssey **GenAI 기초 2: 멀티모달 콘텐츠 제작** 과제 제출물입니다.

> 핵심 메시지: **"피우미와 함께, 창원의 봄을 틔우다"**

## 📄 제출물

| 항목 | 파일 |
|---|---|
| 스토리보드 기획 문서 (PDF) | [`storyboard/piumi_storyboard.pdf`](./storyboard/piumi_storyboard.pdf) |
| 최종 광고 영상 (MP4, 9.97초) | [`video/piumi_ad_final.mp4`](./video/piumi_ad_final.mp4) |

## 🎬 미리보기

<p align="center">
  <img src="./assets/images/scene1_image_final.png" width="23%">
  <img src="./assets/images/scene2_image_final.png" width="23%">
  <img src="./assets/images/scene3_startframe_final.jpg" width="23%">
  <img src="./assets/images/scene4_logo_card_asset.png" width="23%">
</p>
<p align="center"><sub>씬1 손인사 · 씬2 소원빌기 · 씬3 로고 변형(시작 프레임) · 씬4 브랜드 마무리</sub></p>

최종 영상 재생 (GitHub 업로드 후 아래 태그로 재생 가능):

```html
<video src="./video/piumi_ad_final.mp4" controls width="480"></video>
```

## 📁 폴더 구조

```
piumi-ad-campaign/
├── README.md
├── storyboard/
│   └── piumi_storyboard.pdf        # 기획 문서 (브랜드 정의·씬별 프롬프트·도구 비교 등)
├── video/
│   └── piumi_ad_final.mp4          # 최종 제출 영상 (1080p·30fps·H.264/AAC·9.97초)
└── assets/                         # 씬별 생성 원본 자산 (기획 문서 파일명 표기와 1:1 매칭)
    ├── images/
    │   ├── scene1_image_final.png
    │   ├── scene2_image_final.png
    │   ├── scene3_startframe_final.jpg / scene3_endframe_final.jpg
    │   ├── scene4_logo_card_asset.png             # 공식 브랜드 자산(투명배경 고해상도)
    │   └── scene0_walking_image_notused.png       # 초기 기획 씬(최종 미포함)
    ├── videos/
    │   ├── scene1_video_final.mp4
    │   ├── scene2_video_candidate_notused.mp4     # 소원빌기용 영상 후보(최종컷은 정지이미지 팬/줌 채택)
    │   ├── scene3_video_part1.mp4 / scene3_video_final.mp4   # 로고 변형 최종 2파트
    │   ├── scene3_draft_4petals_issue.mp4         # 프롬프트 수정 전(꽃잎 4개 오류)
    │   ├── scene3_draft_closespacing_issue.mp4    # 프롬프트 수정 중간본(간격 오류)
    │   ├── scene0_walking_video_notused_v1.mp4
    │   └── scene0_walking_video_notused_v2.mp4    # 초기 기획 씬 후보(최종 미포함, 비율 문제로 제외)
    └── audio/
        ├── narration_scene1_hello.mp3
        ├── narration_scene2_wish.mp3
        └── bgm_source_full.mp3                    # Suno 원곡(편집 시 필요 구간만 트리밍)
```

## 🛠 사용 도구

| 용도 | 도구 |
|---|---|
| 이미지 생성 | ChatGPT (GPT-4o) |
| 비디오 생성 | Kling AI 3.0 |
| 오디오(TTS) | GPT-4o Mini TTS (nova) |
| 편집 | VITA |

자세한 선정 이유, 씬별 프롬프트 원문, 수정 전/후 비교는 [스토리보드 문서](./storyboard/piumi_storyboard.pdf)를 참고하세요.

## ✅ 과제 요구사항 체크리스트

- [x] 브랜드 아이덴티티 / 캠페인 목표 / 핵심 메시지 정의
- [x] 씬 단위 스토리보드 (필수 필드 전부 기재)
- [x] 프롬프트 "수정 전/후" 비교 기록 (씬3, 2건)
- [x] 이미지·비디오·오디오 생성 AI 각 1종 이상 사용
- [x] 10초 이내 (9.97초)
- [x] 마지막 3~5초 구간 내 브랜드 인지 장치(로고+브랜드명) 포함
- [x] 명확한 메시지 전달 구조 (발견→메시지→브랜드 연결→마무리)
- [x] 보너스1: 립싱크 적용 (씬1)
