<template>
  <div>
    Component DiagsReport
    <div id="tweet">
      <span v-html="content"></span>
    </div>
    <blockquote class="twitter-tweet">
      <p lang="pl" dir="ltr">
        📊W ciągu doby wykonano ponad 4,1 tys. testów na
        <a
          href="https://twitter.com/hashtag/koronawirus?src=hash&amp;ref_src=twsrc%5Etfw"
        >#koronawirus</a>.
        <a href="https://t.co/nSDuVxskn4">pic.twitter.com/nSDuVxskn4</a>
      </p>&mdash; Ministerstwo Zdrowia (@MZ_GOV_PL)
      <a
        href="https://twitter.com/MZ_GOV_PL/status/1244218140613054464?ref_src=twsrc%5Etfw"
      >March 29, 2020</a>
    </blockquote>
    <blockquote class="twitter-tweet">
      <p lang="pl" dir="ltr">
        📊 W ciągu doby wykonano ponad 4,6 tys. testów na
        <a
          href="https://twitter.com/hashtag/koronawirus?src=hash&amp;ref_src=twsrc%5Etfw"
        >#koronawirus</a>.
        <a href="https://t.co/5eSz8DiuBp">pic.twitter.com/5eSz8DiuBp</a>
      </p>&mdash; Ministerstwo Zdrowia (@MZ_GOV_PL)
      <a
        href="https://twitter.com/MZ_GOV_PL/status/1243855446902964227?ref_src=twsrc%5Etfw"
      >March 28, 2020</a>
    </blockquote>
    <div>
      <span v-html="content20190327"></span>
    </div>
  </div>
</template>
<script>
export default {
  name: "diags-report",
  data() {
    return {
      links: [""],
      content: null,
      content20190327: null
    };
  },
  created() {
    this.content = `
      <blockquote class="twitter-tweet">
        <p lang="pl" dir="ltr">
          📊W ciągu doby wykonano ponad 4,1 tys. testów na
          <a
            href="https://twitter.com/hashtag/koronawirus?src=hash&amp;ref_src=twsrc%5Etfw"
          >#koronawirus</a>.
          <a href="https://t.co/nSDuVxskn4">pic.twitter.com/nSDuVxskn4</a>
        </p>&mdash; Ministerstwo Zdrowia (@MZ_GOV_PL)
        <a
          href="https://twitter.com/MZ_GOV_PL/status/1244218140613054464?ref_src=twsrc%5Etfw"
        >March 29, 2020</a>
      </blockquote>
    `,
    this.content20190327 = `<blockquote class="twitter-tweet"><p lang="pl" dir="ltr">📊W ciągu doby wykonano ponad 4,5 tys. testów na <a href="https://twitter.com/hashtag/koronawirus?src=hash&amp;ref_src=twsrc%5Etfw">#koronawirus</a>. <a href="https://t.co/BeFTcAxSQ6">pic.twitter.com/BeFTcAxSQ6</a></p>&mdash; Ministerstwo Zdrowia (@MZ_GOV_PL) <a href="https://twitter.com/MZ_GOV_PL/status/1243478013255340033?ref_src=twsrc%5Etfw">March 27, 2020</a></blockquote>`

  },
  mounted() {
    // /* eslint-disable */
    // (function(d, s, id) {
    //   var js,
    //     fjs = d.getElementsByTagName(s)[0],
    //     t = window.twttr || {};
    //   if (d.getElementById(id)) return t.widgets.load();
    //   js = d.createElement(s);
    //   js.id = id;
    //   js.src = "https://platform.twitter.com/widgets.js";
    //   fjs.parentNode.insertBefore(js, fjs);
    //   t._e = [];
    //   t.ready = function(f) {
    //     t._e.push(f);
    //   };
    //   return t;
    // })(document, "script", "twitter-wjs");
    // /* eslint-enable */
  }
};
</script>
