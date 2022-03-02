---
layout: page
title: 画集
permalink: photos.html
index: 3
---

<style>
  .container { width: initial; }
  .content { max-width: initial; }
  .grid::after {
    content: '';
    display: block;
    clear: both;
  }
  .grid-item {
    float: left;
    width: 250px;
    margin-bottom: 10px;
  }
  .grid-size {
    width: 250px;
  }
  @media (max-width: 48em) {
    .grid-item,
    .grid-size {
      width: calc(50% - 10px);
    }
  }
  .grid-item a {
    display: block;
    width: 100%;
  }
  .grid-item img {
    margin: 0;
    transition: .3s ease;
  }
  .grid-item a:hover {
    border-bottom: none;
  }
  /* view.js */
  .viewer li {
    -webkit-transition: width 500ms cubic-bezier(0.075, 0.820, 0.165, 1.000);
    -moz-transition: width 500ms cubic-bezier(0.075, 0.820, 0.165, 1.000);
    transition: width 500ms cubic-bezier(0.075, 0.820, 0.165, 1.000);
  }
  .viewer .caption {
    visibility: hidden;
    opacity: 0;
    line-height: 50px;
    font-size: 0.8rem;
    -webkit-transition: opacity 1.5s ease-in-out;
    -moz-transition: opacity 1.5s ease-in-out;
    transition: opacity 1.5s ease-in-out;
  }
  .viewer .current .caption {
    opacity: 100;
    visibility: visible;
  }
  .viewer li > div {
    top:20px;
    bottom:20px;
    left:0;
    right:0;
  }
  .viewer li.has-caption > div {
    bottom:50px;
  }
  .viewer span > img {
    display: inline;
  }

</style>

<div class="grid">
  <div class="grid-size"></div>
  <!-- Add new photo from here -->
  <div class="grid-item">
    <a class="view" href="https://storage.gra.cloud.ovh.net/v1/AUTH_011f6e315d3744d498d93f6fa0d9b5ee/qotoorg/media_attachments/files/107/430/071/811/245/466/original/217b6a368289b054.jpg" title="世界之夜" rel="vsco">
      <img src="https://storage.gra.cloud.ovh.net/v1/AUTH_011f6e315d3744d498d93f6fa0d9b5ee/qotoorg/media_attachments/files/107/430/071/811/245/466/original/217b6a368289b054.jpg">
    </a>
  </div>
  <div class="grid-item">
    <a class="view" href="https://storage.gra.cloud.ovh.net/v1/AUTH_011f6e315d3744d498d93f6fa0d9b5ee/qotoorg/media_attachments/files/107/430/071/932/258/705/original/3e5a9a23ae5e8e25.png" title="闭上眼睛也没法不看见" rel="vsco">
      <img src="https://storage.gra.cloud.ovh.net/v1/AUTH_011f6e315d3744d498d93f6fa0d9b5ee/qotoorg/media_attachments/files/107/430/071/932/258/705/original/3e5a9a23ae5e8e25.png">
    </a>
  </div>
  <div class="grid-item">
    <a class="view" href="https://storage.gra.cloud.ovh.net/v1/AUTH_011f6e315d3744d498d93f6fa0d9b5ee/qotoorg/media_attachments/files/107/430/071/675/522/721/original/20d6fb6b47c2db36.png" title="友猫的基督教无神论主义猫猫" rel="vsco">
      <img src="https://storage.gra.cloud.ovh.net/v1/AUTH_011f6e315d3744d498d93f6fa0d9b5ee/qotoorg/media_attachments/files/107/430/071/675/522/721/original/20d6fb6b47c2db36.png">
    </a>
  </div>
  <div class="grid-item">
    <a class="view" href="https://storage.gra.cloud.ovh.net/v1/AUTH_011f6e315d3744d498d93f6fa0d9b5ee/qotoorg/media_attachments/files/107/430/071/793/407/477/original/8ac4e1039562e1e6.jpg" title="屻国" rel="vsco">
      <img src="https://storage.gra.cloud.ovh.net/v1/AUTH_011f6e315d3744d498d93f6fa0d9b5ee/qotoorg/media_attachments/files/107/430/071/793/407/477/original/8ac4e1039562e1e6.jpg">
    </a>
  </div>
  <div class="grid-item">
    <a class="view" href="/public/images/202003.jpg" title="回到水中" rel="vsco">
      <img src="/public/images/202003.jpg">
    </a>
  </div>
  <div class="grid-item">
    <a class="view" href="/public/images/202004.jpg" title="恶种" rel="vsco">
      <img src="/public/images/202004.jpg">
    </a>
  </div>
  <div class="grid-item">
    <a class="view" href="/public/images/202001.jpg" title="以仇恨供养" rel="vsco">
      <img src="/public/images/202001.jpg">
    </a>
  </div>
  <div class="grid-item">
    <a class="view" href="/public/images/202002.jpg" title="奶牛猫！" rel="vsco">
      <img src="/public/images/202002.jpg">
    </a>
  </div>
  <div class="grid-item">
    <a class="view" href="/public/images/恶搞.png" title="明明旁边就有山楂树还要卖艺买冰糖葫芦的衡山派三人组" rel="vsco">
      <img src="/public/images/恶搞.png">
    </a>
  </div>
  <div class="grid-item">
    <a class="view" href="/public/images/202005.png" title="开弓" rel="vsco">
      <img src="/public/images/202005.png">
    </a>
  </div>
    <div class="grid-item">
    <a class="view" href="/public/images/懒得产粮.png" title="周祝-懒得产粮AU问卷" rel="vsco">
      <img src="/public/images/懒得产粮.png">
    </a>
  </div>
    <div class="grid-item">
    <a class="view" href="/public/images/20220301.png" title="草稿1" rel="vsco">
      <img src="/public/images/20220301.png">
    </a>
  </div>
</div>

<script src="{{site.baseurl}}/public/js/masonry.pkgd.min.js"></script>
<script src="{{site.baseurl}}/public/js/imagesloaded.pkgd.min.js"></script>
<script src="{{site.baseurl}}/public/js/view.min.js?auto"></script>
<script>
  var grid = document.querySelector('.grid');

  var msnry = new Masonry(grid, {
    itemSelector: '.grid-item',
    columnWidth: '.grid-size',
    gutter: 10
  });

  imagesLoaded(grid).on('progress', function() {
    msnry.layout();
  });
</script>