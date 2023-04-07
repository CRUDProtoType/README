# Basic CRUD Project

## 기본규칙
- 3가지 버전 작성
- FullStack 
- Backend는 API만 제공
- FrontEnd는 API에 맞춘 데이터로만 작성
- Continer 기반 셋팅
- OS : RockyLinux 9 
   - 서버설정
   - 네트워크
   ```
      $ vi /etc/sysconfig/network-scripts/ifcfg-enp0s3
      $ 
   ```
- DB : Mysql
- Redis : container https://github.com/hong-havi/Redis
- Sql 스키마 https://github.com/CRUDProtoType/README/blob/main/BasicTable.sql
- 기본 기능
   - 회원가입
   - 로그인
   - 글 작성
   - 글 리스트
   - 글 수정
   - 글 삭제
  
  
  
## FullStack
### 필수사항
- 인증 세션
   - API시 JWT.. 등 인증 토큰 사용
   - Fullstack 세션
- ORM 사용가능시 ORM 사용
- Router 사용 및 통일
