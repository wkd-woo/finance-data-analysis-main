# [๐ฑ ์ธํ๋ฐ - ์ฆ๊ถ ๋ฐ์ดํฐ ์์ง๊ณผ ๋ถ์์ผ๋ก ์ ํธ์ ์์ ์ฐพ๊ธฐ](https://bit.ly/inflearn-finace-data)

<a href="https://bit.ly/inflearn-finace-data"><img src="https://cdn.inflearn.com/public/files/courses/326383/86b666ed-064d-42fa-97d2-fb505ce5b735/Screen%20Shot%202021-03-29%20at%206.19.22%20PM.png" width="800"></a>


## ํ์ต ์คํฌ ์๊ฐ

```
๐ผ  Pandas : ํ์ด์ฌ์ ๋ํ์ ์ธ ๋ฐ์ดํฐ ๋ถ์ ๋๊ตฌ๋ก ๊ธ์ต ๋ฐ์ดํฐ ๋ถ์์ ์ํด ๋ง๋ค์ด ์ก์ต๋๋ค.
๐งฎ  Numpy : ํ์ด์ฌ์ ์์น๊ณ์ฐ ๋๊ตฌ ์๋๋ค.
๐  matplotlib : ํ์ด์ฌ์ ๋ํ์ ์ธ ๋ฐ์ดํฐ ์๊ฐํ ๋๊ตฌ ์๋๋ค.
๐  seaborn : matplotlib ์ ์ฌ์ฉํ๊ธฐ ์ฝ๊ฒ ์ถ์ํ ํด ๋์ ๊ณ ์์ค ์๊ฐํ ๋๊ตฌ๋ก ๊ธฐ๋ณธ ํต๊ณ ์ฐ์ฐ์ ์ ๊ณตํฉ๋๋ค.
๐  plotly : ๊ณ ์์ค, ์ ์์ค ์๊ฐํ ๊ธฐ๋ฅ์ ์ ๊ณตํ๋ฉฐ ์ธํฐ๋ํฐ๋ธํ ์๊ฐํ๊ฐ ๊ฐ๋ฅํฉ๋๋ค.
๐  cufflinks : plotly์ pandas๋ฅผ ๊ฐ๋ ฅํ๊ฒ ์ด์ด์ฃผ๋ ์์ฐ์ ์ธ ๋๊ตฌ ์๋๋ค.
๐  FinanceDataReader : ์ฝ๋ ํ ๋ ์ค๋ก ๊ธ์ต ๋ฐ์ดํฐ๋ฅผ ์์งํ  ์ ์๋ ๋๊ตฌ ์๋๋ค.
๐  Requests : ์น ํ์ด์ง์ ์์ค์ฝ๋๋ฅผ HTTP ํต์ ์ผ๋ก ๋ฐ์์ฌ ์ ์๋ ๋๊ตฌ ์๋๋ค.
๐  BeautifulSoup4 : ์น ํ์ด์ง์ ์์ค์ฝ๋์์ ์ํ๋ ์ ๋ณด๋ฅผ ๊ฐ์ ธ์ฌ ์ ์๋ ๋๊ตฌ ์๋๋ค.
โฐ  tqdm : ๋ฐ์ดํฐ ์์ง์ด๋ ์ ์ฒ๋ฆฌ์์ ์ค๋ ๊ฑธ๋ฆฌ๋ ์์์ ์งํ ์ํ๋ฅผ ๋ณผ ์ ์์ต๋๋ค.
```

## ๐ป  ์ฝ๋๊ฐ ์๋ ฅ๋์ง ์์ ํ์ผ(input)๊ณผ ์๋ ฅ๋ ํ์ผ(output) 2๊ฐ์ง ์ค์ต์๋ฃ๋ฅผ ์ ๊ณต

```
์ค๋ช์ด ์ ํ ๋น์ด์๋ ์์ ์ง์  ์ฝ๋๋ฅผ ์๋ ฅํ๋ฉฐ ํ ์ค ํ ์ค ๊ฐ์๋ฅผ ๋ฐ๋ผํด ๋ณผ ์๋ ์์ผ๋ฉฐ
์ฝ๋๊ฐ ์ ํ์๋ ํ์ผ์ ํตํด ์คํํ๋ฉฐ ์ค์ต์ ์งํํ  ์๋ ์์ต๋๋ค.
๊ฐ์๋ฅผ ๋ค ๋ฃ๊ณ  ๋น์ด ์๋ ์์ ์ฑ์ฐ๋ฉฐ ๋ณต์ตํด ๋ณผ ์๋ ์์ต๋๋ค.
```

<a href="https://bit.ly/inflearn-finace-data"><img src="https://cdn.inflearn.com/public/files/courses/326383/d6d08eae-949d-4a4d-a89b-7aafc7e10b53/Screen%20Shot%202021-02-13%20at%2010.25.55%20PM.png" width="800"></a>

## ๐ HTS, MTS ์์ ๋ณผ ์ ์๋ ๋ณด์กฐ์งํ(์ด๋ํ๊ท , ๋ณผ๋ฆฐ์ ๋ฐด๋, RSI, MACD) ์ง์  ๊ตฌํํ๊ณ  ์๋ฆฌ ์ดํดํ๊ธฐ

<a href="https://bit.ly/inflearn-finace-data"><img src="https://cdn.inflearn.com/public/files/courses/326383/c16c45a1-99c2-4070-9a6d-a188a0916c7b/Screen%20Shot%202021-04-03%20at%2012.13.26%20PM.png" width="800"></a>


### LICENSE
<a href="https://ko.wikipedia.org/wiki/%ED%81%AC%EB%A6%AC%EC%97%90%EC%9D%B4%ED%8B%B0%EB%B8%8C_%EC%BB%A4%EB%A8%BC%EC%A6%88_%EB%9D%BC%EC%9D%B4%EC%84%A0%EC%8A%A4"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/12/Cc-by-nc-sa_icon.svg/180px-Cc-by-nc-sa_icon.svg.png"></a>

Read more at [Creative Commons](https://ko.wikipedia.org/wiki/%ED%81%AC%EB%A6%AC%EC%97%90%EC%9D%B4%ED%8B%B0%EB%B8%8C_%EC%BB%A4%EB%A8%BC%EC%A6%88_%EB%9D%BC%EC%9D%B4%EC%84%A0%EC%8A%A4).
