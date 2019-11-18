▪️워크샵은 아래와 같은 목표로 합니다
---
* 간단하게 R을 활용해 고위공직자 재산 데이터를 분석해본다
* `tidyverse`를 이용해서 `select`, `filter`, `mutate`, `group_by`, `summarise`로 기본적인 통계분석을 배워본다
* 차트를 이용해 분석한 결과를 시각화해본다

▪️설치를 해봅시다
---
* R설치
	* [설치파일 다운로드](https://cran.seoul.go.kr/)
	* 운영체제에 맞는 설치파일을 다운로드(Windows or Mac)
	* 최신버전은 R 3.6.1 (2019.11.19 기준)

* RStudio설치
	* R을 설치한 뒤에 RStudio Desktop을 설치
	* [Rstuido 설치파일 다운로드](https://rstudio.com/products/rstudio/download/)
	* 운영체제에 맞는 설치파일을 다운로드(Windows or Mac)
	* 최신버전은 rstudio-1.2.5019 (2019.11.19 기준)

* R과 RStudio 모두 설치했다면 준비 끝. RStudio를 실행시키자! 
 * R을 실행해도 되지만 RStudio는 R언어를 더욱 효과적으로 사용하기 위한 IDE입니다
 * RStuido를 사용하는 이유는 기사를 메모장에 써도 되지만 word 혹은 한글 프로그램을 쓰는 것과 같은 목적입니다

* `tidyverse` 패키지 설치
```r
install.packages("tidyverse", dependency = TRUE)
```
  
▪️R은 이렇게 작동해요
---
* 코드는 Windows의 경우 `ctrl`+`Enter`이며 Mac의 경우 `command`+`return`으로 실행
* 변수는 `<-`로 할당한다
```r
df.cat <- "cat"
df.dog <- "dog"
```

▪️오늘 배우는 문법을 자세히 알고 싶다면?!
---
* Installers:
  * Install packages with their dependencies.
  * Install from GitHub, GitLab, Bitbucket.

📬궁금한 게 생기면 아래로 연락주세요
---
woons@sbs.co.kr (배여운)
