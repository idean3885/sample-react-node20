# 샘플 리액트 프로젝트
> API 서버와 통신하는 샘플 프로젝트입니다.  
> Port: 3000

## 1. 서버 실행 절차
### 1. api 서버 주소 변경
[src/index.js](src/index.js) 파일 10번째 줄 서버 주소 변경
![Api Domain 변경 가이드](https://github.com/idean3885/sample-react-node20/assets/43669379/beeebf18-0ff7-4fdd-a267-58cf12a89dc6)

### 2. 서버 실행
1. 패키지 인스톨
   ```
   npm ci
   ```
2. 서버 실행
   ```
   npm run dev
   ```

## 99. 참고
### 1. build 결과 배포
1. 패키지 인스톨
   ```
   npm ci
   ```
2. 프로젝트 빌드
   ```
   npm run build
   ```
3. 빌드 결과물 기준 서버 실행
   ```
   npx serve -sn build
   ```


