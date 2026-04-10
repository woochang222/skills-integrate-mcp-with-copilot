# Issue Tracker for Extracurricular Activities Project

이 파일은 현재 프로젝트에 추가할 새로운 기능을 정리한 이슈 초안 목록입니다.

## Issue 1: Add authentication and role-based access control
- 학생과 직원 사용자 모두 로그인 기능 추가
- JWT를 사용해 인증 유지
- 학생 전용, 직원 전용 경로 분리
- 로그인 시 이메일 형식 검증

## Issue 2: Add MongoDB persistence and data models
- MongoDB 연결 및 Mongoose 도입
- 학습 활동, 사용자 프로필, 이벤트 데이터를 영속 저장
- 현재 메모리 저장 방식을 데이터베이스 기반으로 변경

## Issue 3: Add student profile management
- 학생 프로필 조회 화면 추가
- GitHub, LeetCode 같은 추가 정보 저장
- 프로필 정보 수정 기능 추가

## Issue 4: Add achievement management CRUD
- 학생 성취 항목 생성, 조회, 수정, 삭제
- 성취 항목에 카테고리, 레벨, 포지션, 보상, 주최자 정보 포함
- 학생별 성취 목록 대시보드에 노출

## Issue 5: Add file upload support for certificates and event materials
- 성취 증명서 파일 업로드 지원
- 이벤트 자료 파일 업로드 지원
- 업로드 파일을 저장하고 필요 시 다운로드/미리보기 가능하게 처리

## Issue 6: Add event creation and management
- 직원이 이벤트 생성 가능
- 이벤트 목록 조회 API 또는 페이지 제공
- 이벤트 삭제 기능 제공
- 이벤트에는 이름, 일시, 주최자, 카테고리, 보상, 안내 문구 포함

## Issue 7: Add staff student account management
- 직원이 학생 계정 생성 가능
- 학생 계정 삭제 기능 제공
- 학생 가입을 관리자가 직접 처리할 수 있도록 함

## Issue 8: Add tutor access and detailed student pages
- 배치(batch)별 학생 조회 기능 추가
- 개별 학생 상세 페이지 제공
- 튜터가 학생을 검색하고 정보 확인 가능하게 함

## Issue 9: Add server-rendered UI pages
- 템플릿 엔진 기반 대시보드 페이지 추가
- 로그인, 학생 대시보드, 직원 대시보드, 프로필, 성취 폼 페이지 등
- 현재 단일 정적 프론트엔드에서 동적 페이지로 확장
