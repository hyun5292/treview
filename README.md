# <p align="center">Treview(Truck Review)</p>

<p align="center">
<img width="50%" src="https://github.com/hyun5292/treview/blob/main/public/images/truck_long.png?raw=true" alt="Treview 로고">
</p>

## 기본 정보

> - 개발 기간<br/>22.12.15 ~ 23.04.06<br/>
>
> - 사이트 주소<br/> https://treview.netlify.app/<br/>
> - 사용 언어 및 개발 환경<br/> <span style="fontWeight: bold;"> <img height="15px" src="https://github.com/hyun5292/treview/blob/main/public/assets/%EC%99%84%EC%84%B1%EB%B3%B8/logo/React.svg.png?raw=true" alt="React 로고">
>   React 18.2.0
>   </span> <span style="fontWeight: bold;"><img height="15px" src="https://github.com/hyun5292/treview/blob/main/public/assets/%EC%99%84%EC%84%B1%EB%B3%B8/logo/nodejs.png?raw=true" alt="nodeJS 로고"> nodeJS 16.17.0</span> <span style="fontWeight: bold;"> <img height="15px" src="https://github.com/hyun5292/treview/blob/main/public/assets/%EC%99%84%EC%84%B1%EB%B3%B8/logo/vscode.png?raw=true" alt="vsCode 로고" />
>   Visual Studio Code
>   </span><br/><span style="fontWeight: bold;"> <img height="15px" src="https://github.com/hyun5292/treview/blob/main/public/assets/%EC%99%84%EC%84%B1%EB%B3%B8/logo/firebase.png?raw=true" alt="Firebase 로고">
>   Firebase 9.20.0</span><span style="fontWeight: bold;"> <img height="15px" src="https://github.com/hyun5292/treview/blob/main/public/assets/%EC%99%84%EC%84%B1%EB%B3%B8/logo/cloudinary.png?raw=true" alt="Cloudinary 로고" />
>   Cloudinary
>   </span><br/><span style=""><img  height="15px" src="https://github.com/hyun5292/treview/blob/main/public/assets/%EC%99%84%EC%84%B1%EB%B3%B8/logo/datadream.png?raw=true" alt="경기도 데이터드림 로고" /> 경기도 데이터 드림 Open API</span>

## 프로젝트 소개

> <b>트럭(Truck) + 리뷰(Review)의 줄임말로,<br/>경기도 내 일반화물업체의 운송을 주선하는 업체의 정보를 검색할 수 있고<br/>공장별 리뷰를 남길 수 있는 사이트입니다.</b>
>
> 사용 API<br/>: https://data.gg.go.kr/portal/data/service/selectServicePage.do?page=1&rows=10&sortColumn=&sortDirection=&infId=38ON1INEO4P05Q4W0IO91211465&infSeq=1&order=&searchWord=%ED%99%94%EB%AC%BC<br/>
> ※해당 API는 데이터 갱신이 2018년 9월 6일자로 중지되었습니다.※
>
> ### 주요 기능
>
> - 공장 별 리뷰 열람 및 작성, 수정, 삭제
> - 회원 가입 및 정보 수정, 로그인, 로그아웃

## 스토리보드

> ### 메인 페이지
>
> <img width="70%" src="https://github.com/hyun5292/treview/blob/main/public/assets/%EC%99%84%EC%84%B1%EB%B3%B8/mainpg.png?raw=true" alt="main page storyboard">
>
> ### 공장 검색 페이지
>
> <img width="70%" src="https://github.com/hyun5292/treview/blob/main/public/assets/%EC%99%84%EC%84%B1%EB%B3%B8/fsearchpg.png?raw=true" alt="factory search page storyboard">
>
> ### 리뷰 목록 페이지
>
> <img width="70%" src="https://github.com/hyun5292/treview/blob/main/public/assets/%EC%99%84%EC%84%B1%EB%B3%B8/reviewListpg.png?raw=true" alt="review list page storyboard">
>
> ### 리뷰 작성 페이지
>
> <img width="70%" src="https://github.com/hyun5292/treview/blob/main/public/assets/%EC%99%84%EC%84%B1%EB%B3%B8/writereviewpg.png?raw=true" alt="review write page storyboard">
>
> ### 리뷰 수정 페이지
>
> <img width="70%" src="https://github.com/hyun5292/treview/blob/main/public/assets/%EC%99%84%EC%84%B1%EB%B3%B8/editreviewpg.png?raw=true" alt="review edit page storyboard">
>
> ### 로그인 페이지
>
> <img width="70%" src="https://github.com/hyun5292/treview/blob/main/public/assets/%EC%99%84%EC%84%B1%EB%B3%B8/loginpg.png?raw=true" alt="login page storyboard">
>
> ### 회원가입 페이지
>
> <img width="70%" src="https://github.com/hyun5292/treview/blob/main/public/assets/%EC%99%84%EC%84%B1%EB%B3%B8/joinpg.png?raw=true" alt="join page storyboard">
>
> ### 회원정보 수정 페이지
>
> <img width="70%" src="https://github.com/hyun5292/treview/blob/main/public/assets/%EC%99%84%EC%84%B1%EB%B3%B8/editmemberpg.png?raw=true" alt="member edit page storyboard">

## 화면 구성

