---
layout: post
title: 2016.4.27 - Jekyll now 설치
---

- [emberjs 동영상](https://www.youtube.com/watch?v=aUDxlEnuFTg) 중간까지 봄 #웹 #웹앱 #JS #프레임워크
- 지킬 나우를 설치 및 설정 #웹 #블로그

블로그에 대한 자세한 설명은 [Github 저장소](https://github.com/sftblw/tilog-ch)를 확인하세요.

# 앰버 동영상에 관해

동영상을 한 번 보는 것만으로는 모자랄듯. 생각외로 어려움.

# 지킬 나우 설치시 겪었던 문제점 및 주요점들

- [x] 설정을 바꾸다 적용되지 않으면, 저장소 설정/옵션/Github Pages에서 Build failed가 나오는지 확인할 것.** Your site is published at 주소** 가 나와야 함. 설정 파일은 yaml 파일이며, 이것에 따라 빌드하는 것으로 보임.
- [x] `id.github.io`를 이미 쓰고있어서 [프로젝트 페이지](https://help.github.com/articles/user-organization-and-project-pages/#project-pages)로 만드려는 경우, `_config.yml` 에서 baseurl 값을 넣어줘야 함.
- [x] 주소는 기본 설정대로라면 마크다운 문서 안에 있는 title: 값임. 제목도 그거.
- [x] disqus 추가도 `_config.yml`에서. shortname은 disqus 이름에 대시가 있는 경우 (둘 중 어떤건지 헷갈릴 수 있는데) 제거된 것임. (결국 깊이 찾아보면 나오긴 나오는데 성가심.)
- [x] about 페이지도 별도로 있으므로 수정해야 함.
