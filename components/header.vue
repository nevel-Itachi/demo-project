<template>
  <div class="header">
    <div class="container-fluid px-0">
      <div class="watch-header">
    <div class="watch-header__left">
      <div class="watch-header__left__name">
        <img src="../assets/image/logo.png" />
      </div>
      <div class="watch-header__left__menu">
        <div class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" id="menu-deal" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            Giao dịch
          </a>
          <ul class="dropdown-menu" aria-labelledby="menu-deal">
            <li><a class="dropdown-item" href="#">Action</a></li>
            <li><a class="dropdown-item" href="#">Another action</a></li>
            <li><a class="dropdown-item" href="#">Something else here</a></li>
          </ul>
        </div>
        <div class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" id="menu-support" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            Hỗ trợ
          </a>
          <ul class="dropdown-menu" aria-labelledby="menu-support">
            <li><a class="dropdown-item" href="#">Action</a></li>
            <li><a class="dropdown-item" href="#">Another action</a></li>
            <li><a class="dropdown-item" href="#">Something else here</a></li>
          </ul>
        </div>
      </div>
    </div>
    <div class="watch-header__right">
      <button type="button">Liên kết ví</button>
    </div>
  </div>
  </div>
  </div>
</template>

<style lang="scss">
  .watch-header {
    box-sizing: border-box;
    display: flex;
    justify-content: space-between;
    background: #FFFFFF;
    border-bottom: 1px solid #F4F4F5;
    &__left {
      display: flex;
      &__name {
        padding: 24px 94px 24px 24px;
      }
      &__menu {
        display: flex;
        gap: 27px;
        padding: 28px 0px;
        font-family: 'Roboto';
        font-style: normal;
        font-weight: 500;
        font-size: 16px;
        line-height: 24px;
        align-items: center;
        color: #18181B;
      }
    }
    &__right {
      padding: 16px 24px 16px 0px;
      button {
        display: flex;
        flex-direction: row;
        justify-content: center;
        align-items: center;
        padding: 14px 48px;
        background: #FAAC2E;
        font-family: 'Roboto';
        font-style: normal;
        font-weight: 500;
        font-size: 14px;
        line-height: 20px;
        color: #18181B;
        border-radius: 8px;
        border: none;
      }
    }
  }
</style>