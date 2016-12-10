---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: page
---

<div class="banner">
    <ul>
        <li>
            <img class="img-responsive" src="{{ site.BASE_PATH }}/assets/images/banner_1.jpg" />
        </li>
        <li>
            <img class="img-responsive" src="{{ site.BASE_PATH }}/assets/images/banner_2.jpg" />
        </li>
        <li>
            <img class="img-responsive" src="{{ site.BASE_PATH }}/assets/images/banner_3.jpg" />
        </li>
    </ul>
</div>

<script type="text/javascript" src="{{ site.BASE_PATH }}/assets/js/jquery-2.1.1.min.js"></script>
<script type="text/javascript" src="{{ site.BASE_PATH }}/assets/unslider/js/unslider-min.js"></script>
<script>
    jQuery(document).ready(function($) {
        $('.banner').unslider({
            autoplay: true,
            arrows: false,
        });
    });
</script>