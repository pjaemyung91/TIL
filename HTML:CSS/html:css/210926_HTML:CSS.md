210926 HTML/CSS

1. 문제

![문제](210926_HTML:CSS.assets/210926_html_css.jpg)

2. 코드구현

```html
<!DOCTYPE html>
<html>
<meta charset="UTF-8">
<title>Insert title here</title>
<style>
    #comp_name {
        position: relative;
    }

    #comp_name > h2{
        margin-bottom: 10px;
    }

    #icon {
        position: absolute;
        top: 10px;
        right: 0px;
    }

    #comp_info{
        position: absolute;
    }
</style>

<head>

<body>
    <footer>
        <div id="comp_name">
            <div id="icon">
                <img src='sns_youtube_icon.png'>
                <img src='sns_facebook_icon.png'>
                <img src='sns_naver_icon.png'>
                <img src='sns_insta_icon.png'>
            </div>
            <h2>동아제약</h2>
            <div id="comp_info">
                <span>
                    서울특별시 동대문구 천호대로64<br>
                    Copyright 2017 garglin.co.kr All Right Reserved / Design by THEJIN
                </span>
            </div>
        </div>
    </footer>
</body>
</head>

</html>
```

3. 풀이
   - div는 position 속성을 통해 겹칠 수 있다.
   - 부모 div의 position을 relative로 자식 div의 속성을 absolute로 하면 두 개의 div가 겹쳐진다.