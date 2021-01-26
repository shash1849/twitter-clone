# twitter-clone
html

<!-- Fixed top navbar -->
<nav class="navbar navbar-toggleable-md fixed-top">
  <button class="navbar-toggler navbar-toggler-right" type="button" data-toggle="collapse" data-target="#navbarsExampleDefault" aria-controls="navbarsExampleDefault" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>

  <div class="collapse navbar-collapse container">
    <!-- Navbar navigation links -->
    <ul class="navbar-nav mr-auto">
      <li class="nav-item active">
        <a class="nav-link" href="#"><i class="octicon octicon-home" aria-hidden="true"></i> Home <span class="sr-only">(current)</span></a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#"><i class="octicon octicon-zap"></i> Moments</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#"><i class="octicon octicon-bell"></i> Notifications</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#"><i class="octicon octicon-inbox"></i> Messages</a>
      </li>
    </ul>
    <!-- END: Navbar navigation links -->
    <!-- Navbar Search form -->
    <form class="navbar-form" role="search">
      <div class="input-group">
        <input type="text" class="form-control input-search" placeholder="Search Twitter" name="srch-term" id="srch-term">
        <div class="input-group-btn">
          <button class="btn btn-default btn-search" type="submit"><i class="octicon octicon-search navbar-search-icon"></i></button>
        </div>
      </div>
    </form>
    <!-- END: Navbar Search form -->
    <!-- Navbar User menu -->
    <div class="dropdown navbar-user-dropdown">
      <button class="btn btn-secondary dropdown-toggle btn-circle" type="button" id="dropdownMenuButton" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false"></button>
      <div class="dropdown-menu" aria-labelledby="dropdownMenuButton">
        <a class="dropdown-item" href="#">Action</a>
        <a class="dropdown-item" href="#">Another action</a>
        <a class="dropdown-item" href="#">Something else here</a>
      </div>
    </div>
    <!-- END: Navbar User menu -->
    <!-- Navbar Tweet button -->
    <button class="btn btn-search-bar">Tweet</button>
  </div>
