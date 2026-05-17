---
title: Privacy Policy
---

<section lang="ko" markdown="1">

# 개인정보 처리방침

<p class="caption">최종 수정: 2026-05-18</p>

MemCard는 가능한 한 적은 정보만 다루는 것을 원칙으로 합니다.

## 수집하지 않는 정보
- 계정 가입, 로그인, 개인정보를 요구하지 않습니다.
- 광고 식별자, 서드파티 분석 도구, 트래킹 SDK를 사용하지 않습니다.

## 기기에 저장되는 정보
저장한 단어, 복습 기록, 선택한 학습 언어는 Apple SwiftData와 `UserDefaults`를 통해 본인 기기에만 저장됩니다. 사용자가 직접 iCloud 백업을 활성화하지 않는 한 기기를 떠나지 않습니다.

## 백엔드로 전송되는 정보
단어 검색 시, 검색어와 대상 언어 코드(예: `en`, `ja`, `sv`)가 HTTPS를 통해 백엔드(Cloudflare Worker)로 전송됩니다. 백엔드는 사전 결과 생성을 위해 서드파티 LLM API에 질의를 전달하고, 결과를 앱으로 반환합니다.

검색 기록을 사용자 식별자와 연결하여 저장하지 않으며, 사용자별 검색 이력을 유지하지 않습니다. 기기 식별자, IP 기반 위치, 사용자 식별자는 의도적으로 수집하지 않습니다. 어뷰즈 방지 및 운영 모니터링 목적의 일반적인 요청 메타데이터(요청 시간, 크기 등)는 단기간 보존될 수 있습니다.

## 서드파티 서비스
- **Cloudflare** — 콘텐츠 전송과 서버리스 백엔드. <https://www.cloudflare.com/privacypolicy/>
- **서드파티 LLM 제공업체** — 사전 결과 생성. 검색어가 일반 API 요청의 일부로 전달됩니다.

## 아동 정보
MemCard는 4+ 등급이며, 아동을 포함한 누구의 개인정보도 의도적으로 수집하지 않습니다.

## 정책 변경
정책이 변경되면 본 문서의 "최종 수정일"이 갱신됩니다.

## 문의
<braverymoment@gmail.com>

</section>

<section lang="en" markdown="1">

# Privacy Policy

<p class="caption">Last updated: 2026-05-18</p>

MemCard is designed to handle as little information as possible.

## Information we do not collect
- No account, sign-in, or personal information is required.
- We do not use advertising identifiers, third-party analytics, or tracking SDKs.

## Information stored on your device
Saved words, review history, and your selected learning language are stored locally on your device using Apple's SwiftData and `UserDefaults`. This data never leaves your device unless you initiate an iCloud Backup (which we do not control).

## Information sent to our backend
When you search for a word, the search term and the target language code (e.g. `en`, `ja`, `sv`) are transmitted to our backend (a Cloudflare Worker) over HTTPS. The backend forwards the query to a third-party large language model (LLM) API to generate the dictionary entry, and returns the result to the app.

We do not associate searches with any user identifier and we do not maintain a per-user search history. We do not intentionally collect device identifiers, IP geolocation, or other identifying information. Standard server-side request metadata (timestamps, request size) may be retained briefly for abuse prevention and operational monitoring.

## Third-party services
- **Cloudflare** — content delivery and serverless backend. <https://www.cloudflare.com/privacypolicy/>
- **Third-party LLM provider** — used to generate dictionary entries. Search terms are forwarded as part of normal API requests.

## Children
MemCard is rated 4+ and is appropriate for all ages. We do not knowingly collect personal information from any user, including children.

## Changes to this policy
We may update this policy from time to time. Material changes will be reflected here with an updated "Last updated" date.

## Contact
<braverymoment@gmail.com>

</section>
