# BBC Learning English Study App

## 📋 프로젝트 개요

BBC Learning English의 "6 Minute English" 팟캐스트를 활용하여 리스닝, 스피킹, 라이팅, 단어/표현을 체계적으로 학습할 수 있는 웹 애플리케이션입니다.

### 핵심 컨셉
- **일주일에 하나의 에피소드를 깊게 학습**
- 6분짜리 자료로 4가지 영역(리스닝, 스피킹, 라이팅, 단어/표현) 동시 향상
- 부담 없는 학습량으로 꾸준한 학습 습관 형성
- 체계적인 5단계 학습 방법론 적용

## 🎯 학습 방법론

### 1단계: 제대로 듣기 (First Listening)
- **스크립트 없이 2-3번 듣기**
  - 1회차: 전체 흐름 파악
  - 2-3회차: 안 들리는 부분 집중해서 듣기
- 완벽하게 다 들리지 않아도 OK
- 안 들리는 부분이 어디인지 파악하는 것이 중요

### 2단계: 한 문장씩 듣고 분석하기 (Sentence Analysis)
- **한 문장씩 반복하며 듣기**
  - 한 문장당 3-4번 반복
  - 안 들린 부분 스크립트로 확인
- **문법/의미 분석**
  - 이해 안 되는 문장은 AI로 직독직해 분석
  - 각 문장의 구조와 의미 완전히 이해
- 하루에 전체를 다 하거나, 3분씩 나눠서 학습 가능

### 3단계: 자막 없이 전체 듣기 (Complete Listening)
- **처음부터 끝까지 스크립트 없이 듣기**
  - 안 들리는 부분이 있으면 멈추고 다시 듣기
  - 해석 안 되면 스크립트 다시 확인
- 어색함 없이 모두 이해될 때까지 반복

### 4단계: 표현을 내 것으로 만들기 (Expression Mastery)
- **핵심 표현 3-4개 선택**
  - BBC 에피소드에서 제공하는 핵심 표현
  - 또는 스크립트에서 유용한 표현 직접 선택
- **예문 만들기**
  - 각 표현마다 내 상황에 맞는 예문 3개 작성
  - 각 예문을 10번씩 소리 내어 말하기 (필수!)
- **플래시 카드 제작**
  - Anki 등의 앱 활용
  - 망각 곡선 활용: 1일 → 1주 → 1달 → 3달 후 복습
  - 장기 기억으로 저장

### 5단계: 말하기와 쓰기 (Speaking & Writing)
- **말하기 연습**
  - 에피소드 주제로 질문 만들기
  - 15초 생각 + 45초 말하기
  - 반드시 녹음하여 들어보기
  - 횡설수설 부분 파악 및 개선
- **쓰기 연습**
  - 에피소드 주제로 짧은 에세이 작성 (200-300단어)
  - 학습한 표현 3개 이상 반드시 사용
  - AI 피드백 활용 (문법 체크, 더 나은 표현 제안)
  - 피드백과 원본 비교하며 학습

## 🎨 주요 기능 요구사항

### 1. 에피소드 관리
- [ ] BBC 6 Minute English 에피소드 목록 표시
- [ ] 에피소드별 정보: 제목, 주제, 길이, 발행일
- [ ] 에피소드 검색 및 필터링 (주제별, 날짜별)
- [ ] 학습 중인 에피소드 표시
- [ ] 완료한 에피소드 기록

### 2. 1단계: 제대로 듣기
- [ ] 오디오 플레이어 (재생, 일시정지, 되감기, 빨리감기)
- [ ] 재생 횟수 카운터 (1회차, 2회차, 3회차 표시)
- [ ] 스크립트 숨김/보기 토글
- [ ] 안 들린 부분 타임스탬프 마킹 기능
- [ ] 메모 기능

### 3. 2단계: 한 문장씩 분석
- [ ] 문장 단위 재생 (현재 문장 하이라이트)
- [ ] 문장별 반복 재생 (자동 루프)
- [ ] 문장별 재생 횟수 추적
- [ ] 스크립트 토글 (문장별로 보기/숨기기)
- [ ] AI 문법 분석 요청 버튼
  - 선택한 문장 직독직해 분석
  - 문법 구조 설명
  - 단어 뜻 및 용법