</nav>
<!-- END: Fixed top navbar -->
<div class="main-container">
  <div class="row profile-background">
    <div class="container">
      <div class="avatar-container">
        <div class="avatar">

        </div>
      </div>
    </div>
  </div>

  <nav class="navbar profile-stats">
    <div class="container">
      <div class="row">
        <div class="col">

        </div>
        <div class="col-6">
          <ul>
            <li class="profile-stats-item-active">
              <a>
                <span class="profile-stats-item profile-stats-item-label">Tweets</span>
                <span class="profile-stats-item profile-stats-item-number">51</span>
              </a>
            </li>
            <li>
              <a>
                <span class="profile-stats-item profile-stats-item-label">Following</span>
                <span class="profile-stats-item profile-stats-item-number">420</span>
              </a>
            </li>
            <li>
              <a>
                <span class="profile-stats-item profile-stats-item-label">Followers</span>
                <span class="profile-stats-item profile-stats-item-number">583</span>
              </a>
            </li>
            <li>
              <a>
                <span class="profile-stats-item profile-stats-item-label">Likes</span>
                <span class="profile-stats-item profile-stats-item-number">241</span>
              </a>
            </li>
          </ul>
        </div>
        <div class="col">

        </div>
      </div>
    </div>
  </nav>
  <div class="container main-content">
    <div class="row">
      <div class="col profile-col">
        <!-- Left column -->
        <div class="profile-header">
          <!-- Header information -->
          <h3 class="profile-fullname"><a>Jon Vadillo<a></h3>
          <h2 class="profile-element"><a>@jonvadillo</a></h2>
          <a class="profile-element profile-website" hrerf=""><i class="octicon octicon-link"></i>&nbsp;jonvadillo.com</a>
          <a class="profile-element profile-website" hrerf=""><i class="octicon octicon-location"></i>&nbsp;Vitoria-Gasteiz, Spain</a>
          <h2 class="profile-element"><i class="octicon octicon-calendar"></i>Joined November 2012</h2>
          <button class="btn btn-search-bar tweet-to-btn">Tweet to Jon Vadillo</button>
          <a class="profile-element profile-website" hrerf=""><i class="octicon octicon-file-media"></i>1,142 Photos and videos</a>
          <div class="pic-grid">
            <!-- Image grid -->
            <div class="row">
              <div class="col pic-col"><img src="https://pbs.twimg.com/media/DFCq7iTXkAADXE-.jpg:thumb" height="73px" class=""></div>
              <div class="col pic-col"><img src="https://pbs.twimg.com/media/DEoQ0vyXoBA1cwQ.png:thumb" height="73px" class=""></div>
              <div class="col pic-col"><img src="https://pbs.twimg.com/media/DDVbW4RXsAAasuw.jpg:thumb" height="73px" class=""></div>
            </div>
            <!-- End: row -->
            <div class="row">
              <div class="col pic-col"><img src="https://pbs.twimg.com/media/DFCq7iTXkAADXE-.jpg:thumb" height="73px" class=""></div>
              <div class="col pic-col"><img src="https://pbs.twimg.com/media/DEoQ0vyXoBA1cwQ.png:thumb" height="73px" class=""></div>
              <div class="col pic-col"><img src="https://pbs.twimg.com/media/DDVbW4RXsAAasuw.jpg:thumb" height="73px" class=""></div>
            </div>
            <!-- End: row -->
          </div>
          <!-- End: image grid -->
        </div>
      </div>
      <!-- End; Left column -->
      <!-- Center content column -->
      <div class="col-6">
        <ol class="tweet-list">
          <li class="tweet-card">
            <div class="tweet-content">
              <div class="tweet-header">
                <span class="fullname">
                  <strong>Jon Vadillo</strong>
                </span>
                <span class="username">@JonVadillo</span>
                <span class="tweet-time">- Jul 18</span>
              </div>
              <a>
                <img class="tweet-card-avatar" src="https://pbs.twimg.com/profile_images/679974972278849537/bzzb-6H4_bigger.jpg" alt="">
              </a>
              <div class="tweet-text">
                <p class="" lang="es" data-aria-label-part="0">¡Nuevo artículo en Mozilla!<br>Resuelto: Corregido – Una breve historia sobre un error reportado por la comunidad <a href="https://t.co/dqg5hVQXA0" class="twitter-timeline-link" target="_blank"><span class="">https://www.mozilla-hispano.org/</span></a>                  <a href="" class="twitter-hashtag"><s>#</s><b>firefox</b></a> <a href="" class="twitter-hashtag"><s>#</s><b>comunidad</b></a>
                  <a href="" class="twitter-hashtag" dir="ltr"></a>
                </p>
              </div>
              <div class="tweet-footer">
                <a class="tweet-footer-btn">
                  <i class="octicon octicon-comment" aria-hidden="true"></i><span> 18</span>
                </a>
                <a class="tweet-footer-btn">
                  <i class="octicon octicon-sync" aria-hidden="true"></i><span> 64</span>
                </a>
                <a class="tweet-footer-btn">
                  <i class="octicon octicon-heart" aria-hidden="true"></i><span> 202</span>
                </a>
                <a class="tweet-footer-btn">
                  <i class="octicon octicon-mail" aria-hidden="true"></i><span> 155</span>
                </a>
              </div>
            </div>
          </li>
          <li class="tweet-card">
            <div class="tweet-content">
              <div class="tweet-header">
                <span class="fullname">
                  <strong>Jon Vadillo</strong>
                </span>
                <span class="username">@JonVadillo</span>
                <span class="tweet-time">- Jul 18</span>
              </div>
              <a>
                <img class="tweet-card-avatar" src="https://pbs.twimg.com/profile_images/679974972278849537/bzzb-6H4_bigger.jpg" alt="">
              </a>
              <div class="tweet-text">
                <p class="" lang="es" data-aria-label-part="0">¡Nuevo artículo en Mozilla!<br>Resuelto: Corregido – Una breve historia sobre un error reportado por la comunidad <a href="https://t.co/dqg5hVQXA0" class="twitter-timeline-link" target="_blank"><span class="">https://www.mozilla-hispano.org/</span></a>                  <a href="" class="twitter-hashtag"><s>#</s><b>firefox</b></a> <a href="" class="twitter-hashtag"><s>#</s><b>comunidad</b></a>
                  <a href="" class="twitter-hashtag" dir="ltr"></a>
                </p>
              </div>
              <div class="tweet-footer">
                <a class="tweet-footer-btn">
                  <i class="octicon octicon-comment" aria-hidden="true"></i><span> 18</span>
                </a>
                <a class="tweet-footer-btn">
                  <i class="octicon octicon-sync" aria-hidden="true"></i><span> 64</span>
                </a>
                <a class="tweet-footer-btn">
                  <i class="octicon octicon-heart" aria-hidden="true"></i><span> 202</span>
                </a>
                <a class="tweet-footer-btn">
                  <i class="octicon octicon-mail" aria-hidden="true"></i><span> 155</span>
                </a>
              </div>
            </div>
          </li>
          <li class="tweet-card">
            <div class="tweet-content">
              <div class="tweet-header">
                <span class="fullname">
                  <strong>Jon Vadillo</strong>
                </span>
                <span class="username">@JonVadillo</span>
                <span class="tweet-time">- Jul 18</span>
              </div>
              <a>
                <img class="tweet-card-avatar" src="https://pbs.twimg.com/profile_images/679974972278849537/bzzb-6H4_bigger.jpg" alt="">
              </a>
              <div class="tweet-text">
                <p class="" lang="es" data-aria-label-part="0">¡Nuevo artículo en Mozilla!<br>Resuelto: Corregido – Una breve historia sobre un error reportado por la comunidad <a href="https://t.co/dqg5hVQXA0" class="twitter-timeline-link" target="_blank"><span class="">https://www.mozilla-hispano.org/</span></a>                  <a href="" class="twitter-hashtag"><s>#</s><b>firefox</b></a> <a href="" class="twitter-hashtag"><s>#</s><b>comunidad</b></a>
                  <a href="" class="twitter-hashtag" dir="ltr"></a>
                </p>
              </div>
              <div class="tweet-footer">
                <a class="tweet-footer-btn">
                  <i class="octicon octicon-comment" aria-hidden="true"></i><span> 18</span>
                </a>
                <a class="tweet-footer-btn">
                  <i class="octicon octicon-sync" aria-hidden="true"></i><span> 64</span>
                </a>
                <a class="tweet-footer-btn">
                  <i class="octicon octicon-heart" aria-hidden="true"></i><span> 202</span>
                </a>
                <a class="tweet-footer-btn">
                  <i class="octicon octicon-mail" aria-hidden="true"></i><span> 155</span>
                </a>
              </div>
            </div>
          </li>
          <li class="tweet-card">
            <div class="tweet-content">
              <div class="tweet-header">
                <span class="fullname">
                  <strong>Jon Vadillo</strong>
                </span>
                <span class="username">@JonVadillo</span>
                <span class="tweet-time">- Jul 18</span>
              </div>
              <a>
                <img class="tweet-card-avatar" src="https://pbs.twimg.com/profile_images/679974972278849537/bzzb-6H4_bigger.jpg" alt="">
              </a>
              <div class="tweet-text">
                <p class="" lang="es" data-aria-label-part="0">¡Nuevo artículo en Mozilla!<br>Resuelto: Corregido – Una breve historia sobre un error reportado por la comunidad <a href="https://t.co/dqg5hVQXA0" class="twitter-timeline-link" target="_blank"><span class="">https://www.mozilla-hispano.org/</span></a>                  <a href="" class="twitter-hashtag"><s>#</s><b>firefox</b></a> <a href="" class="twitter-hashtag"><s>#</s><b>comunidad</b></a>
                  <a href="" class="twitter-hashtag" dir="ltr"></a>
                </p>
              </div>
              <div class="tweet-footer">
                <a class="tweet-footer-btn">
                  <i class="octicon octicon-comment" aria-hidden="true"></i><span> 18</span>
                </a>
                <a class="tweet-footer-btn">
                  <i class="octicon octicon-sync" aria-hidden="true"></i><span> 64</span>
                </a>
                <a class="tweet-footer-btn">
                  <i class="octicon octicon-heart" aria-hidden="true"></i><span> 202</span>
                </a>
                <a class="tweet-footer-btn">
                  <i class="octicon octicon-mail" aria-hidden="true"></i><span> 155</span>
                </a>
              </div>
            </div>
          </li>
          <li class="tweet-card">
            <div class="tweet-content">
              <div class="tweet-header">
                <span class="fullname">
                  <strong>Jon Vadillo</strong>
                </span>
                <span class="username">@JonVadillo</span>
                <span class="tweet-time">- Jul 18</span>
              </div>
              <a>
                <img class="tweet-card-avatar" src="https://pbs.twimg.com/profile_images/679974972278849537/bzzb-6H4_bigger.jpg" alt="">
              </a>
              <div class="tweet-text">
                <p class="" lang="es" data-aria-label-part="0">¡Nuevo artículo en Mozilla!<br>Resuelto: Corregido – Una breve historia sobre un error reportado por la comunidad <a href="https://t.co/dqg5hVQXA0" class="twitter-timeline-link" target="_blank"><span class="">https://www.mozilla-hispano.org/</span></a>                  <a href="" class="twitter-hashtag"><s>#</s><b>firefox</b></a> <a href="" class="twitter-hashtag"><s>#</s><b>comunidad</b></a>
                  <a href="" class="twitter-hashtag" dir="ltr"></a>
                </p>
              </div>
              <div class="tweet-footer">
                <a class="tweet-footer-btn">
                  <i class="octicon octicon-comment" aria-hidden="true"></i><span> 18</span>
                </a>
                <a class="tweet-footer-btn">
                  <i class="octicon octicon-sync" aria-hidden="true"></i><span> 64</span>
                </a>
                <a class="tweet-footer-btn">
                  <i class="octicon octicon-heart" aria-hidden="true"></i><span> 202</span>
                </a>
                <a class="tweet-footer-btn">
                  <i class="octicon octicon-mail" aria-hidden="true"></i><span> 155</span>
                </a>
              </div>
            </div>
          </li>
        </ol>
        <!-- End: tweet list -->
      </div>
      <!-- End: Center content column -->
      <div class="col right-col">
        <div class="content-panel">
          <div class="panel-header">
            <h4>Who to follow</h4><small><a href="">Refresh</a></small><small><a href="">View all</a></small>
          </div>
          <!-- Who to Follow panel -->
          <div class="panel-content">
            <!--Follow list -->
            <ol class="tweet-list">
              <li class="tweet-card">
                <div class="tweet-content">
                  <img class="tweet-card-avatar" src="https://pbs.twimg.com/profile_images/679974972278849537/bzzb-6H4_bigger.jpg" alt="">
                  <div class="tweet-header">
                    <span class="fullname">
                  <strong>Jon Vadillo</strong>
                </span>
                    <span class="username">@JonVadillo</span>
                  </div>

                  <button class="btn btn-follow">Follow</button>
                </div>
              </li>
              <li class="tweet-card">
                <div class="tweet-content">
                  <img class="tweet-card-avatar" src="https://pbs.twimg.com/profile_images/679974972278849537/bzzb-6H4_bigger.jpg" alt="">
                  <div class="tweet-header">
                    <span class="fullname">
                  <strong>Jon Vadillo</strong>
                </span>
                    <span class="username">@JonVadillo</span>
                  </div>

                  <button class="btn btn-follow">Follow</button>
                </div>
              </li>
              <li class="tweet-card">
                <div class="tweet-content">
                  <img class="tweet-card-avatar" src="https://pbs.twimg.com/profile_images/679974972278849537/bzzb-6H4_bigger.jpg" alt="">
                  <div class="tweet-header">
                    <span class="fullname">
                  <strong>Jon Vadillo</strong>
                </span>
                    <span class="username">@JonVadillo</span>
                  </div>

                  <button class="btn btn-follow">Follow</button>
                </div>
              </li>
            </ol>
            <!--END: Follow list -->
          </div>
        </div>
      </div>
    </div>
  </div>

