# SHSP-Native-Form-Endpoint-TY-Page

Script to redirect to a desired Thank You Page when posting directly to a SHSP native form endpoint via the action="" of an HTML form.

<h3>The problem:</h3>
<p>When submitting to a SHSP native form endpoint via the action of an HTML form, the user will be redirected to the response of the POST, which is a "success" JSON page.</p>

<h3>The solution:</h3>
<p>Add a script and an iFrame to the page and have the html form target the iFrame. This way, we can hide the success JSON page within the "display: none;" iFrame and redirect to the desired thank you page via our script.</p>
