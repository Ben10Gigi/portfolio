---
layout: default
title: Contact
permalink: /contact/
---
<style>
.contactNav {
    border-bottom: 10px solid #938E94;
    margin: 0;
}
#skillsHr {
    width: 70%;
}
</style>
<div class="container-fluid">
    <div class="row min-vh-100 justify-content-center">
        <div class="col-12 col-md-6">
        <h1 class="pb-3 text-center">Contact Me</h1>
        <hr id="skillsHr">
            <form class="mx-md-10 text-center firstP p-2 mt-5" action="https://usebasin.com/f/f11010cf2d37" method="POST">
                <div class="form-group">
                    <label for="email" class="w-100 text-center formLabels">Email address</label>
                    <input type="email" name="email" class="form-control" id="email" placeholder="name@website.com">
                </div>
                <div class="form-group">
                    <label for="textarea" class="w-100 text-center formLabels">Message</label>
                    <textarea style="resize: none" name="comment" class="form-control" id="textarea" rows="5"></textarea>
                </div>
                <button type="submit" class="btn btn-outline-dark">Submit</button>
            </form>
        </div>
    </div>
</div>