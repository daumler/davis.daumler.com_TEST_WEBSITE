---
title: ''
date: ''
# type: landing
---
<script src="https://acrobatservices.adobe.com/view-sdk/viewer.js"></script>
<script type="text/javascript">
	document.addEventListener("adobe_dc_view_sdk.ready", function(){ 
		var adobeDCView = new AdobeDC.View({clientId: "d2c6801fe11f44ec9d5e7b2635025433"});
		adobeDCView.previewFile({
			content:{location: {url: "https://acrobatservices.adobe.com/view-sdk-demo/PDFs/Summary.pdf"}},
			metaData:{fileName: "Summary.pdf"}
		}, {embedMode: "LIGHT_BOX", exitPDFViewerType: "RETURN"});
	});
</script>


