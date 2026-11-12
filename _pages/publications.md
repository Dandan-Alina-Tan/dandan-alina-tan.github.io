---
layout: page
permalink: /publications/
title: Publications
description: Journal articles, preprints, and conference contributions.
nav: true
nav_order: 3
---

<style>
:root, html[data-theme="light"] { --global-theme-color:#163f76; --global-hover-color:#215b9e; --alina-heading:#163f76; --alina-soft:#f4f7fc; --alina-line:#dce5f1; }
html[data-theme="dark"] { --global-theme-color:#91b8ed; --global-hover-color:#b9d3f6; --alina-heading:#a6c8f6; --alina-soft:#172539; --alina-line:#344b68; }
h1,h2,h3 { color:var(--alina-heading); }
a { color:var(--global-theme-color); }
a:hover { color:var(--global-hover-color); }
.alina-section { clear:both; margin-top:2.5rem; }
.alina-section h2 { border-bottom:2px solid var(--alina-line); padding-bottom:.65rem; margin-bottom:1.3rem; font-weight:700; }
.alina-news { list-style:none; padding:0 1.2rem; border:1px solid var(--alina-line); border-radius:10px; background:var(--alina-soft); }
.alina-news li { padding:.85rem 0; border-bottom:1px solid var(--alina-line); line-height:1.65; }
.alina-news li:last-child { border-bottom:0; }
.alina-date { color:var(--global-theme-color); font-weight:700; white-space:nowrap; margin-right:.5rem; }
.alina-timeline { position:relative; margin:1.5rem 0 2rem; padding:.5rem 0; }
.alina-timeline:before { content:""; position:absolute; top:0; bottom:0; left:50%; width:3px; background:var(--alina-line); transform:translateX(-50%); }
.alina-entry { position:relative; width:50%; padding:0 2rem 2rem 0; text-align:right; box-sizing:border-box; }
.alina-entry:nth-child(odd) { margin-left:50%; padding:0 0 2rem 2rem; text-align:left; }
.alina-entry:after { content:""; position:absolute; right:-8px; top:10px; width:16px; height:16px; background:var(--global-bg-color,#fff); border:3px solid var(--global-theme-color); border-radius:50%; box-sizing:border-box; }
.alina-entry:nth-child(odd):after { left:-8px; right:auto; }
.alina-institution { display:inline-block; color:var(--alina-heading); font-weight:700; border:1px solid var(--alina-line); border-radius:7px; background:var(--alina-soft); padding:.35rem .6rem; margin-bottom:.4rem; }
.alina-period { display:block; color:var(--global-theme-color); font-size:.9rem; font-weight:600; margin-bottom:.65rem; }
.alina-entry p { margin:.25rem 0; font-size:.95rem; }
@media(max-width:640px) { .alina-timeline:before { left:8px; } .alina-entry,.alina-entry:nth-child(odd) { margin-left:0; width:100%; padding:0 0 1.8rem 2rem; text-align:left; } .alina-entry:after,.alina-entry:nth-child(odd):after { left:0; right:auto; } .alina-news { padding:0 .85rem; } }
#selected-heading, #selected-heading strong, .alina-selected h2, .alina-selected h2 strong { color:#163f76 !important; font-weight:700 !important; }
html[data-theme="dark"] #selected-heading, html[data-theme="dark"] #selected-heading strong { color:#a6c8f6 !important; }
.alina-news { max-height:22rem; overflow-y:auto; overscroll-behavior:contain; scrollbar-width:thin; scrollbar-color:#8da9ce transparent; }
.alina-news:focus-visible { outline:2px solid var(--global-theme-color); outline-offset:4px; }
.alina-news-icon { display:inline-block; font-size:1rem; margin-right:.4rem; }
.publications { width:100%; text-align:left; }
.publications ol.bibliography { list-style:none !important; margin:0 !important; padding:0 !important; }
.publications ol.bibliography > li { list-style:none !important; padding:1.2rem 0 !important; margin:0 !important; border-bottom:1px solid var(--alina-line); }
.publications ol.bibliography > li:last-child { border-bottom:0; }
.publications ol.bibliography > li::marker { content:""; }
.publications .row { display:block !important; margin:0 !important; }
.publications .abbr { display:none !important; }
.publications .col-sm-8 { display:block !important; flex:none !important; width:100% !important; max-width:100% !important; padding:0 !important; margin:0 !important; }
.publications .title { color:var(--alina-heading) !important; font-size:1.05rem; font-weight:700 !important; line-height:1.5; margin-bottom:.4rem; }
.publications .author, .publications .periodical { line-height:1.65; margin-bottom:.35rem; }
.publications .links { margin-top:.45rem; }
</style>


<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

{% bibliography %}

</div>
