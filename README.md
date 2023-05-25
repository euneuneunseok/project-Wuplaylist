# 무:플리 프로젝트

# 프로젝트 소개

  음악만 플레이리스트가 있나? 영화도 있다!

  영화에 대해 이야기하는 사람들이 모이는 영화 추천 및 소통 커뮤니티 사이트

  <br>

# 개발 기간

- 23.05.18 - 23.05.25 (7일)

<br>

## 🤝 팀원 정보 및 업무 분담
  
| 이름   | 담당 영역                                                    | 
| ------ | ------------------------------------------------------------ | 
| 황종인 | - 프론트엔드(70%) / 백엔드(30%)<br />- 백엔드 데이터를 받아와 프론트엔드 기능 구현 및 디버깅, 테스트 |
| 이은석 | - 프론트엔드(30%) / 백엔드(70%)<br />- DB 모델링, 백엔드 데이터 로직 작성, 프론트엔드 디자인 정교화 |

## 개발 환경

  <img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white"> 
  <img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white"> 
  <img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white"> 
  <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
  <img src="https://img.shields.io/badge/vue.js-4FC08D?style=for-the-badge&logo=vue.js&logoColor=white"> 
  <img src="https://img.shields.io/badge/django-092E20?style=for-the-badge&logo=django&logoColor=white">
  <img src="https://img.shields.io/badge/bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white">



### 💻 필수 요구사항

| No.  | 구분               | 기능                                 | 구현 정도(⭐⭐⭐⭐⭐)                                            |
| ---- | ------------------ | ------------------------------------ | ----------------------------------------------------------- |
| 1    | 영화 데이터         | 최소 50개 이상 존재           | ⭐⭐⭐⭐⭐                                                       |
| 2    |                    | 데이터 fixture에 저장         | ⭐⭐⭐⭐⭐                                                       |
| 3    | 추천 알고리즘       | 최소 1개 이상의 영화를 추천 받아야함 | ⭐⭐⭐⭐⭐                                                  |
| 4    |                    | 추천 알고리즘 기술적 설명            | ⭐⭐⭐⭐⭐                                                  |
| 5    | 커뮤니티           | 유저가 소통할 수 있는 커뮤니티 기능  | ⭐⭐⭐⭐⭐                                                    |
| 6    | 에러 페이지           |필요에 따라 적절한 에러 페이지 구성   | ⭐⭐⭐⭐⭐                                                    |




# 목표 서비스 구현 및 실제 구현 정도

  1. 신작 & 개봉 예정인 영화 목록
  2. 평점 높은 영화 목록
  3. 장르로 필터링한 목록 보여주는 페이지
    - (영화 이름으로 검색하는 기능)
  4. 영화 플레이리스트를 공유하는 커뮤니티
    - 댓글, 대댓글, 좋아요 기능
    - 인기 플레이리스트를 홈 화면에 노출시키기?

  
# 데이터베이스 모델링 (ERD)

<img src="./1학기_final_pjt.png" alt="erd">


# 개발 일지
| No.  | Date     | Name   | ToDo                                                         | 
| ---- | -------- | ------ | ------------------------------------------------------------ | 
| |~23/5/21| 이은석&황종인 | 기본 기능 구현<br> 디자인, 컨셉 설정 |
| |23/5/22 | 이은석 | 팔로우 버튼 디테일 <br> 데이터 베이스 runserver 시 자동 갱신|  
| | 23/5/22 | 황종인 | 로그인 시 state에 로그인한 유저 정보 저장<br> 게시글,댓글 좋아요 기능| 
| |23/5/23 | 이은석 | 영화 디테일 modal 제작<br> 장르 모델 추가<br> 장르 한글 데이터를 store 저장<br> 장르 필터링 버튼 제작 <br> 장르로 영화 필터링 기능 구현  |  
| | 23/5/23 | 황종인 | 게시글 모델 movies M:N연결<br> 플레이리스트에 영화 포스터 미리보기 제작 <br> 프로필 페이지에 작성한 플레이리스트, 팔로우,팔로잉, 정보 출력 <br>  | 
| |23/5/24 | 이은석 | 영화 데이터 overlay로 제목 보여주기 구현 <br> 홈에서 영화 보여주는 방식 스크롤 사용 <br> 팔로우한 사람의 플레이리스트 보여주기 구현 <br> 좋아요 수가 많은 플레이리스트 보여주기 <br> 플레이 리스트 카드 모양 디자인 <br> | 
| | 23/5/24 | 황종인 | 유저가 만든 플레이리스트 홈화면에 출력<br> 플레이리스트 각족 버튼 위치 디자인 수정 <br> 회원가입 시 메시지 출력 <br> 로그인 시에만 접근 가능한 페이지 설정 <br>|
| |23/5/25 | 이은석 | 전체 배경색 설정 <br> Nav bar 하나로 적용 <br> 프로필 페이지 CSS 적용 <br> 회원가입, 로그인 페이지 CSS 적용 <br> 전체적 버그 수정, CSS 수정 |
| | 23/5/25 | 황종인 | 작성시각, 수정시각 포맷팅 <br> 플레이리스트에 영화 담을 때 중복 제거 <br> 팔로우 플레이리스트 작성자 이름과 작성 시간 출력 <br> 버그 수정, css 수정  |





