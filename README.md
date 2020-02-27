# GA parameter setting GUIDE

## 공통코드 삽입
모든 페이지의 ```<head>``` 에서 가능한 한 높은 위치에 코드를 붙여넣으세요. ( 공통영역으로 정의하여 모든 페이지에 삽입되도록 합니다. )
```
<!-- Google Tag Manager -->
<script>
  dataLayer = [];
</script>

<script>(function(w,d,s,l,i){w[l]=w[l]||[];w[l].push({'gtm.start':
new Date().getTime(),event:'gtm.js'});var f=d.getElementsByTagName(s)[0],
j=d.createElement(s),dl=l!='dataLayer'?'&l='+l:'';j.async=true;j.src=
'https://www.googletagmanager.com/gtm.js?id='+i+dl;f.parentNode.insertBefore(j,f);
})(window,document,'script','dataLayer','GTM-WJHQG7X');</script>
<!-- End Google Tag Manager -->
```
## 추가 태그 삽입.
```
<!-- Google Tag Manager (noscript) -->
<noscript><iframe src="https://www.googletagmanager.com/ns.html?id=GTM-WJHQG7X"
height="0" width="0" style="display:none;visibility:hidden"></iframe></noscript>
<!-- End Google Tag Manager (noscript) -->
```

