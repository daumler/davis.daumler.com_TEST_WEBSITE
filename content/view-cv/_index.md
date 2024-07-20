---
title: ''
date: ''
---
<!---NOTE: This site uses GoatCounter, an open-source, not-for-profit web analytics platform that does not track personal data or use any cookies. GoatCounter is a donation-supported and privacy-friendly alternative to Google Analytics or Matomo, intended for noncommercial or small-business websites. More information on the philosophy and mechanics of GoatCounter can be found here (<< https://www.goatcounter.com/why >>), and an open-source repository for the platform can be found here (<< https://github.com/arp242/goatcounter >>). --->

{{< cta cta_text="DOWNLOAD CV" cta_link="/CV/" cta_new_tab="true" >}}

<html>
<head>
  <meta http-equiv="X-UA-Compatible" content="IE-edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    #myPDF {
      width: 100%;
      height: 100vh;
    }
    div {text-align: center;}
  </style>
</head>
<body>
  <iframe id="myPDF" src="/uploads/Daumler_CV.pdf#toolbar=0&navpanes=0" frameborder="0"></iframe>
</body>
</html>


<html>
<body>
<script type="text/javascript" src="scripts/pdfobject.js"></script>
<div id="pdf1" style="width:500px; height:375px;"></div>
<script type='text/javascript'>
var myPDF = new PDFObject({ 
     url: '/uploads/Daumler_CV.pdf', 
     pdfOpenParams: { 
          view: 'Fit', 
          scrollbars: '0', 
          toolbar: '0', 
          statusbar: '0', 
          navpanes: '0' }
      }).embed('pdf1'); 
</script>
</body>
</html>