# 📝 영화 추천 알고리즘에 대한 기술적 설명

1. 유저들이 작성한 플레이리스트 중 좋아요가 가장 많은 3개의 인기 플레이리스트 추천

  - final-pjt-front/src/components/ReviewPopular.vue

  - 메인 알고리즘

    전체 플레이리스트를 좋아요 기준 순으로 정렬 시키고 좋아요 수가 가장 많은 세개만 각자 출력

  ```javascript

    sortedArticles() {
        const newArticles = []
        for (const article of this.$store.state.articles) {
          newArticles.push(article)
        }

        let editArticles = newArticles.sort(function(a,b){
          return b.like_user.length - a.like_user.length
        })
        return editArticles
      },

  ```

2. 자신이 팔로우한 사람들의 최신 순서로 플레이리스트 추천


FollowPlaylist.vue
- 최근 게시글부터 탐색을 해서 게시글의 작성자가 접속한 유저가 팔로잉한 유저인 경우 게시글의 작성자를 포함한 데이터를 가공하여 리스트에 저장하고 가장 최근의 게시글이 출력되면서 작성한 유저까지 보이도록 만듦 

```javascript
  getArticles(){
      // 팔로잉한 사람의 게시글을 최근 게시글부터 탐색
      const reverse = [...this.Articles].reverse()
      for (const article of reverse) {
          if (this.currentUser.followings.includes(article.user)) {
              this.followingArticles.push(article)
                axios({
                    method: 'get',
                    url: `${API_URL}/accounts/user/detail/${article.user}/`,
                    headers: {
                        Authorization: `Token ${ this.token }`,
                    }    
                })
                .then((res) => {
                    const userInfo = {
                        ...article,
                        username: res.data.username
                    }
                    this.followingArticlesPlusAuthor.push(userInfo)
                })
                .catch(err => console.log(err))
                
              }
              
          }
      },

```

# 이슈 관리

<hr>
```
게시글의 댓글을 불러오는 과정에서 Type Error
```
### 해결 
- article의 초기값은 null이고 axios 요청으로 값이 렌더린 되는데 null 값의 id는 읽어올 수 없어서 오류
- article이 렌더링되었을 때 실행되도록 `v-if="article"` 을 통해 해결
<hr>


```
댓글을 생성하고 새로고침하지 않고 댓글을 띄우기 위해 router.push를 활용했는데 경로의 name에 id가 들어가있어서 param으로 보내주는 방법이 필요했음
```

### 해결
- 
<hr>

```
중복 영화 데이터가 db에 저장되어서 오류가 발생
```
### 해결
- 원인은 모르겠지만 데이터를 최초 저장하는 과정에서 발생한 오류로 예상
- migrate를 새로 해줌

<hr>

```
플레이리스트 게시글에서 로그아웃을 하면 나오는 빈 화면이 그냥 나왔음 
```
### 해결
- 로그인이 필요하다는 안내를 해주는 alert를 보여주고, 로그인 페이지로 이동하게 만듦

<hr>

```
플레이리스트에 영화를 추가하면 영화를 추가한 순서대로 출력되지 않음
movie_id 순서대로 출력
플레이리스트 수정할 때 영화를 제외하고 수정을 취소하면 새로고침을 하기 전까지는 영화가 제외된 상태로 출력 됨
```

<hr>

```
테이블에서 migrate를 해도 테이블이 없다고 하는 에러
no such table: movies_movie
```

