<template>
  <header class="AppHeader">
    <div class="HeaderBlock">

      <button class="Button -primary ControlButton" id="HeaderSidebarToggleButton">
        <i class="fa fa-bars Icon" aria-hidden="true"></i>
      </button>

      <form class="Search">
        <button class="Button -primary ControlButton" id="HeaderSearchToggleButton">
          <i class="fa fa-search Icon" aria-hidden="true"></i>
        </button>
        <input type="seaarch" class="FormControl -sm" placeholder="Search...">
      </form>

    </div>
    <div class="HeaderBlock">
      <nav class="ProjectNav">


        <a
          href=""
          class="Button -sm -default -outline -rounded">
          <i class="fa fa-github"></i>
          <span>View on GitHub</span>
        </a>

        <a
          href=""
          class="Button -sm -default -outline -rounded">
          <i class="fa fa-cloud-download"></i>
          <span>Download</span>
        </a>

        <a
          href=""
          class="Button -sm -primary -raised -rounded">
          <i class="fa fa-heart"></i>
          <span>Support Us</span>
        </a>
      </nav>
    </div>
    <div class="HeaderBlock">

      <nav class="ProfileNav">
        <div class="Dropdown NavItem Notifications">
          <a
            href=""
            class="DropdownToggle NavLink NotificationsLink">
            <i class="fa fa-bell-o"></i>
            <sup>
              <span class="Counter">8</span>
            </sup>
          </a>
          <div class="DropdownContent -end">
            Dropdown Content
          </div>
        </div>
        <div class="Dropdown NavItem Profile">
          <a
            href=""
            class="DropdownToggle NavLink ProfileLink">
            <div
              class="Img"
              style="
                background-image: url('https://avatars3.githubusercontent.com/u/3959008?v=3&amp;s=40')
              ">
            </div>
            <div class="Name">
              John Doe
            </div>
          </a>
          <div class="DropdownContent -end">
            <nav class="Nav">
              <a href="">
                <i class="fa fa-user Icon"></i>
                Profile
              </a>
              <a href="">
                <i class="fa fa-gear Icon"></i>
                Settings
              </a>
              <div class="Divider"></div>
              <a href="">
                <i class="fa fa-power-off Icon"></i>
                Logout
              </a>
            </nav>
          </div>
        </div>
      </nav>

    </div>
  </header>
</template>

<style lang="scss" src="./Header.scss"></style>

<script>
  export default {

  };
</script>
