# <p align="center">Treview(Truck Review)</p>

<p align="center">
<img width="50%" src="https://github.com/hyun5292/treview/blob/main/public/images/truck_long.png?raw=true" alt="Treview 로고">
</p>

## 기본 정보

> - 개발 기간<br/>22.12.15 ~ 23.04.06<br/>
>
> - 사이트 주소<br/> https://treview.netlify.app/<br/>
> - 사용 언어 및 개발 환경<br/> <span style="fontWeight: bold;"> <img height="15px" src="data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9Ii0xMS41IC0xMC4yMzE3NCAyMyAyMC40NjM0OCI+CiAgPHRpdGxlPlJlYWN0IExvZ288L3RpdGxlPgogIDxjaXJjbGUgY3g9IjAiIGN5PSIwIiByPSIyLjA1IiBmaWxsPSIjNjFkYWZiIi8+CiAgPGcgc3Ryb2tlPSIjNjFkYWZiIiBzdHJva2Utd2lkdGg9IjEiIGZpbGw9Im5vbmUiPgogICAgPGVsbGlwc2Ugcng9IjExIiByeT0iNC4yIi8+CiAgICA8ZWxsaXBzZSByeD0iMTEiIHJ5PSI0LjIiIHRyYW5zZm9ybT0icm90YXRlKDYwKSIvPgogICAgPGVsbGlwc2Ugcng9IjExIiByeT0iNC4yIiB0cmFuc2Zvcm09InJvdGF0ZSgxMjApIi8+CiAgPC9nPgo8L3N2Zz4K" alt="React 로고">
>   React 18.2.0
>   </span> <span style="fontWeight: bold;"><img height="15px" src="https://img.icons8.com/?size=2x&id=hsPbhkOH4FMe&format=png" alt="nodeJS 로고"> nodeJS 16.17.0</span> <span style="fontWeight: bold;"> <img height="15px" src="https://res.cloudinary.com/sudol5292/image/upload/v1694195999/vscode_rwngfk.png" alt="vsCode 로고" />
>   Visual Studio Code
>   </span><br/><span style="fontWeight: bold;"> <img height="15px" src="https://firebase.google.com/static/images/brand-guidelines/logo-vertical.png?hl=ko" alt="Firebase 로고">
>   Firebase 9.20.0</span><span style="fontWeight: bold;"> <img height="15px" src="https://cloudinary-marketing-res.cloudinary.com/image/upload/w_320,h_223,c_pad,b_auto:predominant,fl_preserve_transparency/v1652806223/cloudinary_cloud_glyph_regular.jpg?_s=public-apps" alt="Cloudinary 로고" />
>   Cloudinary
>   </span><br/><span style=""><img  height="15px" src="https://data.gg.go.kr/img/ggportal/desktop/common/h1.png" alt="경기도 데이터드림 로고" /> 경기도 데이터 드림 Open API</span>

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
> <img width="70%" src="https://res.cloudinary.com/sudol5292/image/upload/v1694415851/treview-storyboard/mainpg_agy0el.png" alt="main page storyboard">
>
> ### 공장 검색 페이지
>
> <img width="70%" src="https://res.cloudinary.com/sudol5292/image/upload/v1694415850/treview-storyboard/fsearchpg_vdwaph.png" alt="factory search page storyboard">
>
> ### 리뷰 목록 페이지
>
> <img width="70%" src="https://res.cloudinary.com/sudol5292/image/upload/v1694415850/treview-storyboard/reviewListpg_wocgoq.png" alt="review list page storyboard">
>
> ### 리뷰 작성 페이지
>
> <img width="70%" src="https://res.cloudinary.com/sudol5292/image/upload/v1694415850/treview-storyboard/writereviewpg_mnie6z.png" alt="review write page storyboard">
>
> ### 리뷰 수정 페이지
>
> <img width="70%" src="https://res.cloudinary.com/sudol5292/image/upload/v1694415850/treview-storyboard/editreviewpg_mdlma1.png" alt="review edit page storyboard">
>
> ### 로그인 페이지
>
> <img width="70%" src="https://res.cloudinary.com/sudol5292/image/upload/v1694415850/treview-storyboard/loginpg_niro2d.png" alt="login page storyboard">
>
> ### 회원가입 페이지
>
> <img width="70%" src="https://res.cloudinary.com/sudol5292/image/upload/v1694415850/treview-storyboard/joinpg_ojl0ym.png" alt="join page storyboard">
>
> ### 회원정보 수정 페이지
>
> <img width="70%" src="https://res.cloudinary.com/sudol5292/image/upload/v1694415850/treview-storyboard/editmemberpg_dh1k39.png" alt="member edit page storyboard">

## 화면 구성

> ### 메인 페이지
>
> <img width="70%" src="https://res.cloudinary.com/sudol5292/image/upload/v1694416646/treview-storyboard/screencapture-treview-netlify-app-2023-09-11-16_12_28_dnq1o3.png" alt="main page">
>
> ### 공장 검색 페이지
>
> <img width="70%" src="https://res.cloudinary.com/sudol5292/image/upload/v1694416646/treview-storyboard/screencapture-treview-netlify-app-search-2023-09-11-16_11_06_opea95.png" alt="factory search page">
>
> ### 리뷰 목록 페이지
>
> <img width="70%" src="https://res.cloudinary.com/sudol5292/image/upload/v1694416645/treview-storyboard/screencapture-treview-netlify-app-review-2023-09-11-16_11_55_drduv8.png" alt="review list page">
>
> ### 리뷰 작성 페이지
>
> <img width="70%" src="https://res.cloudinary.com/sudol5292/image/upload/v1694416646/treview-storyboard/screencapture-treview-netlify-app-review-write-2023-09-11-16_15_51_gx33vl.png" alt="review write page">
>
> ### 리뷰 수정 페이지
>
> <img width="70%" src="https://res.cloudinary.com/sudol5292/image/upload/v1694416648/treview-storyboard/screencapture-treview-netlify-app-review-edit-2023-09-11-16_16_32_nr0l65.png" alt="review edit page">
>
> ### 로그인 페이지
>
> <img width="70%" src="https://res.cloudinary.com/sudol5292/image/upload/v1694416646/treview-storyboard/screencapture-treview-netlify-app-user-login-2023-09-11-16_13_06_pewysi.png" alt="login page">
>
> ### 회원가입 페이지
>
> <img width="70%" src="https://res.cloudinary.com/sudol5292/image/upload/v1694416773/treview-storyboard/screencapture-treview-netlify-app-user-join-2023-09-11-16_19_18_kn29vu.png" alt="join page">
>
> ### 회원정보 수정 페이지
>
> <img width="70%" src="https://res.cloudinary.com/sudol5292/image/upload/v1694416647/treview-storyboard/screencapture-treview-netlify-app-user-edit-2023-09-11-16_14_05_bpt0zt.png" alt="member edit page">

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
