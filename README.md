# Nomflix

NomadCoder Lecture Learning React and ES6 by building a Movie Discovery App. 

## Summary

  - [Example](#example)
  - [How it Works](#how-it-works)
  - [Getting Started](#getting-started)
  - [Installing & Starting](#installing--starting)
  - [Deployment](#deployment)
  - [Built With](#built-with)
  - [Authors](#authors)
  - [License](#license)

## Example

> Movie List 

![Movies](https://user-images.githubusercontent.com/37660333/103149560-ef9ead00-47ad-11eb-819b-96d046b80400.png)

> TV List

![TV](https://user-images.githubusercontent.com/37660333/103149675-f4b02c00-47ae-11eb-9fca-4b9f95242eb3.png)

> Search

<img src="https://user-images.githubusercontent.com/37660333/103149963-2676c200-47b2-11eb-9eaf-0db22da9ede1.gif" width="100%" />

> Detail

<img src="https://user-images.githubusercontent.com/37660333/103150017-efed7700-47b2-11eb-8e4d-da0830e2c2cd.gif" width="100%"/>
</br>

## How it Works

### 영화 & TV 프로그램 로딩

>1. 영화 혹은 TV 페이지 접근 시 해당 페이지의 Data Logic Component에서 axios를 통해 'TMDB'에서 제공하는 API에 최신, 상영 혹은 방영 예정, 인기 영화 혹은 TV 프로그램 데이터 요청
>2. Response로 나온 결과값 안에 각 영화 정보를 각각 Poster Component에 Mapping 시킨 후 화면에 출력

<br>

### 영화 & TV 프로그램 작품 검색

>1. 페이지 내부의 검색바를 통해 검색 값(Search Term) 제출
>2. 해당 페이지의 Data Logic Component에서 axios를 통해 'TMDB'에서 제공하는 API에 검색 값을 바탕으로 영화 혹은 TV 프로그램 작품 검색 결과 데이터 요청
>3. Response로 나온 결과값 안에 각 영화 정보를 각각 Poster Component에 Mapping 시킨 후 화면에 출력

<br>

### 영화 & TV 프로그램 상세 페이지

>1. 영화 리스트, TV 프로그램 리스트 와 검색결과 페이지의 포스터를 클릭하면 상세 페이지로 이동
>2. 페이지 접근 시 해당 페이지의 Data Logic Component에서 axios를 통해 'TMDB'에서 제공하는 API에 해당 작품의 상세 정보 요청
>3. Response로 나온 결과값 안에 모든 정보를 각각의 형태에 맞춰 Component에 Mapping 시킨 후 화면에 출력

<br>

## Getting Started

이 지침을 따르시면 로컬 PC에서 개발과 테스트를 위한 해당 프로젝트의 사본을 실행, 설치, 배포시킬 수 있습니다.

### Prerequisites

프로젝트를 실행시키기 위해 다음 프로그램들이 필요합니다.

```
- NPM (https://nodejs.org/en)
- Git (https://git-scm.com)
```

## Installing & Starting



해당 프로젝트의 사본을 설치 및 실행하기 위해 다음 단계들을 거쳐야 합니다.

- git을 통해 로컬에 프로젝트 Clone 하기

  > 'https://github.com/gangslee/nomflix.git' 를 통해 사용자의 로컬 PC로 프로젝트를 Clone 합니다.

* Window의 경우 Git Bash 등을 통해 입력합니다.
* Linux, MacOS 등등에서는 Terminal을 통해 입력합니다.
* GitHub Desktop을 통해서도 Clone이 가능합니다.

- 로컬 프로젝트의 NPM Update 하기

  > 로컬 프로젝트가 설치 된 위치에서 다음 명령어를 통해 앞서 설치한 NPM 패키지들을 Update 합니다.

  ```
  npm update
  ```

- 프로젝트 실행하기
  > 로컬 프로젝트가 설치 된 위치에서 다음 명령어를 통해 프로젝트를 실행합니다.
  ```
  npm start
  ```

## Deployment



> 로컬 프로젝트가 설치 된 위치에서 다음 명령어를 통해 프로젝트를 build 합니다.

```
npm run build
```

- 생성된 build 산출물들을 웹 서버의 root directory에 복사 후 서버를 재실행 시켜야 합니다.

## Built With

- [ReacttJS](https://ko.reactjs.org/) - 웹 프레임워크
- [TMDB](https://www.themoviedb.org/) - 영화 & TV 프로그램 API 제공

## Authors

- **이경수(grandnet1225@gmail.com)** - [gangselee](https://github.com/gangslee)

## License

[![License](https://img.shields.io/badge/license-mit-blue)](http://badges.mit-license.org)

- Licensed under the [MIT License](LICENSE)