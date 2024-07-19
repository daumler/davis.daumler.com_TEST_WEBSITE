---
title: ''
date: ''
---

<div id="adobe-dc-view" style="width: 800px;"></div>
<script src="https://documentcloud.adobe.com/view-sdk/main.js"></script>
<script type="text/javascript">
const ADOBE_KEY = 'b9151e8d6a0b4d798e0f8d7950efea91';

if(window.AdobeDC) displayPDF();
else {
  document.addEventListener("adobe_dc_view_sdk.ready", () => displayPDF());
}

function displayPDF() {
  console.log('Lets do some AWESOME PDF stuff!');
  let adobeDCView = new AdobeDC.View({clientId: ADOBE_KEY, divId: "mypdf" });
  adobeDCView.previewFile({
    content:{location: {url: "https://static.raymondcamden.com/enclosures/cat.pdf"}},
    metaData:{fileName: "cat.pdf"}
  }); 
}
</script>


```
<script src="https://documentcloud.adobe.com/view-sdk/main.js"></script>
```


```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE-edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Embed PDFs in HTML</title>
  <style>
    #myPDF {
      width: 85%;
      height: 975px;
    }
  </style>
</head>
<body>
  <iframe id="myPDF" src="/uploads/Daumler_CV.pdf" frameborder="0"></iframe>
</body>
</html>
```



```
<div id="adobe-dc-view" style="width: 800px;"></div>
<script src="https://acrobatservices.adobe.com/view-sdk/viewer.js"></script>
<script type="text/javascript">
	document.addEventListener("adobe_dc_view_sdk.ready", function(){ 
		var adobeDCView = new AdobeDC.View({clientId: "d2c6801fe11f44ec9d5e7b2635025433", divId: "adobe-dc-view"});
		adobeDCView.previewFile({
			content:{location: {url: "https://acrobatservices.adobe.com/view-sdk-demo/PDFs/Bodea Brochure.pdf"}},
			metaData:{fileName: "Bodea Brochure.pdf"}
		}, {embedMode: "IN_LINE"});
	});
</script>
```
