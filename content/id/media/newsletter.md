---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Newsletter"
linktitle: "Newsletter"
summary:
date: 2021-10-10
draft: false  # Is this a draft? true/false
toc: true  # Show table of contents? true/false
type: docs  # Do not modify.
weight: 1
# Add menu entry to sidebar.
# - Substitute `example` with the name of your course/documentation folder.
# - name: Declare this menu item as a parent with ID `name`.
# - parent: Reference a parent ID if this page is a child.
# - weight: Position of link in menu.
menu:
  media:
    parent: Media
    name: Newsletter
    # parent: Fasilitas
    weight: 2
---

<div class="row">
  <div class="column">
    <center><b>Edisi 01: April - Juni 2021</b></center>
  </div>
  <div class="column">
    <center><b>Edisi 02: Juli - September 2021</b></center>
  </div>
  <div class="column">
    <center><b>Edisi 03: Oktober - Desember 2021</b></center>
  </div>
</div>

<div class="row">
  <div class="column">
    <img src="/img/cover-01.png"></img>
    <p style="font-size: .8em" class="showmore">
    Resolusi Tinggi (56 MB) {{% staticref "files/newsletter/NEBULA_E01.pdf" "newtab" %}}<button>Unduh</button>{{% /staticref %}} <br>
    Resolusi Rendah (14 MB) {{% staticref "files/newsletter/NEBULA_E01_low.pdf" "newtab" %}}<button>Unduh</button>{{% /staticref %}} 
    </p>
  </div>
  <div class="column">
     <img src="/img/cover-02.png"></img>
    <p style="font-size: .8em" class="showmore">
    Resolusi Tinggi (75 MB) {{% staticref "files/newsletter/NEBULA_E02_HD_opt.pdf" "newtab" %}}<button>Unduh</button>{{% /staticref %}} <br>
    Resolusi Rendah (33 MB) {{% staticref "files/newsletter/NEBULA_E02_SD.pdf" "newtab" %}}<button>Unduh</button>{{% /staticref %}} 
    </p>
  </div>
  <div class="column">
    <img src="/img/cover-03.png"></img>
    <p style="font-size: .8em" class="showmore">
    Resolusi Tinggi (26 MB) {{% staticref "files/newsletter/NEBULA_E03_HD.pdf" "newtab" %}}<button>Unduh</button>{{% /staticref %}} <br>
    Resolusi Rendah (7 MB) {{% staticref "files/newsletter/NEBULA_E03_SD.pdf" "newtab" %}}<button>Unduh</button>{{% /staticref %}}
    </p>
  </div>
</div>

<div class="row">
  <!-- <div class="column">
    <p style="font-size: .8em">Narasumber: <br> 1. Premana W. Premadi, Ph.D. <br>  2. Muhammad Yusuf, S.Si.</p>
  </div> -->
  <div class="column">
    <!-- <p style="font-size: .8em">Narasumber: <br> 1. Dr. Kiki Vierdayanti <br>  2. Muhammad Yusuf, S.Si.</p> -->
  </div>
  <div class="column">
    <!-- <p style="font-size: .8em">Narasumber: <br> 1. Premana W. Premadi, Ph.D. <br>  2. Muhammad Yusuf, S.Si.</p> -->
  </div>
</div>

<style>
* {
  box-sizing: border-box;
}

/* Create three equal columns that floats next to each other */
.column {
  float: left;
  width: 33%;
  padding: 10px;
  /* text-align: justify;
  text-justify: inter-word; */
  }

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* div.desc {
  padding: 20px;
} */

/* @media screen and (min-width: 601px) {
  p {
    font-size: 16px;
  }
}

@media screen and (max-width: 600px) {
  p {
    font-size: 14px;
  }
} */

.showmore {
  font-size: 0.8em;
}

.showmore .more, .showmore.show .dots {
  display: none
}

.showmore.show .more {
  display: inline
}

.showmore button {
  cursor: pointer;
  display: block;
  margin-top: 0.5em;
  margin-bottom: 1em;
  font-weight: bold;
  background-color: #656565;
  color: white;
  border: none;
  outline: none;
  padding: 0.5em;
}
</style>
