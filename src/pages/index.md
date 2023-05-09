---
layout: ../layouts/default.astro
---

<div class="jumbotron center">
<img src="/logo.png" height="220" class="logo">
<h1 class="display-4 lead">Hello!</h1>

<p class="lead">Cutebox is a new take on social networking using the ActivityPub protocol and a custom user interface to make the fediverse fun, efficient and easy to use again.</p>

<br><br>

<p><a href="/deploy" class="btn btn-primary">Deploy now</a> <a href="https://web.cutebox.cc" class="btn btn-secondary">Join the main instance</a></p>

</div>

<style>
    .btn {
        margin-right: 20px;
    }
    @media(max-width:800px) {
        .btn {
            display: block;
            margin: 0 auto;
            margin-bottom: 20px;
        }
    }
</style>