> ### 메인 페이지
>
> <img width="70%" src="https://github.com/hyun5292/treview/blob/main/public/assets/%EC%99%84%EC%84%B1%EB%B3%B8/screencapture_main.png?raw=true" alt="main page">
>
> ### 공장 검색 페이지
>
> <img width="70%" src="https://github.com/hyun5292/treview/blob/main/public/assets/%EC%99%84%EC%84%B1%EB%B3%B8/screencapture_fsearchpg.png?raw=true" alt="factory search page">
>
> ### 리뷰 목록 페이지
>
> <img width="70%" src="https://res.cloudinary.com/sudol5292/image/upload/v1694416645/treview-storyboard/screencapture-treview-netlify-app-review-2023-09-11-16_11_55_drduv8.png" alt="review list page">
>
> ### 리뷰 작성 페이지
>
> <img width="70%" src="https://github.com/hyun5292/treview/blob/main/public/assets/%EC%99%84%EC%84%B1%EB%B3%B8/screencapture_reviewListpg.png?raw=true" alt="review write page">
>
> ### 리뷰 수정 페이지
>
> <img width="70%" src="https://github.com/hyun5292/treview/blob/main/public/assets/%EC%99%84%EC%84%B1%EB%B3%B8/screencapture_editreviewpg.png?raw=true" alt="review edit page">
>
> ### 로그인 페이지
>
> <img width="70%" src="https://github.com/hyun5292/treview/blob/main/public/assets/%EC%99%84%EC%84%B1%EB%B3%B8/screencapture_loginpg.png?raw=true" alt="login page">
>
> ### 회원가입 페이지
>
> <img width="70%" src="https://github.com/hyun5292/treview/blob/main/public/assets/%EC%99%84%EC%84%B1%EB%B3%B8/screencapture_joinpg.png?raw=true" alt="join page">
>
> ### 회원정보 수정 페이지
>
> <img width="70%" src="https://github.com/hyun5292/treview/blob/main/public/assets/%EC%99%84%EC%84%B1%EB%B3%B8/screencapture_editmemberpg.png?raw=true" alt="member edit page">

## Architecture

```
treview
├─ .gitattributes
├─ .gitignore
├─ package-lock.json
├─ package.json
├─ public
│  ├─ assets
│  ├─ favicon.ico
│  ├─ images
│  ├─ index.html
│  └─ _redirects
├─ README.md
├─ src
│  ├─ app.jsx
│  ├─ app.module.css
│  ├─ common
│  │  ├─ colors.css
│  │  └─ sizes.css
│  ├─ components
│  │  ├─ factory
│  │  │  └─ factory.jsx
│  │  ├─ factory_main
│  │  │  ├─ factory_main.jsx
│  │  │  └─ factory_main.module.css
│  │  ├─ factory_search
│  │  │  ├─ factory_search.jsx
│  │  │  └─ factory_search.module.css
│  │  ├─ factory_search_bar
│  │  │  ├─ factory_search_bar.jsx
│  │  │  └─ factory_search_bar.module.css
│  │  ├─ factory_table
│  │  │  ├─ factory_table.jsx
│  │  │  └─ factory_table.module.css
│  │  ├─ footer
│  │  │  ├─ footer.jsx
│  │  │  └─ footer.module.css
│  │  ├─ header
│  │  │  ├─ header.jsx
│  │  │  └─ header.module.css
│  │  ├─ header_menu
│  │  │  ├─ header_menu.jsx
│  │  │  └─ header_menu.module.css
│  │  ├─ img_uploader
│  │  │  ├─ img_uploader.jsx
│  │  │  └─ img_uploader.module.css
│  │  ├─ loading
│  │  │  ├─ loading.jsx
│  │  │  └─ loading.module.css
│  │  ├─ reset_btn
│  │  │  ├─ reset_btn.jsx
│  │  │  └─ reset_btn.module.css
│  │  ├─ review
│  │  │  └─ review.jsx
│  │  ├─ review_edit
│  │  │  ├─ review_edit.jsx
│  │  │  └─ review_edit.module.css
│  │  ├─ review_form
│  │  │  ├─ review_form.jsx
│  │  │  └─ review_form.module.css
│  │  ├─ review_list
│  │  │  ├─ review_list.jsx
│  │  │  └─ review_list.module.css
│  │  ├─ review_search_bar
│  │  │  ├─ review_search_bar.jsx
│  │  │  └─ review_search_bar.module.css
│  │  ├─ review_table
│  │  │  ├─ review_table.jsx
│  │  │  └─ review_table.module.css
│  │  ├─ review_write
│  │  │  ├─ review_write.jsx
│  │  │  └─ review_write.module.css
│  │  ├─ select
│  │  │  ├─ select.jsx
│  │  │  └─ select.module.css
│  │  ├─ user
│  │  │  └─ user.jsx
│  │  ├─ user_edit
│  │  │  ├─ user_edit.jsx
│  │  │  └─ user_edit.module.css
│  │  ├─ user_input_form
│  │  │  ├─ user_input_form.jsx
│  │  │  └─ user_input_form.module.css
│  │  ├─ user_join
│  │  │  ├─ user_join.jsx
│  │  │  └─ user_join.module.css
│  │  └─ user_login
│  │     ├─ user_login.jsx
│  │     └─ user_login.module.css
│  ├─ css
│  │  ├─ page.module.css
│  │  ├─ rForm.module.css
│  │  └─ table.module.css
│  ├─ dataFile
│  │  ├─ emailList.json
│  │  ├─ sigun_nm_list.json
│  │  └─ tel_num_list.json
│  ├─ images
│  │  ├─ truck.png
│  │  ├─ truckImg.png
│  │  └─ truckImg2.png
│  ├─ index.js
│  ├─ index.module.css
│  └─ service
│     ├─ auth_service.js
│     ├─ factoryList.js
│     ├─ firebase.js
│     ├─ ImageUploader.js
│     └─ review_service.js
└─ yarn.lock

```

<!-- Markdown Link & Image dfn's -->
