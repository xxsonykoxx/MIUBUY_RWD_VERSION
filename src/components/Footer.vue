<template>
  <footer>
    <h5 class="copyright"><span>© </span>baihu & sonyko</h5>
  </footer>
</template>

<style lang="scss">
footer {
  margin-top: 10px;
}
.copyright {
  display: flex;
  align-items: center;
  position: absolute;
  bottom: 5px;
  left: 50%;
  transform: translateX(-50%);
  font-family: myfont, serif;
  font-weight: lighter;
  color: #fff;
  font-size: 24px;
  span {
    font-size: 14px;
  }
}
@media screen and (max-width: 768px) {
  .copyright {
    position: relative !important;
    justify-content: center;
    align-items: center;
    bottom: 0;
    transform: none;
    margin-bottom: 15px;
  }
}
</style>
