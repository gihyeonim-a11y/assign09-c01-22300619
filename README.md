# Deployment: GitHub URL, Vercel URL, MockAPI Endpoint URL 
https://6adea6f64e88f1bba4a53b5f.mockapi.io/

https://github.com/2026-2-OSS/assign09-c01-22300619.git

assign09-c01-22300619.vercel.app

# Service: 주제, Field, CRUD 기능
HTML, Bootstrap, JavaScript와 MockAPI를 활용해 개발한 학생 관리 웹 프로그램
데이터 필드는 이름, 나이, 전공, 학년의 총 4가지 속성으로 구성
비동기 통신을 기반으로 학생 정보의 등록, 실시간 검색, 수정, 삭제에 대한 전체 CRUD 기능이 구현
입력값 유효성 검증 및 예외 처리를 적용함

# Key Learning: fetch(), JSON, async/await, REST API 등 배운 내용 3가지
Fetch  서버와 비동기 HTTP 통신을 수행하는 인터페이스   
async/await: 비동기 코드를 동기식처럼 읽기 쉽고 직관적으로 작성하는 문법   
REST API: URI 기반으로 리소스를 표현하고 HTTP Method를 이용해 CRUD 작업을 수행
# AI / Search Usage: 사용 내역과 본인 추정 AI 코드 기여율(%)
사실 교수님의 pdf파일만 봐도 모든 과제를 수행할 수 있어서 AI 사용률이 10%정도도 안되었다. 문법을 이해하는 용도로 사용.

# Problem & Solution / Reflection: 문제 해결 및 느낀 점
updateStudent 구현할때, method를 Patch로 하니까 error가 계속 나서 Put으로 바꾸고나니 해결되었다.