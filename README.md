# Manga API
Restful API Manga bahasa Indonesia built with ❤️ and node.js

# Usage
1. Clone this repository
    ```bash
    git clone https://github.com/febryardiansyah/manga-api.git
    ```
2. Install dependecies (`yarn` or `npm install`)
3. Start the development environment (*if you haven't installed nodemon globally, you can do `npm i nodemon --save`)
    ```bash
    npm run dev or npm run start
    ```
4. visit http://localhost:3000/api

# Documentation
__API__ __PATH__ = https://mangamint.glitch.me/api/
</br>__ApI__ Version = `v1.0`

## All Manga
Get Latest Manga Update
```
/manga/page/[pagenumber]
```
example : https://mangamint.glitch.me/api/manga/page/1

## Popular Manga
Get Popular Manga
```
/manga/popular/[pageNumber]
```
example : https://mangamint.glitch.me/api/manga/popular/1

## Detail Manga
```
/manga/detail/[endpoint]
```
example : https://mangamint.glitch.me/api/manga/detail/after-transformation-mine-and-her-wild-fantasy/

## Search Manga by Name
```
/cari/[query]
```
example : https://mangamint.glitch.me/api/cari/komi%20san

## Genre List
```
/genres
```
example : https://mangamint.glitch.me/api/genres

## Genre Detail
```
/genres/[endpoint]/[pagenumber]
```
example : https://mangamint.glitch.me/api/genres/action/1

## Recomended Manga
```
/recomended
```
example : https://mangamint.glitch.me/api/recomended

## Manhua List (Chinese Comic)
```
/manhua/[pageNumber]
```
example : https://mangamint.glitch.me/api/manhua/1

## Manhwa List (Korean Comic)
```
/manhwa/[pageNumber]
```
example : https://mangamint.glitch.me/api/manhua/1

## Chapter
```
/chapter/[chapterEndpoint]
```
example : https://mangamint.glitch.me/api/chapter/after-transformation-mine-and-her-wild-fantasy-chapter-70-bahasa-indonesia/
