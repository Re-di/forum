<template>
  <div class="tile is-ancestor">
    <div class="tile is-parent">
      <article class="tile is-child box">
        <p class="subtitle">热门板块</p>
        <p align="right">
          <button class="button is-info">全部板块</button>
        </p>
        <div class="card">
          <header class="card-header">
            <p class="card-header-title">板块名</p>
            <a href="#" class="card-header-icon" aria-label="more options">
              <span class="icon">
                <i class="fas fa-angle-down" aria-hidden="true"></i>
              </span>
            </a>
          </header>
          <div class="card-content">
            <div class="content">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus nec iaculis mauris.板块简介
              <a
                href="#"
              >@bulmaio</a>.
              <a href="#">#css</a>
              <a href="#">#responsive</a>
              <br />
            </div>
          </div>
          <footer class="card-footer">
            <a href="#" class="card-footer-item">关注</a>
            <a href="#" class="card-footer-item">进入板块</a>
          </footer>
        </div>
      </article>
    </div>
    <div class="tile is-parent is-8">
      <article class="tile is-child box">
        <p align="right">
          <button class="button is-info">更多推荐</button>
        </p>
        <p class="subtitle">推荐帖子</p>

        <div class="box">
          <article class="media">
            <div class="media-left">
              <figure class="image is-64x64">
                <img src="https://bulma.io/images/placeholders/128x128.png" alt="Image" />
              </figure>
            </div>
            <div class="media-content">
              <div class="content">
                <p>
                  <strong>发帖人用户名</strong>
                  <small>@发帖人主页</small>
                  <br />帖子标题
                </p>
                <button class="button is-info">查看详情</button>
              </div>
            </div>
          </article>
        </div>
        <div class="box">
          <article class="media">
            <div class="media-left">
              <figure class="image is-64x64">
                <img src="https://bulma.io/images/placeholders/128x128.png" alt="Image" />
              </figure>
            </div>
            <div class="media-content">
              <div class="content">
                <p>
                  <strong>发帖人用户名</strong>
                  <small>@发帖人主页</small>
                  <br />帖子标题
                </p>
                <button class="button is-info">查看详情</button>
              </div>
            </div>
          </article>
        </div>
      </article>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.subtitle {
  text-align: left;
}
.button {
  text-align: center;
  margin: 0 auto;
}
</style>




