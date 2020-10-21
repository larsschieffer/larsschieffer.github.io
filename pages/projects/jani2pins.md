---
layout: default
permalink: /projects/jani2pins
---

<div style="position: relative; top: 45%; -webkit-transform: translateY(-45%); -ms-transform: translateY(-45%);transform: translateY(-45%);">
    <div id="adobe-dc-view" style="height:65vh; width: 90%; margin-left: auto; margin-right: auto;"></div>
    <script src="https://documentcloud.adobe.com/view-sdk/main.js"></script>
    <script type="text/javascript">
        document.addEventListener("adobe_dc_view_sdk.ready", function(){ 
            var adobeDCView = new AdobeDC.View({clientId: "7d941f79bb0743e38b0d8389c1ea0dc8", divId: "adobe-dc-view"});
            adobeDCView.previewFile({
                content:{location: {url: "/assets/slides/jani2pins.pdf"}},
                metaData:{fileName: "JANI2PINS - Presentation"}
            }, {embedMode: "SIZED_CONTAINER", dockPageControls: false, showDownloadPDF: false, 
                showPrintPDF: false});
        });
    </script>
    <div style="text-align: center">
        <span>
            <a href="https://dgit.cs.uni-saarland.de/s8lsschi/jani2pins" target="_blank">JANI2PINS</a>: The JANI front-end module for the LTSmin toolset
        </span>
    </div>
</div>