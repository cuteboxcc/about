---
layout: ../layouts/default.astro
---

# Features

cutebox is a soft-fork of GoToSocial that aims to make it easy for everyone to host a small fediverse instance at home. It comes with its own web interface, is well documented and takes care of things that can go wrong. We even offer a free subdomain service for people who can't afford a domain. A simple run-and-use web-based management console is planned along with an image for the Raspberry Pi. We want to make the fediverse community-owned and accessible again and are opposed to corperate-like structures like Mastodon.

## Mastodon API compatibility

The Mastodon API has become the de facto standard for client communication with federated servers, so cutebox has implemented and extended the API with custom functionality. This also means you'd feel right at home with most Mastodon apps working great with cutebox. If you're tech savy you can even write your own scripts to automate cutebox.

## Granular post settings

It's important that when you post something, you can choose who sees it.

cutebox offers public, unlisted and direct posts.

## Customizability

Plenty of config options to play around with, including:

* Easily adjustable post length.
* Media upload size settings.
* Custom CSS for public pages

## Easy to run

No external dependencies. Simply install [using the documentation](/deploy) and run.

cutebox plays nice with lower-powered machines like Raspberry Pi, old laptops and tiny $5/month VPSes.

The user interface is hosted on Netlify and media is cached using Cloudflare to ensure a smooth experience, even if your home internet is slow.

## Safety + security features

* Built-in, automatic support for secure HTTPS with caddy
* Strict privacy enforcement for posts and strict blocking logic.
* Import and export allow lists and deny lists. Subscribe to community-created block lists (think Ad blocker, but for federation!).
* HTTP signature authentication: cutebox requires HTTP Signatures when sending and receiving messages, to ensure that your messages can't be tampered with and your identity can't be forged.

## Various federation modes

cutebox doesn't apply a one-size-fits-all approach to federation. Who your server federates with should be up to you.

<br>

* 'Normal' federation; discover new servers.
* Allow list-only federation; choose which servers you talk to.
* Zero federation; keep your server private.

## OIDC integration

cutebox supports OpenID Connect (OIDC) identity providers, meaning you can integrate it with existing user management services like Auth0, Gitlab, etc., or run your own and hook cutebox up to that (we recommend Dex).

# Wishlist

These cool things will be implemented if time allows (because we really want them):

<br>

* Groups and group posting!
* Reputation-based 'slow' federation.
* Community decision-making for federation and moderation actions.
* User-selectable custom templates for rendering public posts:
  * Twitter-style
  * Blogpost
  * Gallery
  * Etc.
* Easy setup using a dedicated web interface
* Raspberry Pi images

Most of these points are taken from GoToSocial. Please help them out so the cutebox backend gets better.