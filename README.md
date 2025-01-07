![배너 이미지](./image/banner.jpg)

# 알쓰(흥미진진한 코딩 여행)

> 기업 코딩 테스트 합격을 목표로 하는 **Java 기반 알고리즘 스터디**입니다.

---

## 목차

1. [스터디 소개](#스터디-소개)  
2. [알고스터디 인원 소개](#알고스터디-인원-소개)  
3. [진행 방식](#진행-방식)  
   1. [알고리즘 재활 기간](#1-알고리즘-재활-기간)  
   2. [라이브 코딩 기간](#2-라이브-코딩-기간)  
4. [폴더 구조](#폴더-구조)  
5. [문제 제출 규칙](#문제-제출-규칙)  
6. [Git 사용 가이드](#git-사용-가이드)
7. [추가 규칙](#추가-규칙)
8. [일정](#일정)  
9. [문의](#문의)

---

## 스터디 소개

- **프로젝트 이름**: 알쓰(흥미진진한 코딩 여행)
- **목표**: 기업 코딩 테스트 합격
- **사용 언어**: Java (공식 문서만 검색 가능, 기타 자료 검색 지양)
- **플랫폼**: GitHub, Discord, Baekjoon(BOJ), Programmers(PG), Softeer(SOF)

---

## 알고스터디 인원 소개

<table>
  <tr>
    <td>
        <a href="https://github.com/goldenkiwi-hyeuk">
            <img src="https://avatars.githubusercontent.com/u/95901686?s=96&v=4" width="100px" />
        </a>
    </td>
    <td>
        <a href="https://github.com/doongyeop">
            <img src="https://avatars.githubusercontent.com/u/164111972?v=4" width="100px" />
        </a>
    </td>
    <td>
        <a href="https://github.com/jun-23">
            <img src="https://avatars.githubusercontent.com/u/78009502?v=4" width="100px" />
        </a>
    </td>
    <td>
        <a href="https://github.com/EH05">
            <img src="https://avatars.githubusercontent.com/u/133950134?v=4" width="100px" />
        </a>
    </td>
  </tr>

  <tr> 
    <td align="center"><a href="https://github.com/goldenkiwi-hyeuk">박성혁</a></td>
    <td align="center"><a href="https://github.com/doongyeop">이동엽</a></td>
    <td align="center"><a href="https://github.com/jun-23">정해준</a></td>
    <td align="center"><a href="https://github.com/gyungmean">최은혜</a></td>
  </tr>
</table>

---

## 진행 방식

### 1) 알고리즘 재활 기간
- **기간**  
  - 스터디 초기에 진행 (예: 2~4주 정도)
- **방식**  
  - 6문제를 **3+3** 형태로 두 번에 나누어 풀이  
    - 예시:  
      - 월요일 ~ 화요일 자정 전까지 3문제  
      - 수요일 ~ 금요일 자정 전까지 3문제
  - 문제는 현재 자신의 수준에 맞추어 자유롭게 선정
  - 각자 자신의 폴더에 `.java` 코드 업로드  
- **검사**  
  - 매주 화요일 0시, 금요일 0시(월·목 자정) 전까지 제출 여부만 확인  
  - 코드 리뷰는 진행하지 않음  
- **재활 기간 종료 후**  
  - 매주 2회 라이브 코딩 세션으로 진행 전환

### 2) 라이브 코딩 기간
- **기간**  
  - 재활 기간 종료 후, **매주 2회** 진행
- **시간**  
  - 1회당 약 **1시간 30분**
- **방식**  
  1. **숙제(공통 문제) 풀이 공유** (약 15분)  
     - 이전 숙제 문제에서 접근 방식 간단 공유  
  2. **라이브 코딩** (약 1시간)  
     - **디스코드** 이용  
       - 각자 **마이크 음소거**, **카메라 화면 ON** 상태에서 코딩 진행
       - Java 공식 문서(JDK Doc) 외 다른 자료 검색 지양  
     - 문제 난이도: **BOJ 골드3 ~ 플래티넘5**  
  3. **풀이·접근법 정리** (약 15분)  
     - 라이브 코딩 문제의 아이디어와 구현 내용 재정리  
- **추가 숙제**  
  - 라이브 코딩에서 다루다 미완성된 문제는 **다음 세션 전까지 완성**  
  - + 골드1 ~ 플래5 난이도 중 **스터디원들이 번갈아** 문제 1개 출제  
  - 해당 문제도 각자 폴더에 `.java` 파일 업로드

---

## 폴더 구조

```
├─ README.md # 스터디 개요 및 진행 안내
├─ 알고리즘 재활기간
│ └─ 1주차-1
│   ├─ 홍길동
│   │ ├─ BOJ1234_문제이름.java
│   │ ├─ BOJ5678_문제이름.java
│   │ └─ BOJ9999_문제이름.java
│   └─ 성춘향
│     ├─ BOJ1234_문제이름.java
│     ├─ BOJ5678_문제이름.java
│     └─ BOJ9999_문제이름.java
├─ 라이브 코딩 기간
│ └─ 1주차-1
│   ├─ 숙제
│   │ ├─ BOJ1234_문제이름_홍길동.java
│   │ └─ BOJ1234_문제이름_성춘향.java
│   └─ 라이브코딩
│     ├─ BOJ5678_문제이름_홍길동.java
│     └─ BOJ5678_문제이름_성춘향.java
```

- **알고리즘 재활기간**:  
  - 주차별 → 개인 폴더 → 해당 주차 기간에 3문제 (주 2회)
- **라이브 코딩 기간**:  
  - 각 주차·세션 폴더(`1주차-1-숙제`, `1주차-1-라이브코딩`)에 문제 및 본인 이름 포함 `.java` 파일 업로드
 
---

## 문제 제출 규칙

### 1) 알고리즘 재활 기간  
   - 매주 6문제(3+3)  
   - **화·금 0시**(월·목 자정) 전까지 제출  
   - 제출 여부만 확인 (코드 리뷰 없음)

### 2) 라이브 코딩 기간  
   - 라이브 코딩/숙제 폴더에 본인 이름(또는 아이디)이 포함된 파일 업로드  
   - 마감 시간 동일 (화·금 0시)

---

## Git 사용 가이드

### 1. 원본 레포지토리 Fork
   - 원본 레포지토리를 개인 GitHub 계정으로 Fork합니다.

### 2. 로컬 Clone
   - Fork한 저장소를 로컬 환경으로 Clone합니다.
   ```
      git clone https://github.com/<본인계정>/알쓰(흥미진진한코딩여행).git
   ```

### 3. **브랜치 생성**
   - 작업 시작 전에 반드시 새 브랜치를 생성합니다.
   - 브랜치명은 다음 규칙을 따릅니다:
   - week<주차>-<세션>-<이름>
   - 예시 : 
   ```
      git checkout -b week1-1-honggildong
   ```

### 4. **작업 후 커밋**
   - 작업 내용을 저장소에 추가하고 커밋합니다.
   - 커밋 메시지 규칙:
      - feat: 1주차-1 홍길동 BOJ1234 문제풀이
      - fix: 1주차-1 홍길동 BOJ5678 문제 수정
   - 커밋 명령어 예시:
   ```
      git add .
      git commit -m "feat: 1주차-1 홍길동 BOJ1234 문제풀이" || git commit -m "feat: 1주차-1 홍길동 BOJ1234 BOJ5678 BOJ9999 문제풀이" 
   ```

### 5. **푸시(Push)**  
   - 작업한 내용을 개인 Fork 저장소로 Push합니다.
   ```
      git push origin week1-1-honggildong
   ```

### 6. **Pull Request**  
   - 해당 기간 모든 파일을 전부 개인 저장소에 Push한 경우(알고리즘 재활기간 기준 3문항 / 라이브 코딩 기간 기준 2문항) Pull Request를 합니다.
   - GitHub에서 개인 Fork 저장소에서 원본 저장소로 Pull Request를 생성합니다.
   - PR 생성 시:
      - Base: 원본 저장소의 main 브랜치
      - Compare: 자신의 작업 브랜치
   - PR 제목 및 설명 규칙:
      - 제목: [1주차-1] 홍길동 문제 풀이
      - 설명 : 
         ```
            - 1주차 1세션 문제 풀이
            - BOJ1234: 문제 이름
            - BOJ5678: 문제 이름
         ```

### 7. **Pull Request Merge**  
   - 생성한 PR은 본인이 직접 Merge합니다.
   - GitHub에서 Merge 버튼을 눌러 작업을 반영합니다.
      - Merge 방식: Squash and Merge
    
### 8. **브렌치 삭제**  
   - Merge 완료 후, 사용했던 브랜치를 삭제합니다.
   ```
      git branch -d week1-1-honggildong  # 로컬 브랜치 삭제
      git push origin --delete week1-1-honggildong  # 원격 브랜치 삭제
   ```

---

## 추가 규칙

### 1. 항상 브랜치를 사용하여 작업
   - main 브랜치에서 직접 작업하거나 Push하지 않습니다.
   - 새 작업은 반드시 브랜치를 생성한 후 진행합니다.

### 2. 원본 저장소 최신 상태 동기화
   - 원본 저장소의 업데이트 내용을 정기적으로 Fork 저장소에 반영합니다.
   ```
      git remote add upstream https://github.com/goldenkiwi-hyeuk/Alsseu-ExcitingCodingJourney.git
      git fetch upstream
      git merge upstream/main
      git push origin main
   ```

### 3. 문제 풀이 파일 규칙
   - 파일명은 다음 형식을 따릅니다: BOJ<문제번호>_<문제이름>.java
   - 예시: BOJ1234_정렬.java

---

## 일정

- **알고리즘 재활 기간**  
  - 첫 4주 (조정 가능)  
  - 매주 6문제, 3+3 형태로 풀이  
  - **화·금 0시** 마감

- **라이브 코딩 기간**  
  - 재활 기간 후, 매주 2회 진행  
  - 1회당 약 1시간 30분  
  - 숙제 + 라이브 코딩 + 문제 풀이 공유

---

## 문의

프로젝트와 관련된 질문이나 제안 사항은 다음을 통해 문의하세요:

- **관리자**: 박성혁 (goldenkiwi971202@gmail.com)
