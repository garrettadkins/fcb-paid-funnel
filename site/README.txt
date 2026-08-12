First Community Bank - paid traffic funnel (static site)

Deploy: drag this folder into Netlify (or connect it as the publish directory).

Pages
  index.html       Landing page (no nav; account CTAs link to the form)
  form.html        Lead form. Reads ?account=... from the landing CTAs and
                   redirects to thank-you.html on submit.
  thank-you.html   Confirmation + prep checklist.

Form submissions
  The form currently only redirects (no backend). For Netlify Forms, add
  netlify and data-netlify="true" to the <form id="lead-form"> tag and set
  action="/thank-you.html", then remove the submit handler script at the
  bottom of form.html.

Imagery
  Gray blocks with class="media-slot" mark where photos/video go. Replace each
  with an <img src="assets/your-photo.jpg" style="width:100%;height:100%;object-fit:cover">.

Assets
  assets/fcb-logo.png, fcb-logo-white.png (reverse), mark-big-*.png (logomark mattes).
