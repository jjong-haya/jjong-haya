# 함종하 | Jongha Ham

### Full-stack Developer · AI Voice Product Builder · Robotics Software Learner

<p>
  <a href="mailto:jongha0315@gmail.com"><img src="https://img.shields.io/badge/Email-jongha0315%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://github.com/jjong-haya"><img src="https://img.shields.io/badge/GitHub-jjong--haya-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" /></a>
  <img src="https://komarev.com/ghpvc/?username=jjong-haya&style=flat-square&color=2563EB" alt="Profile views" />
</p>

I build product flows that connect UI, API, data, cloud infrastructure, and AI workflows into one working service.

사용자가 바로 체감할 수 있는 서비스를 만들기 위해 프론트엔드, 백엔드, 데이터 모델, 인증/권한, AI 파이프라인을 함께 설계하고 구현합니다.

---

## Profile

| Area | Summary |
| --- | --- |
| Main Focus | Full-stack product engineering, AI voice interfaces, club/team operation platforms |
| Product Style | Practical workflows, admin tools, member management, realtime interaction, automation |
| Engineering Strength | UI/API integration, auth and permission modeling, structured AI output, deployment-aware design |
| Current Interests | AI voice logging, LLM workflow reliability, robotics software, cloud architecture |

## Core Skills

- **Frontend**: React, TypeScript, Vite, Tailwind CSS, Flutter, Riverpod
- **Backend**: NestJS, Express, Node.js, TypeORM, REST API, Swagger/OpenAPI
- **Database & Infra**: PostgreSQL, Supabase, MySQL, Redis, Firebase, AWS, S3, Lambda, Docker, Terraform
- **AI & Voice**: Gemini, OpenAI, audio LLM parsing, STT transcript parsing, structured JSON output, Zod schema validation
- **Realtime & Ops**: Socket.IO, WebSocket, JWT reauth flow, Prometheus metrics, Sentry monitoring
- **Robotics**: Python, C++, ROS 2, Linux-based robotics workflows

## Tech Stack

### Product Engineering

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

### Server, Data, Infrastructure