- [ ] 어려운 문장 북마크 기능

### 4. 3단계: 전체 듣기
- [ ] 전체 오디오 재생 (스크립트 숨김 상태)
- [ ] 이해도 체크 버튼 (이해함/어려움)
- [ ] 어려운 구간 타임스탬프 표시
- [ ] 완료 확인 체크리스트

### 5. 4단계: 표현 학습
- [ ] 에피소드별 핵심 표현 목록 (BBC 제공)
- [ ] 커스텀 표현 추가 (스크립트에서 선택)
- [ ] 표현별 예문 작성 인터페이스
  - 예문 3개 입력란
  - AI 예문 제안 기능
- [ ] 예문 읽기 연습 카운터 (목표: 10회)
- [ ] 플래시 카드 생성
  - 표현 앞면, 예문 뒷면
  - Anki 형식 내보내기 지원
- [ ] 복습 스케줄러
  - 1일 후, 1주 후, 1달 후, 3달 후 알림
  - 복습 완료 체크
- [ ] 내 표현 컬렉션 (학습한 모든 표현 보관)

### 6. 5단계: 말하기와 쓰기
- [ ] **말하기 연습**
  - 에피소드 주제 기반 질문 생성
  - 15초 카운트다운 타이머
  - 45초 녹음 기능
  - 녹음 재생 및 저장
  - 녹음 기록 보관 (날짜별)
  - AI 피드백 (발음, 유창성, 문법)
- [ ] **쓰기 연습**
  - 에세이 에디터 (200-300단어 가이드)
  - 단어 수 카운터
  - 학습한 표현 사용 체크 (최소 3개)
  - AI 문법 체크 및 피드백
  - 더 나은 표현 제안
  - 작성한 에세이 저장 및 히스토리

### 7. 학습 진행 관리
- [ ] 주간 학습 진행도 (현재 단계 표시)
- [ ] 각 단계별 완료 체크리스트
- [ ] 일주일 학습 타임라인
  - Day 1: 1단계
  - Day 2-3: 2단계
  - Day 4: 3단계
  - Day 5-6: 4단계
  - Day 7: 5단계
- [ ] 학습 시간 추적
- [ ] 연속 학습 일수 (Streak)

### 8. 대시보드 및 통계
- [ ] 전체 학습 현황 한눈에 보기
- [ ] 완료한 에피소드 수
- [ ] 학습한 표현 총 개수
- [ ] 작성한 에세이 수
- [ ] 녹음 연습 횟수
- [ ] 주간/월간 학습 통계
- [ ] 학습 캘린더 (학습한 날짜 표시)

### 9. 사용자 설정
- [ ] 프로필 관리
- [ ] 학습 목표 설정
- [ ] 알림 설정 (복습 알림, 학습 리마인더)
- [ ] 테마 설정 (다크/라이트 모드)
- [ ] 오디오 재생 속도 조절

### 10. AI 통합
- [ ] 문장 분석 (직독직해, 문법 설명)
- [ ] 예문 생성 제안
- [ ] 에세이 피드백
- [ ] 말하기 피드백
- [ ] 학습 질문 답변

## 🛠 기술 스택 (제안)

### Frontend
- **React** (TypeScript)
- **Next.js** (SSR, Routing)
- **Tailwind CSS** (스타일링)
- **shadcn/ui** (UI 컴포넌트)
- **Zustand** 또는 **Redux Toolkit** (상태 관리)
- **React Query** (서버 상태 관리)

### Audio
- **Howler.js** 또는 **Web Audio API** (오디오 재생)
- **WaveSurfer.js** (오디오 시각화)
- **MediaRecorder API** (녹음 기능)

### Backend
- **Node.js** + **Express** 또는 **Next.js API Routes**
- **PostgreSQL** 또는 **MongoDB** (데이터베이스)
- **Prisma** 또는 **TypeORM** (ORM)

### AI Integration
- **OpenAI API** (GPT-4, GPT-3.5)
  - 문법 분석
  - 예문 생성
  - 에세이 피드백
  - 발음/유창성 피드백

### 인증
- **NextAuth.js** 또는 **Clerk**

