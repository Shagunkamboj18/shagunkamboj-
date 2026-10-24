<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Strategy Notes</title>
<style>
:root{--bg:#f4f7ef;--fg:#0f2a1c;--muted:#4c6354;--accent:#0b7a3b;--rule:#d0dcc8;--panel:#e4eed8;--pop:#b6f23a;--hero:#0d3b27}
@media (prefers-color-scheme:dark){:root{--bg:#0e1a14;--fg:#e8f1e4;--muted:#9db3a4;--accent:#6fe39a;--rule:#25382d;--panel:#172a20;--hero:#123a27}}
*{box-sizing:border-box}
body{margin:0;background:var(--bg);color:var(--fg);font:18px/1.7 Georgia,"Times New Roman",serif}
main{max-width:680px;margin:0 auto;padding:40px 22px 72px}
header.site{display:flex;justify-content:space-between;align-items:baseline;flex-wrap:wrap;gap:6px 14px;padding:20px 24px;background:var(--hero);border-radius:16px;margin-bottom:36px;font-family:"Helvetica Neue",Arial,sans-serif}
header.site a{color:var(--pop);text-decoration:none;font-weight:900;font-size:1.6rem;letter-spacing:-.02em}
header.site span{color:#d9ead9;font-size:.9rem}
h1{font:900 clamp(2.2rem,8vw,3.6rem)/1.05 "Helvetica Neue",Arial,sans-serif;letter-spacing:-.03em;margin:0 0 14px}
h2{font:800 1.4rem/1.25 "Helvetica Neue",Arial,sans-serif;margin:2.2em 0 .6em;padding-left:14px;border-left:8px solid var(--pop)}
.lede{font-size:1.2rem;color:var(--muted);margin:0 0 24px}
.meta{font:.9rem "Helvetica Neue",Arial,sans-serif;color:var(--muted)}
p{margin:0 0 1.1em}
ul,ol{padding-left:1.2em;margin:0 0 1.2em}
li{margin-bottom:.5em}
a{color:var(--accent)}
.item{display:block;padding:20px 22px;margin-bottom:16px;background:var(--panel);border-left:10px solid var(--pop);border-radius:14px;text-decoration:none;color:var(--fg)}
.item h3{font:700 1.4rem/1.25 "Helvetica Neue",Arial,sans-serif;margin:4px 0 8px}
.item:hover h3{color:var(--accent)}
.item p{margin:0;color:var(--muted);font-size:1rem}
.back{display:inline-block;margin-bottom:24px;font:.95rem "Helvetica Neue",Arial,sans-serif}
.take{background:var(--panel);border-radius:6px;padding:16px 20px;margin:1.6em 0}
.scroll{overflow-x:auto}
table{border-collapse:collapse;width:100%;font:.95rem/1.5 "Helvetica Neue",Arial,sans-serif}
th,td{text-align:left;padding:10px 12px;border-bottom:1px solid var(--rule);vertical-align:top}
th{color:var(--muted);font-weight:600}
footer{margin-top:3em;padding-top:18px;border-top:1px solid var(--rule);font:.85rem "Helvetica Neue",Arial,sans-serif;color:var(--muted)}
</style>
</head>
<body>
<main>
<header class="site"><a href="#home">Strategy Notes</a><span>Business case studies &amp; analysis</span></header>
<div id="view"></div>
<footer>© <span id="yr"></span> Strategy Notes</footer>
</main>
<script>
var POSTS=[
{
id:"netflix-vs-disney",
title:"Can Netflix stay ahead of Disney?",
date:"24 October 2026",
summary:"Disney has more cash and a cheaper bundle. Netflix still holds the better position, if it plays it right.",
body:`
<h2>The short answer</h2>
<p>Yes,
