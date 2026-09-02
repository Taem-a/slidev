---
theme: bricks
title: misc?
author: taem
aspectRatio: 16/9
transition: fade
mdc: true
layout: cover
class: cover-page
---

<div class="cover-tag">CTF · MISCELLANEOUS</div>

# misc?

<div class="cover-line"></div>

<style>
:global(html .slidev-layout) { background:#000!important; }
.cover-page { position:relative; display:flex; flex-direction:column; justify-content:center; padding:52px 66px; background:#10251d!important; color:#fff!important; overflow:hidden; font-family:Inter,"PingFang SC","Microsoft YaHei",sans-serif; }
.cover-page::after { content:""; position:absolute; right:-100px; top:-120px; width:400px; height:400px; border:60px solid rgba(255,255,255,.06); transform:rotate(18deg); }
.cover-tag { color:#ff8568; font-size:11px; font-weight:800; letter-spacing:3px; }
.cover-page h1 { margin:18px 0; color:#fff; font-size:78px; line-height:1; font-weight:800; letter-spacing:-5px; }
.cover-line { width:66px; height:5px; background:#ff6844; }
.cover-subtitle { color:rgba(255,255,255,.68); font-size:17px; letter-spacing:2px; }
</style>

---
layout: default
class: content-page intro-page
---

<div class="page-label">01 · INTRO</div>

# Misc是什么？有什么特点？
<div class="en-title">Miscellaneous</div>

<div class="intro-layout">
  <div class="intro-copy">
    <p class="key-text">Misc，也就是<strong>安全杂项</strong></p>
    <p>在 CTF 中，不能归类到其他方向的题目，都属于 Misc 的范畴</p>
  </div>
  <div class="point-list">
    <div><b>01</b><span>内容种类多，范围广</span></div>
    <div><b>02</b><span>对前置基础要求较低，学习曲线平缓</span></div>
    <div><b>03</b><span>知识点有趣（吗</span></div>
  </div>
</div>

<div class="callout">接下来，让我们一起走进 Misc 的世界 →</div>

<style>
.intro-page { position:relative; padding:52px 66px; background:#0d1210!important; color:#f1f4f1!important; font-family:Inter,"PingFang SC","Microsoft YaHei",sans-serif; }
.intro-page::after { content:""; position:absolute; left:66px; right:66px; bottom:27px; height:1px; background:#2b3630; }
.intro-page h1 { margin:0; color:#f1f4f1; font-size:42px; line-height:1.08; font-weight:800; letter-spacing:-1.5px; }
.page-label { position:absolute; top:35px; right:66px; color:#718078; font-size:10px; font-weight:700; letter-spacing:2px; }
.en-title { margin-top:5px; color:#829087; font-size:14px; letter-spacing:1.2px; }
.intro-layout { display:grid; grid-template-columns:1fr 1fr; gap:48px; align-items:center; margin-top:35px; }
.intro-copy { padding-right:20px; }.intro-copy p{line-height:1.7}.key-text{font-size:21px;line-height:1.6!important}.key-text strong{color:#ff6844}
.point-list { display:grid; gap:10px; }.point-list>div{display:flex;align-items:center;gap:17px;padding:14px 17px;background:#171e1a;border:1px solid #2b3630;border-left:4px solid #3b8b6b;box-shadow:0 8px 22px rgba(0,0,0,.16)}.point-list b{color:#ff6844;font-size:10px}
.callout { margin-top:25px; padding:13px 17px; background:#192820; border:1px solid #294438; color:#b9d9c9; font-weight:700; font-size:13px; }
</style>

---
layout: default
class: content-page topics-page
---

<div class="page-label">02 · OVERVIEW</div>

# Misc 包含什么？

<div class="topics-grid">
  <div><b>01</b><span>编码</span></div>
  <div><b>02</b><span>隐写</span></div>
  <div><b>03</b><span>压缩包</span></div>
  <div><b>04</b><span>OSINT</span></div>
  <div><b>05</b><span>流量 / 内存 / 磁盘取证</span></div>
  <div><b>06</b><span>应急响应</span></div>
  <div><b>07</b><span>区块链</span></div>
  <div><b>08</b><span>AI安全</span></div>
  <div class="more"><b>more</b><span>....</span></div>
</div>

<style>
.topics-page { position:relative; padding:52px 66px; background:#0d1210!important; color:#f1f4f1!important; font-family:Inter,"PingFang SC","Microsoft YaHei",sans-serif; }
.topics-page::after{content:"";position:absolute;left:66px;right:66px;bottom:27px;height:1px;background:#2b3630}.topics-page h1{margin:0;color:#f1f4f1;font-size:42px;line-height:1.08;font-weight:800;letter-spacing:-1.5px}.page-label{position:absolute;top:35px;right:66px;color:#718078;font-size:10px;font-weight:700;letter-spacing:2px}
.topics-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:11px;margin-top:31px}.topics-grid>div{min-height:72px;display:flex;align-items:center;gap:15px;padding:12px 17px;background:#171e1a;border:1px solid #2b3630;box-shadow:0 6px 18px rgba(0,0,0,.12)}.topics-grid b{color:#ff6844;font-size:10px}.topics-grid span{font-size:16px;font-weight:700}.topics-grid .more{background:#18392d;color:#fff;border-color:#315b49}
</style>

---
layout: default
class: content-page encoding-page
---

<div class="page-label">03 · ENCODE & DECODE</div>

# 编码
<div class="en-title">encode&decode</div>

<div class="text-layout">
  <div>
    <p class="key-text">编码把原始信息转换为另一种形式，经常用于数据的<strong>传输和储存</strong></p>
    <p>在 Misc 中，我们会遇到不同形式的编码</p>
  </div>
  <div class="info-card">
    <p>从最简单的 ASCII、base64 到神秘的文字、看似杂乱无章的字符，都可能是一种编码</p>
    <div class="mini-flow"><span>识别</span><i>→</i><span>搜索</span><i>→</i><span>解码</span></div>
  </div>
</div>

<div class="bottom-copy">我们就要在已有知识的基础上，在网上搜索相关信息来解出编码中的信息</div>

<!-- 比如计算机的底层使用2进制编码，而网页的数据传输通常使用base64编码 -->

<style>
.encoding-page{position:relative;padding:52px 66px;background:#0d1210!important;color:#f1f4f1!important;font-family:Inter,"PingFang SC","Microsoft YaHei",sans-serif}.encoding-page::after{content:"";position:absolute;left:66px;right:66px;bottom:27px;height:1px;background:#2b3630}.encoding-page h1{margin:0;color:#f1f4f1;font-size:42px;line-height:1.08;font-weight:800;letter-spacing:-1.5px}.page-label{position:absolute;top:35px;right:66px;color:#718078;font-size:10px;font-weight:700;letter-spacing:2px}.en-title{margin-top:5px;color:#829087;font-size:14px;letter-spacing:1.2px}
.text-layout{display:grid;grid-template-columns:1fr 1fr;gap:48px;align-items:center;margin-top:35px}.text-layout p{line-height:1.7}.key-text{font-size:21px;line-height:1.6!important}.key-text strong{color:#ff6844}.info-card{padding:24px;background:#163328;color:#fff;border:1px solid #28513f;box-shadow:12px 12px 0 #111814}.info-card p{margin-top:0;color:rgba(255,255,255,.78)}.mini-flow{display:flex;align-items:center;justify-content:space-between;margin-top:20px}.mini-flow span{padding:7px 12px;background:rgba(255,255,255,.1);font-size:12px}.mini-flow i{color:#ff8467;font-style:normal}.bottom-copy{margin-top:25px;padding:13px 17px;background:#192820;border:1px solid #294438;color:#b9d9c9;font-weight:700;font-size:13px}
</style>

---
layout: default
class: content-page steganography-page
---

<div class="page-label">04 · STEGANOGRAPHY</div>

# 隐写
<div class="en-title">Steganography</div>

<div class="text-layout">
  <div>
    <p class="key-text">隐写是一种将<strong>秘密信息</strong>隐藏在其他载体中的技术</p>
    <p>这个载体可以是图片，视频，甚至是一段普通的文本</p>
    <p>计算机中的文件以二进制形式存储，因此信息可以通过不同方式隐藏在文件数据之中。</p>
  </div>
  <div class="carrier-card">
    <div class="card-title">常见隐写载体包括</div>
    <div class="carrier-grid"><span>图片隐写</span><span>音频隐写</span><span>视频隐写</span><span>文档隐写</span></div>
  </div>
</div>

<div class="bottom-copy">隐写包含的内容很多，且层出不穷，要结合题目持续学习和实践</div>

<style>
.steganography-page{position:relative;padding:52px 66px;background:#0d1210!important;color:#f1f4f1!important;font-family:Inter,"PingFang SC","Microsoft YaHei",sans-serif}.steganography-page::after{content:"";position:absolute;left:66px;right:66px;bottom:27px;height:1px;background:#2b3630}.steganography-page h1{margin:0;color:#f1f4f1;font-size:42px;line-height:1.08;font-weight:800;letter-spacing:-1.5px}.page-label{position:absolute;top:35px;right:66px;color:#718078;font-size:10px;font-weight:700;letter-spacing:2px}.en-title{margin-top:5px;color:#829087;font-size:14px;letter-spacing:1.2px}
.text-layout{display:grid;grid-template-columns:1fr 1fr;gap:48px;align-items:center;margin-top:35px}.text-layout p{line-height:1.7}.key-text{font-size:21px;line-height:1.6!important}.key-text strong{color:#ff6844}.carrier-card{padding:24px;background:#163328;color:#fff;border:1px solid #28513f;box-shadow:12px 12px 0 #111814}.card-title{margin-bottom:14px;color:#a8c8b9;font-size:11px;letter-spacing:2px}.carrier-grid{display:grid;grid-template-columns:1fr 1fr;gap:9px}.carrier-grid span{padding:13px;background:rgba(255,255,255,.09);text-align:center;font-size:13px}.bottom-copy{margin-top:25px;padding:13px 17px;background:#192820;border:1px solid #294438;color:#b9d9c9;font-weight:700;font-size:13px}
</style>

---
layout: image-right
image: '/powchanosint1.jpg'
class: osint-page

---

<div class="page-label">05 · OPEN SOURCE INTELLIGENCE</div>

# OSINT
<div class="en-title">Open source intelligence</div>

<p class="key-text">OSINT也是 Misc 的一部分。</p>

它通过公开可获得的信息进行搜集、关联和分析

简单来说，网络上所说的“开盒”就是从开源信息中找到人的信息和地理位置

一些看似普通的公开信息也可能暴露位置、身份或其他隐私线索

<style>
.osint-page{position:relative;padding:60px 54px 48px 66px;background:#0d1210!important;color:#fff!important;font-family:Inter,"PingFang SC","Microsoft YaHei",sans-serif}.osint-page h1{margin:0;color:#fff;font-size:52px;line-height:1.08;font-weight:800;letter-spacing:-1.5px}.osint-page p{margin:11px 0;max-width:410px;color:rgba(255,255,255,.5);font-size:14px;line-height:1.7}.osint-page .key-text{margin-top:30px;color:#fff;font-size:20px}.page-label{position:absolute;top:35px;right:54px;color:rgba(255, 255, 255, 0.5);font-size:10px;font-weight:700;letter-spacing:2px}.en-title{margin-top:5px;color:#ff947a;font-size:14px;letter-spacing:1.2px}
</style>

---
layout: default
class: content-page archive-page
---

<div class="page-label">06 · ARCHIVE</div>

# 压缩包
<div class="en-title">形形色色的压缩包</div>

<div class="archive-layout">
  <div>
    <p class="key-text">Misc 题目中也常见各种<strong>加密的压缩包</strong></p>
    <p>有些密码藏在旁边的隐写中，有些密码甚至根本无法恢复</p>
  </div>
  <div class="method-list">
    <div><b>01</b><span>密码爆破</span></div>
    <div><b>02</b><span>修复伪加密</span></div>
    <div><b>03</b><span>明文攻击</span></div>
  </div>
</div>

<div class="compare-row"><span>最基础：<strong>直接尝试恢复</strong>密码</span><span>更高级：理解压缩包的<strong>结构和工作原理</strong></span></div>

<style>
.archive-page{position:relative;padding:52px 66px;background:#0d1210!important;color:#f1f4f1!important;font-family:Inter,"PingFang SC","Microsoft YaHei",sans-serif}.archive-page::after{content:"";position:absolute;left:66px;right:66px;bottom:27px;height:1px;background:#2b3630}.archive-page h1{margin:0;color:#f1f4f1;font-size:42px;line-height:1.08;font-weight:800;letter-spacing:-1.5px}.page-label{position:absolute;top:35px;right:66px;color:#718078;font-size:10px;font-weight:700;letter-spacing:2px}.en-title{margin-top:5px;color:#829087;font-size:14px;letter-spacing:1.2px}.archive-layout{display:grid;grid-template-columns:1fr 1fr;gap:48px;align-items:center;margin-top:35px}.archive-layout p{line-height:1.7}.key-text{font-size:21px;line-height:1.6!important}.key-text strong{color:#ff6844}.method-list{display:grid;gap:10px}.method-list>div{display:flex;align-items:center;gap:17px;padding:14px 17px;background:#171e1a;border:1px solid #2b3630;border-left:4px solid #3b8b6b}.method-list b{color:#ff6844;font-size:10px}.compare-row{display:grid;grid-template-columns:1fr 1fr;gap:12px;margin-top:28px}.compare-row span{padding:14px 17px;background:#171e1a;border:1px solid #2b3630;font-size:13px}.compare-row strong{color:#ff6844}
</style>

---
layout: default
class: content-page forensics-page
---

<div class="page-label">07 · FORENSICS</div>

# 流量分析（取证）
<div class="en-title">forensics</div>

<div class="forensics-copy">
  <p style="font-size:12px">取证是从数据中恢复，寻找并分析有价值的信息，最常见的是流量取证</p>
  <p style="font-size:12px">流量一般就是网络/USB流量，设备和网络活动传输的一个个数据包汇集起来就变成了一组流量</p>
  <p style="font-size:12px">流量分析，就是对这些数据包进行查看和分析，从中寻找通信内容与相关线索</p>
</div>

<div class="image-frame">
  <div class="frame-bar"><i></i><i></i><i></i><span>pcap 流量包</span></div>
  <img src="./pcap.png" alt="pcap流量包">
</div>

<style>
.forensics-page{position:relative;padding:52px 66px;background:#0d1210!important;color:#f1f4f1!important;font-family:Inter,"PingFang SC","Microsoft YaHei",sans-serif}.forensics-page::after{content:"";position:absolute;left:66px;right:66px;bottom:27px;height:1px;background:#2b3630}.forensics-page h1{margin:0;color:#f1f4f1;font-size:42px;line-height:1.08;font-weight:800;letter-spacing:-1.5px}.page-label{position:absolute;top:35px;right:66px;color:#718078;font-size:10px;font-weight:700;letter-spacing:2px}.en-title{margin-top:5px;color:#829087;font-size:14px;letter-spacing:1.2px}.forensics-copy{display:grid;grid-template-columns:repeat(3,1fr);gap:15px;margin:14px 0}.forensics-copy p{margin:0;color:#9aa69f;font-size:11px;line-height:1.55}.image-frame{height:260px;overflow:hidden;background:#080d0b;border:1px solid #2b3630;border-radius:4px;box-shadow:0 10px 26px rgba(0,0,0,.28)}.frame-bar{height:27px;display:flex;align-items:center;gap:6px;padding:0 11px;color:#87948c;font-size:9px}.frame-bar i{width:6px;height:6px;border-radius:50%;background:#f36a4b}.frame-bar i:nth-child(2){background:#e5b94f}.frame-bar i:nth-child(3){background:#72a87a}.frame-bar span{margin-left:6px}.image-frame img{display:block;width:100%;height:233px;object-fit:cover;object-position:top}
</style>

---
layout: end
class: end-page
---

<div class="cover-tag">END OF PRESENTATION</div>

# THANKS FOR WATCHING

## 谢谢观看

<div class="end-speaker">主讲人：taem</div>

<style>
.end-page{position:relative;display:flex;flex-direction:column;justify-content:center;padding:52px 66px;background:#10251d!important;color:#fff!important;text-align:left!important;overflow:hidden;font-family:Inter,"PingFang SC","Microsoft YaHei",sans-serif}.end-page::after{content:"";position:absolute;right:-100px;top:-120px;width:400px;height:400px;border:60px solid rgba(255,255,255,.06);transform:rotate(18deg)}.cover-tag{color:#ff8568;font-size:11px;font-weight:800;letter-spacing:3px}.end-page h1{margin:20px 0 8px;max-width:650px;color:#fff;font-size:58px;line-height:1;font-weight:800}.end-page h2{color:#ff8568;font-weight:500}.end-speaker{position:absolute;left:66px;bottom:40px;padding-top:13px;width:calc(100% - 132px);border-top:1px solid rgba(255,255,255,.22);color:rgba(255,255,255,.65);font-size:12px;letter-spacing:2px}
</style>
