---
layout: single
title: "Resume"
permalink: /resume/
---

## My Resume

<iframe 
    id="resumeFrame" 
    src="/assets/resume.html" 
    style="width:100%; border: none; overflow: hidden;" 
    scrolling="no">
</iframe>

<script>
    function resizeIframe() {
        const iframe = document.getElementById('resumeFrame');
        if (iframe.contentWindow.document.body) {
            iframe.style.height = iframe.contentWindow.document.body.scrollHeight + 'px';
            iframe.style.width = iframe.contentWindow.document.body.scrollWidth + 'px';
        }
    }

    document.getElementById('resumeFrame').onload = resizeIframe;
    window.onresize = resizeIframe;
</script>

## Download My Resume

You can download my resume in PDF format by clicking the link below:

[Download Resume (PDF)](/assets/resume.pdf)
