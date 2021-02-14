+++
title = "Contact"
slug = "contact"
+++
<!-- markdownlint-disable -->
<form name="contact" method="POST" action="{{ .Site.Params.Contact.confirm_page }}" netlify>
    <div class="row gtr-50 gtr-uniform">
        <div class="col-6 col-12-mobilep">
            <input type="text" name="name" aria-label="Your name" placeholder="Your name">
        </div>
        <div class="col-6 col-12-mobilep">
            <input type="email" name="email" aria-label="Email address" placeholder = "Email address">
        </div>
        <div class="col-12">
            <textarea name="message" aria-label="Enter your message" placeholder="Enter your message" rows="6"></textarea>
        </div>
        <div class="col-12">
            <ul class="actions special">
                <li>
                    <input type="submit" value="Send" />
                </li>
            </ul>
        </div>
    </div>
</form>
