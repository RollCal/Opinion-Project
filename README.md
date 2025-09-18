# Opinion-Project

# 🌳 토론 커뮤니티 프로젝트 'Opinion'
> "찬반 투표를 넘어, 생각의 흐름을 시각화하는 새로운 토론의 장"

<br/>

## 📝 프로젝트 개요

[cite_start]'Opinion'은 기존의 찬반 투표만으로는 사용자의 다양한 생각과 그 이유를 파악하기 어렵다는 문제의식에서 출발한 프로젝트입니다[cite: 13]. [cite_start]사용자의 의견과 그에 대한 이유를 **트리 구조로 시각화**하여 보여주는 새로운 커뮤니티 서비스를 제안하고 기획했습니다[cite: 14].

[cite_start]2개월이라는 기간 동안 기획부터 개발, 팀 협업까지 전 과정을 관리하여 성공적으로 MVP(최소 기능 제품)를 출시했습니다[cite: 15].

<br/>

## ✨ 주요 기능

- **트리 구조 게시글**: 사용자의 의견과 그에 대한 꼬리 질문/답변이 나무처럼 뻗어나가는 시각적인 UI를 제공합니다.
- **임베딩 기반 의견 검색**: 백엔드와 협력하여 설계한 검색 API를 통해 사용자가 원하는 의견을 쉽게 찾을 수 있습니다.
- **실시간 토론 및 투표**: 다양한 주제에 대해 자신의 의견을 표현하고 다른 사람들과 생각을 나눌 수 있습니다.

<br/>

##  Architectural Diagram

```
┌───────────┐        ┌──────────────────┐        ┌────────────────┐
│           │        │                  │        │                │
│  Client   │◀───────▶  Backend Server  │◀───────▶   Database/Cache │
│ (Browser) │        │     (API)        │        │   (DB, Redis)  │
│           │        │                  │        │                │
└───────────┘        └──────────────────┘        └────────────────┘
```
<br/>

## 🛠️ 기술 스택

| 구분 | 기술 |
| --- | --- |
| **Project Management** | [cite_start]`Notion`, `Git` [cite: 29] |
| **Backend** | [cite_start]`Redis`, `AWS` (언어/프레임워크 추가) [cite: 29] |
| **Frontend**| (언어/프레임워크 추가) |
| **Common**| [cite_start]`API 설계`, `DB 설계` [cite: 29] |

<br/>

## 🔗 관련 링크

- **🎨 Figma (UI/UX Design)** : [[Figma 링크를 여기에 붙여넣으세요](https://www.figma.com/board/ttny8aA9hGPNMAqGZqPxa6/Opinion?node-id=0-1&p=f&t=DpxtSQy7rRQJUUfY-0)]
- **👩‍💻 Front-End Repository** : [https://github.com/RollCal/onion_front](https://github.com/RollCal/onion_front)
- **👨‍💻 Back-End Repository** : [https://github.com/RollCal/onion](https://github.com/RollCal/onion)

<br/>

## 👨‍👩‍👧‍👦 팀원 소개

| 이름 | 포지션 | 주요 역할 |
| --- | --- | --- |
| **이정호** | **PM (Project Manager)** | - [cite_start]서비스 기획 및 UX 설계 리딩 [cite: 16, 18] [cite_start]<br/> - 개발 일정 및 우선순위 관리 [cite: 22] [cite_start]<br/> - 팀 협업 구조 설계 및 커뮤니케이션 총괄 [cite: 17, 26] |
| (이름 추가) | Front-End | (역할 추가) |
| (이름 추가) | Back-End | (역할 추가) |

<br/>

## 🚀 주요 성과

- [cite_start]**성능 최적화 달성**: 게시글 트리 구조의 로딩 속도 저하 문제를 해결하기 위해 **Redis와 페이지네이션을 도입하여 로딩 속도를 93.44% 향상**시켰습니다[cite: 20].
- [cite_start]**성공적인 MVP 출시**: 목표 기간 내에 **기획했던 핵심 기능의 90% 이상을 구현**하여 완성도 높은 MVP를 출시하는 데 성공했습니다[cite: 28].
- [cite_start]**체계적인 협업 시스템 구축**: **Git 기반의 코드 형상 관리**와 **Notion을 통한 업무 현황 관리 체계**를 구축하여 효율적인 팀워크를 이끌었습니다[cite: 25].
