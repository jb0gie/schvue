<template>
  <div class="p-4">
    <div
      class="navbar rounded-full bg-gradient-to-r from-[#247420] to-[#420247]"
    >
      <div class="navbar-start">
        <div class="text-4xl font-bold">
          <code
            style="
              color: transparent;
              background-clip: text;
              -webkit-background-clip: text;
              background-image: url('https://media3.giphy.com/media/zkrFC9UU5O9wxQJ69s/giphy.gif');
            "
          >
            schweb3
          </code>
          <span class="text-pink-300">.</span>
          <code>
            <span
              style="
                color: transparent;
                background-clip: text;
                -webkit-background-clip: text;
                background-image: url('https://media2.giphy.com/media/bTDdkhpX34Hwp1eaiS/200w.webp?cid=ecf05e47havsfdo7vnub33cofwhw8suyhqvh1e5t1wr1veb4&rid=200w.webp&ct=g');
              "
            >
              247
            </span>
            <span
              style="
                color: transparent;
                background-clip: text;
                -webkit-background-clip: text;
                background-image: url('https://i.giphy.com/media/5xtDarMq3ckPLlJtUHK/giphy-downsized-large.gif');
              "
            >
              420
            </span>
          </code>
          <span class="text-pink-300">.</span>
          <code
            style="
              color: transparent;
              background-clip: text;
              -webkit-background-clip: text;
              background-image: url('https://media2.giphy.com/media/JlVxiw2MrW4DwKeG4e/giphy.gif?cid=ecf05e47havsfdo7vnub33cofwhw8suyhqvh1e5t1wr1veb4&rid=giphy.gif&ct=g');
            "
          >
            xyz
          </code>
        </div>
        <div>
          <img
            src="https://image.flaticon.com/icons/svg/497/497348.svg"
            alt
            class="w-8"
          />
        </div>
      </div>
      <div class="navbar-end">
        <div class="avatar avatar-ring avatar-md">
          <div class="dropdown-container">
            <div class="dropdown">
              <label
                class="btn btn-ghost flex cursor-pointer px-0"
                tabindex="0"
              >
                <img
                  src="https://mastodon.247420.xyz/system/accounts/avatars/109/473/867/332/038/427/original/4b3de76134039d66.png"
                  alt="avatar"
                />
              </label>
              <div class="dropdown-menu dropdown-menu-bottom-left">
                <router-link
                  tabindex="-1"
                  class="dropdown-item text-sm"
                  to="/welcome"
                >
                  welcome
                </router-link>
                <router-link
                  tabindex="-1"
                  class="dropdown-item text-sm"
                  to="/home"
                >
                  home
                </router-link>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      title: 'what a schvue',
    };
  },
};
</script>
