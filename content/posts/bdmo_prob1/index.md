---
title: "জ্যামিতি সমস্যা (BdMO Regional Geometry Problem)"
date: 2026-10-14
draft: true
description: "BdMO Regional Geometry Problem-এর জ্যামিতিক সমাধান।"
tags: ["Problem Solving", "Math"]
---

BdMO Regional Geometry Problem-এর জ্যামিতিক সমাধান।

<!--more-->
![জ্যামিতির চিত্র](/images/ss.png)
![জ্যামিতির চিত্র](/images/ss2.png)
\(B,G\) যোগ করি এবং \(GH \perp BD\) আঁকি।

যেহেতু \(GH \parallel CD\),

\[
\therefore CD = 4
\]

আবার,

\[
BG = BD = 8
\]

(এরা একই বৃত্তের ব্যাসার্ধ)

এবং

\[
BA = BF = 4
\]

(ভাব কেন?)

ধরি,

\[
\sin \theta = \frac{4}{8} = \frac{1}{2}
\]

\[
\theta = \arcsin \frac{1}{2}
\]

\[
\therefore \theta = 30^\circ
\]

এখন, বৃত্তখণ্ড \(BGD\)-এর ক্ষেত্রফল,

\[
[BGD]
= \frac{\pi r^2 \theta}{360^\circ}
\]

\[
= \frac{\pi \times 8^2 \times 30}{360}
= \frac{16\pi}{3}
\]

পিথাগোরাসের উপপাদ্য অনুযায়ী,

\[
BG^2 = AG^2 + AB^2
\]

\[
AG^2 = BG^2 - AB^2
\]

\[
= 8^2 - 4^2 = 48
\]

\[
\therefore AG = \sqrt{48} = 4\sqrt{3}
\]

এখন, \(\triangle ABG\)-এর ক্ষেত্রফল,

\[
[ABG]
= \frac{1}{2} \times 4 \times 4\sqrt{3}
= 8\sqrt{3}
\]

আবার, বৃত্তখণ্ড \(ABF\)-এর ক্ষেত্রফল,

\[
[ABF]
= \frac{\pi r^2 \theta}{360^\circ}
\]

\[
= \frac{90^\circ \times 16\pi}{360^\circ}
= 4\pi
\]

সুতরাং, চিত্রের ক্ষেত্রফল,

\[
[AGDF] = [BGD] + [ABG] - [ABF]
\]

\[
= \frac{16\pi}{3} + 8\sqrt{3} - 4\pi
\]

\[
\therefore [AGDF] = \frac{4\pi}{3} + 8\sqrt{3}
\]

এখানে,

\[
a = \frac{4}{3}, \qquad b = 8
\]

অতএব,

\[
\boxed{\frac{b}{a} = 6}
\]

**বি.দ্র.:** এখানে \([x]\) দ্বারা \(x\)-এর ক্ষেত্রফল বোঝানো হয়েছে।