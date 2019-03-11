---
layout: default
title: Home
---
<style>
.homeNav {
    border-bottom: 10px solid #938E94;
    margin: 0;
}
#skillsHr {
    width: 70%;
}
</style>
<div class="container-fluid">
    <div class="row mt-1">
        <div class="col mt-1">
            <div class="jumbotron jumbotron-fluid mx-auto mt-0 mt-md-2 jumbotron-main">
                <div class="container text-center">
                    <div class="row">
                        <div class="col-md-6 col-12 my-md-auto mb-4">
                            <h1 class="display-4 my-0 my-md-2">Dennis Marrero<span id="blink">|</span></h1>
                        </div>
                        <div class="col-md-6 col-12 m-auto animated fadeIn delay-1s slow">
                            <img src="\assets\images\me.jpg" class="img-thumbnail rounded-pill img-responsive mx-auto self" alt="...">
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div class="row pb-10">
        <div class="col-md-8 col-12 m-auto">
            <p class="text-center mb-8 p-2 p-md-1 firstP animated fadeIn delay-2s">
                Hey there, I'm Dennis, a front end designer & developer. I'm passionate about learning new technologies and methods to curate various web apps and am always yearning for continuous improvement on my skills to further build and perfect my current knowledge set.
            </p>
        </div>
    </div>
    <div data-aos="fade-down" class="row mt-2 mt-md-10 mb-8 skills">
        <div class="col-md-6 col-12">
            <h3 class="text-center">Skills</h3>
            <hr id="skillsHr">
                <div class="row justify-content-center">
                    <div class="col-md-9 col-12 text-center">
                        <ul class="skills p-0">
                            <li>Web Development</li>
                            <li>Responsive Web Design</li>
                            <li>Microsoft Office 365</li>
                            <li>G Suite</li>
                            <li>Video/Image Editing</li>
                        </ul>
                    </div>
                </div>
        </div>
        <div class="col-md-6 col-12">
            <h3 class="text-center">Technologies</h3>
            <hr id="skillsHr">
                <div class="row justify-content-center">
                    <div class="col-md-9 col-12 text-center">
                        <ul class="skills p-0">
                            <li>HTML/5</li>
                            <li>CSS/3</li>
                            <li>SASS</li>
                            <li>Bootstrap</li>
                            <li>Jekyll</li>
                            <li>Javascript</li>
                            <li>Markdown</li>
                        </ul>
                    </div>
                </div>
        </div>
    </div>
</div>
<script>
AOS.init();
window.onbeforeunload = function () {
window.scrollTo(0, 0);
}
</script>