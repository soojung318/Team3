# 워크샵-Team3
node.js 서버로 부동산 매매 페이지 구현하기

## 👨🏼‍💻팀원 소개
<table>
  <tbody>
    <tr>
      <td align="center"><a href="https://github.com/soojung318"><img src="https://avatars.githubusercontent.com/u/106755183?v=4" width="100px" alt="Chris"/><br /><sub><b>신수정 </b></sub></a><br /></td>
      <td align="center"><a href=""><img src="" width="100px;" alt=""/><br /><sub><b>손빈 </b></sub></a><br /></td>
     <tr/>
  </tbody>
</table>

## 🛠️ 기술 스택
- Frontend : <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=HTML5&logoColor=white"/>, <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=CSS3&logoColor=white"/>, <img src="https://img.shields.io/badge/JSON-000000?style=flat&logo=JSON&logoColor=white"/>, <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=JavaScript&logoColor=white"/>, <img src="https://img.shields.io/badge/jQuery-0769AD?style=flat&logo=jQuery&logoColor=white"/>, <img src="https://img.shields.io/badge/Bootstrap-7952B3?style=flat&logo=Bootstrap&logoColor=white"/>
- Backend :  <img src="https://img.shields.io/badge/Node.js-339933?style=flat&logo=Node.js&logoColor=white"/>, <img src="https://img.shields.io/badge/mongoDB-47A248?style=flat&logo=MongoDB&logoColor=white"/>
- Version Control : <img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=GitHub&logoColor=white"/>

## ✒️구현 결과
|구현기능|구현여부|
|------|:---:|
|부동산 매매 도메인|⭕|
|매매 CRUD|⭕|
|검색 기능|⭕|
|웹 브라우저에서 동작|⭕|
|자산관리|❌|

## 🎬Demo
<img src="https://github.com/soojung318/Team3/assets/106755183/1c225f1e-0a3b-4a0f-bff6-7c2e1c6f897d" width="800" alt="데모영상"/>

<!--#### 매물 등록
![team3_input](https://github.com/soojung318/Team3/assets/106755183/f0ca1228-b9ed-473b-bc9e-e94fb2eeff09)
#### 매물 정보 수정
![team3_update](https://github.com/soojung318/Team3/assets/106755183/bfb1ccdf-6d2d-40cd-ae34-dfe022f9d514)
#### 매물 검색
![team3_search](https://github.com/soojung318/Team3/assets/106755183/8cb63ec6-9265-484a-95fb-620faa563969)
#### 매수
![team3_delete](https://github.com/soojung318/Team3/assets/106755183/0291f5fa-2695-4d28-804c-78bb25c2d875)
-->

## 🛢️구조
### MongoDB
`pair` 데이터베이스에 `realestate` 테이블 생성
- `id` : MongoDB 고유 ObjectId
- `title` : 매매할 건물명
- `address` : 건물 주소
- `price` : 매매가
- `num` : 매매 문의 연락처
- `size` : 면적
- `date` : 매물 등록일
```
{"_id":{"$oid":"6675339f7388ff6ebbca103d"},"title":"서초아파트","address":"서초구","price":"40억","num":"02-355-6636","size":"456.45","date":"2024-06-22"}
{"_id":{"$oid":"6675391dbee80fb171973527"},"title":"서초아파트","address":"서초구","price":"30억","num":"02-255-9888","size":"159.58","date":"2024-06-22"}
```