### 배포
- **Vercel** (Frontend + API)
- **Railway** 또는 **Supabase** (Database)

## 📊 데이터 모델 (개념)

### Episode (에피소드)
```typescript
{
  id: string
  title: string
  topic: string
  description: string
  audioUrl: string
  transcript: Sentence[]
  keyExpressions: Expression[]
  duration: number // seconds
  publishedDate: Date
  difficulty: 'beginner' | 'intermediate' | 'advanced'
}
```

### Sentence (문장)
```typescript
{
  id: string
  episodeId: string
  text: string
  startTime: number // seconds
  endTime: number
  order: number
}
```

### Expression (표현)
```typescript
{
  id: string
  episodeId: string
  text: string
  meaning: string
  examples: string[]
  isBBCProvided: boolean
}
```

### UserProgress (사용자 진행도)
```typescript
{
  id: string
  userId: string
  episodeId: string
  currentStage: 1 | 2 | 3 | 4 | 5
  stage1Completed: boolean
  stage1ListenCount: number
  stage2CompletedSentences: string[]
  stage3Completed: boolean
  stage4Expressions: UserExpression[]
  stage5Speaking: SpeakingPractice[]
  stage5Writing: WritingPractice[]
  startedAt: Date
  completedAt?: Date
}
```

### UserExpression (사용자 표현 학습)
```typescript
{
  id: string
  userId: string
  expressionId: string
  customExamples: string[]
  practiceCount: number // 10회 목표
  reviewSchedule: {
    day1: { date: Date, completed: boolean }
    week1: { date: Date, completed: boolean }
    month1: { date: Date, completed: boolean }
    month3: { date: Date, completed: boolean }
  }
  flashcardId?: string
}
```

### SpeakingPractice (말하기 연습)
```typescript
{
  id: string
  userId: string
  episodeId: string
  question: string
  audioUrl: string // 녹음 파일
  duration: number
  transcription?: string // AI 전사
  feedback?: string // AI 피드백
  createdAt: Date
}
```

### WritingPractice (쓰기 연습)
```typescript
{
  id: string
  userId: string
  episodeId: string
  content: string
  wordCount: number
  usedExpressions: string[]
  feedback?: {
    grammar: string[]
    suggestions: string[]
    improvedVersion?: string
  }
  createdAt: Date
}
```

## 🎯 MVP (Minimum Viable Product) 우선순위

### Phase 1: 핵심 학습 기능
1. 에피소드 목록 및 선택
2. 1-3단계 리스닝 기능
   - 오디오 재생
   - 스크립트 보기/숨기기
   - 문장별 재생
3. 기본 진행도 추적

### Phase 2: 표현 학습
1. 4단계 표현 학습 기능
   - 표현 선택
   - 예문 작성
   - 복습 스케줄러
2. 플래시 카드

### Phase 3: 말하기/쓰기
1. 5단계 말하기/쓰기 기능
   - 녹음 기능
   - 에세이 작성
   - AI 피드백

### Phase 4: 통계 및 개선
1. 대시보드
2. 통계
3. 알림
4. UX 개선

## 📝 참고사항

### BBC Learning English 데이터 소스
- BBC Learning English API 또는 웹 스크래핑
- 에피소드 오디오 파일 URL
- 스크립트 텍스트
- 핵심 표현 및 단어

### 법적 고려사항
- BBC 콘텐츠 사용 권한 확인
- 저작권 및 라이선스 준수
- 교육 목적 fair use 검토

### 접근성
- 키보드 네비게이션
- 스크린 리더 지원
- WCAG 2.1 AA 준수

### 모바일 지원
- 반응형 디자인
- PWA (Progressive Web App) 고려
- 오프라인 학습 기능 (추후)

## 🚀 시작하기

1. 요구사항 상세 분석
2. UI/UX 디자인 및 프로토타입
3. 기술 스택 최종 확정
4. 데이터베이스 스키마 설계
5. MVP 개발 시작

---

**프로젝트 목표**: 일주일에 단 하나의 6분짜리 에피소드로 영어 4가지 영역을 모두 향상시킬 수 있는 가장 효율적이고 지속 가능한 학습 앱 만들기
