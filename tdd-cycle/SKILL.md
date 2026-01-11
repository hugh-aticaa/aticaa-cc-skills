---
name: tdd-cycle
description: TDD Red-Green-Refactor 사이클 가이드
allowed-tools:
  - Read
  - Write
  - Edit
  - Bash
  - Grep
---

# TDD Cycle Helper

Kent Beck 스타일 TDD 사이클을 진행해줘.

## 현재 단계 파악
1. 테스트 파일 확인
2. 실패하는 테스트 있는지 확인
3. 현재 Red/Green/Refactor 중 어느 단계인지 판단

## 단계별 행동

### 🔴 Red (테스트 없거나 실패)
- 가장 작은 실패 테스트 작성
- 테스트 실행해서 실패 확인

### 🟢 Green (테스트 실패 중)
- 테스트 통과하는 **최소한의** 코드 작성
- 테스트 실행해서 통과 확인

### 🔵 Refactor (테스트 통과)
- 중복 제거
- 네이밍 개선
- 구조 개선
- 테스트 재실행으로 검증

## 원칙
- 한 번에 하나의 테스트만
- 최소한의 코드로 통과
- 구조 변경과 기능 변경 분리