css

body {
  background-color: #e6ecf0;
  padding-top: 54px;
}

a {
  color: #1DA1F2;
}

@media screen and (min-width: 1236px) {
  .container {
    width: 1190px;
  }
}
/* Top Navbar elements' styles */
.navbar {
  background-color: #fff;
  border-bottom: 1px solid rgba(0, 0, 0, 0.15);
}
.navbar-nav > li a {
  color: #66757f;
  font-size: 14px;
  font-weight: bold;
}

.input-search {
  font-size: 13px;
}

.input-search, .btn-search {
  background-color: #f5f8fa;
  border-radius: 21px;
  border: 1px solid #e6ecf0;
}
.btn-search {
  background-color: #fff;
}

.navbar-search-icon {
  color: #66757f;
}

.btn-circle {
  border-radius: 50%;
  width: 40px;
  height: 40px;
  background-image: url(https://pbs.twimg.com/profile_images/679974972278849537/bzzb-6H4_normal.jpg);
}

.btn-search-bar {
  border-radius: 100px;
  border: 1px solid #1da1f2;
  color: #fff;
  background-color: #4AB3F4;
  border-color: transparent;
  font-weight: bold;
  font-size: 14px;
}

.btn-search-bar:hover{
      background-color: #1DA1F2;
    border-color: #1DA1F2;
  cursor:pointer;
}

.navbar-form {
  margin-right: 15px;
}

.navbar-user-dropdown {
  margin-right: 15px;
}
/* END: Top Navbar elements' styles */

.profile-background {
  height: 320px;
  background-image: url('https://pbs.twimg.com/profile_banners/439335622/1496682615/1500x500');
}

/* Main avatar */
.avatar-container {
  bottom: -87px;
  left: 10px;
  position: absolute;
  transition: bottom .3s;
  z-index: 3;
}

.avatar {
  background: #fff;
  background-image: url(https://pbs.twimg.com/profile_images/679974972278849537/bzzb-6H4_400x400.jpg);
  background-size: cover;
  border: 5px solid #fff;
  border-radius: 50%;
  height: 200px;
  position: relative;
  width: 200px;
}
/* END: Main avatar */

/* Stats Navbar elements' styles */
.profile-stats {
  background-color: #fff;
  padding-top: 0;
  padding-bottom: 0;
}

.profile-stats ul {
  margin: 0;
  list-style: none;
  padding: 0;
}

.profile-stats li {
  display: inline-block;
}

.profile-stats a {
  padding: 10px 16px;
  display: block;
  text-align: center;
}

.profile-stats-item {
  color: #657786;
  display: block;
}

.profile-stats-item-active {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-color: #1DA1F2 !important;
}

.profile-stats-item-label {
  font-size: 12px;
  font-weight: bold;
}

.profile-stats-item-number {
  font-size: 18px;
  font-weight: bold;
}

/* END: Stats Navbar elements' styles */

/* Main content elements' styles */

/* Left column*/
.profile-header {
  margin-top: 35px;
  padding-right: 15px;
  padding-left: 15px;
}

.profile-element {
  color: #657786;
  display: block;
  font-size: 14px;
  margin-top: 12px;
}
.profile-fullname {
  color: #000;
}

.profile-website {
  color: #1DA1F2 !important;
  cursor: pointer;
}

.profile-website:hover {
  text-decoration: underline !important;
}

.tweet-to-btn {
  margin-top: 16px;
  margin-bottom: 16px;
  width:100%;
}
/* END: Left column*/

/* Main column*/
.main-content {
}

.tweet-list {
  list-style: none;
  margin: 8px 4px 0;
  padding: 0;
}
.tweet-card {
  background-color: #fff;
  border-bottom: 1px solid #e6ecf0;
  min-height: 52px;
  padding: 9px 12px;
}

.tweet-content {
  margin-left: 58px;
  font-size: 14px;
  line-height: 20px;
  font-weight: normal;
}
.tweet-card-avatar {
  border-radius: 50%;
  height: 48px;
  width: 48px;
  float: left;
  margin-top: 3px;
  margin-left: -58px;
}

.tweet-footer-btn {
  margin-right: 30px;
}
.tweet-footer-btn i, .tweet-footer-btn span {
  color: #657786;
  font-size: 16px;
}
.tweet-footer-btn span {
  margin-left: 8px;
}
/* END Main column*/

/* Right column*/
.pic-col {
  margin: 2px;
  padding: 2px;
}

.right-col {
  padding-left: 0;
}
.content-panel {
  margin: 10px 0 0;
  background-color: #fff;
  line-height: 16px;
  padding: 15px;
}

.content-panel h4 {
  display: inline-block;
}

.content-panel small {
  font-size: 66%;
  margin-left: 6px;
}

.content-panel li {
  min-height: 70px;
}

.btn-follow {
  border-color: #1DA1F2;
  color: #1DA1F2;
  background-color: #fff;
  border: 1px solid #1da1f2;
  display: block;
  font-size: 12px;
  line-height: 16px;
  padding: 4px 12px;
  border-radius: 100px;
  box-shadow: none;
  cursor: pointer;
  font-weight: bold;
  text-align: center;
  min-width: 89px;
}

.btn-follow:hover {
  background-color: #E8F5FD;
}
/* END: Right column*/

/* END: Main content elements' styles */