![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

### AI, Voice, Robotics

![Google Gemini](https://img.shields.io/badge/Google_Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Zod](https://img.shields.io/badge/Zod-3E67B1?style=for-the-badge&logo=zod&logoColor=white)
![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=for-the-badge&logo=socketdotio&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![ROS 2](https://img.shields.io/badge/ROS_2-22314E?style=for-the-badge&logo=ros&logoColor=white)

---

## Selected Projects

### PTLog AI Voice Platform

> AI voice workout logging platform that turns PT session audio into structured workout-log JSON.

PT 트레이너의 수업 녹음과 오디오 업로드를 운동일지 JSON으로 변환하는 AI 음성 기록 플랫폼입니다.

- Flutter 앱에서 운동별 음성 녹음, 오디오 파일 업로드, 분석 상태 UI를 구현했습니다.
- NestJS 백엔드에서 Gemini Audio LLM 기반 오디오 분석과 OpenAI/Gemini 텍스트 LLM 추상화를 구성했습니다.
- Zod 스키마를 JSON Schema로 변환해 LLM 구조화 출력을 강제하고, 운동명/세트/피드백 데이터를 안정적으로 파싱했습니다.
- Redis와 Socket.IO 기반 실시간 AI 세션 구조, 세션 재인증, 오디오 청크 ack/reject 흐름을 다뤘습니다.
- Prometheus와 Sentry를 통해 오디오 길이, LLM 호출 지연, 토큰 사용량, 실패율을 관측할 수 있게 설계했습니다.

**Role**: Full-stack · AI Integration · Backend Architecture  
**Tech**: `Flutter` `Riverpod` `Dio` `NestJS` `TypeORM` `PostgreSQL` `Redis` `Socket.IO` `Gemini` `OpenAI` `Zod` `S3` `Prometheus`

### Kmu_Kobot_Web

> KOBOT operations platform for members, permissions, projects, notices, bookings, and GitHub sync.

국민대학교 로봇 동아리 KOBOT 운영을 위한 회원/권한/프로젝트/공지/공간 예약 플랫폼입니다.

- React와 TypeScript 기반으로 운영자와 회원이 함께 사용하는 웹 워크스페이스를 구현했습니다.
- Supabase Auth, PostgreSQL RLS, 역할 기반 권한 모델을 활용해 기능별 접근 제어를 설계했습니다.
- 회원 승인, 공지, 프로젝트 모집/관리, 공간 예약, GitHub 연동 흐름을 하나의 운영 플랫폼으로 연결했습니다.
- 문서화와 마이그레이션을 함께 관리하며 실제 조직 운영에 필요한 변경 이력을 남겼습니다.

**Role**: Frontend · Backend Integration · Permission Design  
**Tech**: `React` `TypeScript` `Vite` `Supabase` `PostgreSQL` `RLS` `React Query`

### K-Game

> AWS-based AI game service with Daily Word and Prompt Room.

Daily Word와 Prompt Room을 포함한 AWS 기반 AI 게임 서비스입니다.

- React 프론트엔드와 Express API 서버를 분리한 3-tier 서비스 구조를 구성했습니다.
- AWS Lambda를 실시간 AI 응답, 힌트 생성, Daily Word 배치 생성 역할로 분리했습니다.
- RDS MySQL, EC2, S3, Lambda, Terraform을 활용해 인프라 구조를 코드와 문서로 정리했습니다.
- 제한된 IAM 권한 환경에서 배포 제약을 분석하고 가능한 우회 설계를 README에 명확히 남겼습니다.

**Role**: Full-stack · Cloud Architecture · AI Feature Design  
**Tech**: `React` `Express` `AWS Lambda` `RDS MySQL` `Terraform` `Bedrock`

### kmu-conquest

> Campus building conquest mobile game built with Flutter, Supabase, and geolocation.

국민대 캠퍼스 건물 점령전을 콘셉트로 한 위치 기반 모바일 게임입니다.

- Flutter와 Riverpod 기반으로 지도, 위치, 시즌, 전투, 미션 화면을 구성했습니다.
- Supabase 연동, Google Maps, geolocation, in-app purchase 등 모바일 서비스 요소를 실험했습니다.
- GPS 필터링, 실내 감지, 지오펜스 체크 등 위치 기반 게임에 필요한 로직을 분리했습니다.

**Role**: Mobile App Development · Location-based Game Logic  
**Tech**: `Flutter` `Dart` `Supabase` `Riverpod` `Google Maps` `Geolocation`

### kobot-website

> Official website for Kookmin University robotics club KOBOT.

국민대학교 로봇 동아리 KOBOT 공식 웹사이트입니다.

- 동아리 소개, 활동, 프로젝트, 공지 흐름을 담은 공식 웹사이트를 구현했습니다.
- React, TypeScript, Vite 기반으로 빠르게 배포 가능한 정적 웹 구조를 구성했습니다.

**Role**: Frontend Development  
**Tech**: `React` `TypeScript` `Vite` `Supabase` `Tailwind CSS`

---

## Activities

### KOBOT Robotics Club

- 로봇 동아리 운영과 프로젝트 흐름을 지원하는 웹 플랫폼을 개발했습니다.
- 로봇/임베디드/자율주행 학습과 Python, C++, ROS 2 기반 소프트웨어에 관심을 두고 있습니다.

### Full-stack and AI Product Projects

- 실제 사용자가 반복적으로 수행하는 업무를 줄이는 웹 서비스와 AI 워크플로를 주로 만들고 있습니다.
- 단순 데모보다 인증, 권한, 데이터 저장, 운영 화면, 배포 제약까지 포함한 서비스를 선호합니다.

---

## GitHub

<p>
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=jjong-haya&show_icons=true&theme=transparent&hide_border=true" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=jjong-haya&layout=compact&theme=transparent&hide_border=true" alt="Top languages" />
</p>

---

## Contact

- Email: [jongha0315@gmail.com](mailto:jongha0315@gmail.com)
- GitHub: [github.com/jjong-haya](https://github.com/jjong-haya)