### 해결
- 데이터 테이블이 생성되기 전에 데이터 저장 함수가 먼저 호출되어서 그런 것으로 예상
- 일단 임시로 operator에서 임시로 주석처리를 해두고 migrate을 한 후에 데이터 저장 진행

<hr>

```
javascript 정렬 기능을 제대로 알지 못했음
```
### 해결
- a-b 오름차순, b-a 내림차순
```
  const articles = this.$store.state.articles
    articles.sort(function(a,b){
      return parseFloat(b.like_user.length)-parseFloat(a.like_user.length)
})
```

- reverse() 기능 사용 가능

<hr>
<br>

# 서비스 구현

| No   | 기능          | 기능 설명        | 구현 정도(⭐⭐⭐⭐⭐) | 실제 구현 수준         | 
| ---- | --------------| ----------------| ---------------- | ---------------- |
| 1    | 로그인       | all auth를 통한 로그인 기능 구현  | ⭐⭐⭐⭐⭐   |   |          
| 2    | 로그아웃   | all auth 을 통한 로그아웃 기능 구현    | ⭐⭐⭐⭐⭐  | | |  
| 3    | 회원가입      | 필요한 데이터를 담아서 직접 만든 회원 가입 기능 구현  |⭐⭐⭐⭐⭐    |  |  |          
| 4    | 전체 영화 리스트 | 데이터에 있는 모든 영화 조회 | ⭐⭐⭐⭐⭐  | | |          
| 5    | 인기 플레이 리스트 조회 | 좋아요가 많은 top 3 조회  | ⭐⭐⭐⭐⭐  | | |  
| 6    | 팔로잉 플레이리스트 | 팔로우한 사람의 최신 업데이트된 플레이리스트 조회 | ⭐⭐⭐⭐⭐  | | |  
| 7    | 장르 선택 버튼 | 여러개 클릭 가능 <br> 다시 선택시 취소 | ⭐⭐⭐⭐⭐  | | |  
| 8    | 선택한 장르에 따른 영화 조회 | 위에서 선택한 장르에 따른 영화 조회  | ⭐⭐⭐⭐⭐  | | |  
| 9   | 플레이리스트 | 만들어진 모든 플레이리스트 조회, 플레이리스트에 포함된 영화 포스터들도 바로보기 가능, 좋아요 기능  | ⭐⭐⭐⭐⭐  | | |  
| 10   | 플레이리스트 생성 | 플레이리스트에 제목, 내용, 영화들 담아서 생성 가능  | ⭐⭐⭐⭐⭐  | | |  
| 11   | 플레이리스트 상세 정보 조회 | 제목을 클릭해서 접근, 상세 정보들 확인 가능 | ⭐⭐⭐⭐⭐  | | |  
| 12    | 영화 정보 모달 | 메인 홈페이지, 플레이리스트의 상세페이지 <br> 장르별 영화 추천 페이지에서 모달로 영화 상세 정보 조회 가능  | ⭐⭐⭐⭐⭐  | | |  
| 13    | 플레이리스트 댓글 CRUD 기능 | 댓글 생성, 좋아요, 수정, 삭제, 기능  | ⭐⭐⭐⭐⭐  | | |  
| 14    | 라우터의 자신의 프로필 페이지 | 작성한 게시글 개수, 작성한 게시글, 이름 ,소개글, 팔로워, 팔로잉 조회 가능  | ⭐⭐⭐⭐⭐  | | |  
| 15    | 유저 아이디를 클릭해서 들어간 프로필 | 작성한 게시글 개수, 작성한 게시글, 이름 ,소개글, 팔로워, 팔로잉 조회 가능 <br> 자신의 프로필이 아니라면 팔로우,언팔로우 가능  | ⭐⭐⭐⭐⭐  | | |  
| 16    | 로그인,비로그인 상태에 따른 Nav bar | 로그인이 되어있으면 프로필/로그아웃 <br> 로그인이 안되어있으면 로그인/회원가입  | ⭐⭐⭐⭐⭐  | | |  
| 17    | 플레이리스트 영화 검색 | 플레이리스트 작성할 때 영화 선택을 하기 위한 영화 제목 검색 기능<br>  | ⭐⭐⭐⭐⭐  | | |  
| 18    | 플레이리스트 수정 기능 | 수정할 때 영화를 검색해서 다시 추가,삭제 가능하고 이미 선택된 것이라면 불투명 표시  | ⭐⭐⭐⭐⭐  | | |  



# 기타 (느낀 점, 후기)

## 이은석

## 황종인