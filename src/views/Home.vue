<template>
  <div class="container">
    <div id="name-container">
      <img id="avatar" src="./../assets/images/av.png" alt="avatar" />
      <h1>Spencer Woo</h1>
    </div>
    <div class="title-desc-container">
      <a id="github" href="https://github.com/ghosthim" target="_blank" rel="noopener noreferrer"
        ><img class="title-font" src="./../assets/images/github.svg" />Developer</a
      >
      <span>/</span>
      <a id="blog" href="https://blog.api2u.me" target="_blank" rel="noopener noreferrer"
        ><img class="title-font" src="./../assets/images/zeit.svg" />Blogger</a
      >
    </div>
    <div class="article">
      <h2>WHO AM I</h2>
      <p>
        I'm <i>Youngeje Lee</i> with the ID <i>API2U</i>. Some other variations:
      </p>

      <h2>Academics</h2>
      <ul>
        <li>
          🍭 QLU (🇨🇳
          <a href="http://www.qlu.edu.cn/" target="_blank" rel="noopener noreferrer">QiLu University of Technology</a
          >).
        </li>
      </ul>

      <h2>Devices</h2>
      <ul>
        <li>⚫ DELL G3 3579</li>
        <li>🔵 iPhone 8 PLUS / iPad Pro 2020 / AirPods 2</li>
      </ul>

      <h2>Contacts</h2>
      <ul>
        <li>
          <b>Email：</b>
          <a href="mailto:i@api2u.me">i#api2u.me</a><i> (Preferred)</i>
        </li>
      </ul>
    </div>
  </div>
</template>

<style lang="css" scoped>
#name-container {
  display: flex;
  flex-direction: row;
  justify-content: flex-start;
  align-items: center;
}

#avatar {
  width: 42px;
  height: 42px;
  border-radius: 50%;
  margin-right: 12px;
}

#copyright:hover {
  border: none;
}

.title-font {
  width: 16px;
  height: 16px;
  margin-right: 4px;
}

.title-desc-container {
  display: flex;
  align-items: center;
  justify-content: flex-start;
  margin: 8px 0;
}

.title-desc-container a {
  display: flex;
  align-items: center;
}

.title-desc-container span {
  margin: 0px 4px;
}

.title-desc-container #github {
  color: #24292e;
}

.title-desc-container #sspai {
  color: #ca2c2a;
}

.title-desc-container #blog {
  color: #0070f3;
}
</style>
