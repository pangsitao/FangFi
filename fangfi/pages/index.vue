<template>
  <div class="container">
    <header>
      <nav>
        <a>DOCS</a>
        <a>APP</a>
        <a href="" target="_blank" class="telegram"
          ><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 20">
            <path
              fill-rule="evenodd"
              d="M18.38 19.78a1.19 1.19 0 001.11.14 1.17 1.17 0 00.73-.84C21.08 15 23.19 4.66 24 1a.79.79 0 00-1.05-.9C18.73 1.6 5.82 6.45.54 8.4a.83.83 0 00-.54.8.82.82 0 00.59.8c2.37.71 5.48 1.7 5.48 1.7s1.45 4.3 2.21 6.57a.85.85 0 001.41.37l3.1-2.92s3.57 2.62 5.59 4.06zm-11-8.68l1.68 5.54.38-3.51L19.61 4a.28.28 0 00-.34-.44z"
            ></path></svg
        ></a>
      </nav>
    </header>
    <section class="section0">
      <h2>想了解更多，阅读我们的文档和白皮书，或者参加我们的社区 Telegram  Discord</h2>
    </section>
    <section class="section1">
      <h2>How It Works</h2>
      <article>
        Fang协议维护一系列映像资产，可以跟踪真实世界不动产的价格。我们的镜像资产系统致力于使用智能合约成为区块链上的基础设施，将真实世界的不动产带入区块链世界。
      </article>
      <div>
        
      </div>
    </section>
    <section class="section2"></section>
    <div class="footer">
      <div class="copyright"></div>
      <div>
        <a href="https://github.com/pangsitao/FangFi" target="_blank" rel="noopener noreferrer"><img src="../assets/img/social_github.png" alt="Github" /></a>
        <a href="" target="_blank" rel="noopener noreferrer"><img src="../assets/img/social_telegram.png" alt="Telegram" /></a>
        <a href="" target="_blank" rel="noopener noreferrer"><img src="../assets/img/social_discord.png" alt="Discord" /></a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  components: {},
};
</script>

<style>
.container {
  font-family: "Poppins",sans-serif;
  font-style: normal;
  background-color: #fff;
  color: #232c45;
}

header nav a {
  font-size: 14.2px;
  line-height: 44px;
  font-weight: 600;
  letter-spacing: 0.6px;
  padding: 0 15px;
  display: inline-block;
  vertical-align: middle;
  position: relative;
  cursor: pointer;
  transition: color 0.2s;
  text-transform: uppercase;
  color: #232c45;
}

header nav a:before{
  content: '';
  position: absolute;
  top: 50%;
  left: 0;
  margin-top: -6px;
  height: 12px;
  width: 1px;
  background: #11182f;
  opacity: 0.2;
}

header nav a:first-child:before{
  display: none;
}

header nav a svg {
  width: 20px;
  height: 16px;
  fill: #232c45;
  transition: 0.2s;
}

section {
  padding: 160px 30px;
}

.footer{
  padding: 0 30px;
  background-color: #f5f8fc;
}

.footer div{
  font-weight: 500;
  color: #000;
}

.footer a{
  opacity: 0.25;
  padding: 10px;
  transform: .2s;
}
</style>
