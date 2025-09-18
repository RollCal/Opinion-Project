# Opinion-Project

# 🌳 토론 커뮤니티 프로젝트 'Opinion'
> "찬반 투표를 넘어, 생각의 흐름을 시각화하는 새로운 토론의 장"

<br/>

## 📝 프로젝트 개요

'Opinion'은 기존의 찬반 투표만으로는 사용자의 다양한 생각과 그 이유를 파악하기 어렵다는 문제의식에서 출발한 프로젝트입니다. 사용자의 의견과 그에 대한 이유를 **트리 구조로 시각화**하여 보여주는 새로운 커뮤니티 서비스를 제안하고 기획했습니다.

2개월이라는 기간 동안 기획부터 개발, 팀 협업까지 전 과정을 관리하여 성공적으로 MVP(최소 기능 제품)를 출시했습니다.

<br/>

## ✨ 주요 기능

- **트리 구조 게시글**: 사용자의 의견과 그에 대한 꼬리 질문/답변이 나무처럼 뻗어나가는 시각적인 UI를 제공합니다.
- **임베딩 기반 의견 검색**: 백엔드와 협력하여 설계한 검색 API를 통해 사용자가 원하는 의견을 쉽게 찾을 수 있습니다.
- **실시간 토론 및 투표**: 다양한 주제에 대해 자신의 의견을 표현하고 다른 사람들과 생각을 나눌 수 있습니다.

<br/>

##  Architectural Diagram

<img width="4620" height="2452" alt="image" src="https://github.com/user-attachments/assets/9f7e8d84-2e6a-4c9e-bc65-c6f6babebcff" />

<br/>

## 🛠️ 기술 스택 (Tech Stack)

<table>
  <tr>
    <td align="center"><strong>Frontend</strong></td>
    <td>
      <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td align="center"><strong>Backend</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white"/>
      <img src="https://img.shields.io/badge/Gunicorn-499848?style=for-the-badge&logo=gunicorn&logoColor=white"/>
      <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white"/>
      <br/>
      <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"/>
      <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td align="center"><strong>Infrastructure</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Amazon AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white"/>
      <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
      <img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white"/>
      <img src="https://img.shields.io/badge/Amazon S3-569A31?style=for-the-badge&logo=amazons3&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td align="center"><strong>Collaboration</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
      <img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white"/>
      <img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white"/>
    </td>
  </tr>
</table>

<br/>

## 🔗 관련 링크

- **🎨 Figma (UI/UX Design)** : [[Figma - opinion](https://www.figma.com/board/ttny8aA9hGPNMAqGZqPxa6/Opinion?node-id=0-1&p=f&t=DpxtSQy7rRQJUUfY-0)]
- **👩‍💻 Front-End Repository** : [https://github.com/RollCal/onion_front](https://github.com/RollCal/onion_front)
- **👨‍💻 Back-End Repository** : [https://github.com/RollCal/onion](https://github.com/RollCal/onion)

<br/>

## 👨‍👩‍👧‍👦 팀원 소개 (Team Members)

| Position | Name | Role |
| :---: | :---: | :--- |
| **👑 Team Leader / PM** | **이정호** | - 프로젝트 총괄 기획 및 일정 관리 <br/> - Front-End 개발 및 Back-End 일부 기능 개발 <br/> - 공통 UI/UX 설계 참여 |
| **Back-End** | 이원도 | - 서버 배포 및 Back-End 개발 <br/> - 공통 UI/UX 설계 참여 |
| **Back-End** | 류종현 | - 데이터베이스 설계 및 Back-End 개발 <br/> - 공통 UI/UX 설계 참여 |
| **Front-End**| 장석천 | - Front-End 개발 및 Back-End 일부 기능 개발 <br/> - 공통 UI/UX 설계 참여 |

<br/>

## 🚀 주요 성과

- **성능 최적화 달성**: 게시글 트리 구조의 로딩 속도 저하 문제를 해결하기 위해 **Redis와 페이지네이션을 도입하여 로딩 속도를 93.44% 향상**시켰습니다.
- **성공적인 MVP 출시**: 목표 기간 내에 **기획했던 핵심 기능의 90% 이상을 구현**하여 완성도 높은 MVP를 출시하는 데 성공했습니다.
- **체계적인 협업 시스템 구축**: **Git 기반의 코드 형상 관리**와 **Notion을 통한 업무 현황 관리 체계**를 구축하여 효율적인 팀워크를 이끌었습니다.
