---
title:  Matahari  Saat Ini
date: 2020-12-09T00:00:00.000Z
lastmod: 2020-12-09T00:00:00.000Z
draft: true
toc: true
type: docs
menu:
  penelitian-2:
    name: Matahari Saat Ini
    weight: 2

weight: 2
---
<style>
/*
  The grid itself needs only 4 CSS declarations:
*/

.myGallery {
  display: grid;
  grid-gap: 10px;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
}

.myGallery img {
  width: 100%;
}

/*
  And here are some declarations for the image caption.
  Just hover over one of the last 5 images to see it.
*/

.myGallery .item {
  position: relative;
  overflow: hidden;
}

.myGallery .item img {
  vertical-align: middle;
}

.myGallery .caption {
  margin: 0;
  padding: 1em;
  position: absolute;
  z-index: 1;
  bottom: 0;
  left: 0;
  width: 100%;
  max-height: 100%;
  overflow: auto;
  box-sizing: border-box;
  transition: transform 0.5s;
  transform: translateY(100%);
  background: rgba(0, 0, 0, 0.7);
  color: rgb(255, 255, 255);
}

.myGallery .item:hover .caption {
  transform: translateY(0%);
}

/*
  The rest is only styling for this example page
*/

/* @import url("https://fonts.googleapis.com/css2?family=Vollkorn:wght@400;900&display=swap");

body {
  font: 400 1.5em/1.58 Vollkorn, serif;
} */

/* h1,
p {
  text-align: center;
} */

.myGallery {
  font-size: 1rem;
}
</style>

<div class="myGallery">
  <div class="item">
    <img src="/img/sun/2020-10-23-0313_3_CaK.jpg" />
    <span class="caption">CaK - 23 Okt 2020 03:13 UT</span>
  </div>
  <div class="item">
    <img src="/img/sun/2020-10-23-0310_6_Halpha.jpg" />
    <span class="caption">H-alpha - 23 Okt 2020 03:10 UT</span>
  </div>
  <div class="item">
    <img src="/img/sun/2020-09-28-0317_5_white.jpg" />
    <span class="caption">White Light - 28 Sep 2020 03:17 UT</span>
  </div>
</div>