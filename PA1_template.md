



<!DOCTYPE html>
<html lang="en" class=" is-copy-enabled is-u2f-enabled">
  <head prefix="og: http://ogp.me/ns# fb: http://ogp.me/ns/fb# object: http://ogp.me/ns/object# article: http://ogp.me/ns/article# profile: http://ogp.me/ns/profile#">
    <meta charset='utf-8'>
    

    <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/frameworks-f06bc73a54aace421e06cbe6f22439a8d202499f5a90f5a7ce5a2293a4c43637.css" integrity="sha256-8GvHOlSqzkIeBsvm8iQ5qNICSZ9akPWnzloik6TENjc=" media="all" rel="stylesheet" />
    <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/github-6a520940318606f1f12f9e35d6d6ce2aab3330373b3963b7c1740248adc4c28a.css" integrity="sha256-alIJQDGGBvHxL5411tbOKqszMDc7OWO3wXQCSK3Ewoo=" media="all" rel="stylesheet" />
    
    
    
    

    <link as="script" href="https://assets-cdn.github.com/assets/frameworks-952d14ac162c6f6f327175882f6b1a4645bf7aadc9b36ccd52d50fc6f34c8568.js" rel="preload" />
    
    <link as="script" href="https://assets-cdn.github.com/assets/github-3a5e3e4545c7e854b0e62b1a23353a46965d0e3264b19b3b4f775ff66dc9689a.js" rel="preload" />

    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta http-equiv="Content-Language" content="en">
    <meta name="viewport" content="width=device-width">
    
    <title>coursera-repdata/PA1_template.md at master · sefakilic/coursera-repdata</title>
    <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub">
    <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub">
    <link rel="apple-touch-icon" href="/apple-touch-icon.png">
    <link rel="apple-touch-icon" sizes="57x57" href="/apple-touch-icon-57x57.png">
    <link rel="apple-touch-icon" sizes="60x60" href="/apple-touch-icon-60x60.png">
    <link rel="apple-touch-icon" sizes="72x72" href="/apple-touch-icon-72x72.png">
    <link rel="apple-touch-icon" sizes="76x76" href="/apple-touch-icon-76x76.png">
    <link rel="apple-touch-icon" sizes="114x114" href="/apple-touch-icon-114x114.png">
    <link rel="apple-touch-icon" sizes="120x120" href="/apple-touch-icon-120x120.png">
    <link rel="apple-touch-icon" sizes="144x144" href="/apple-touch-icon-144x144.png">
    <link rel="apple-touch-icon" sizes="152x152" href="/apple-touch-icon-152x152.png">
    <link rel="apple-touch-icon" sizes="180x180" href="/apple-touch-icon-180x180.png">
    <meta property="fb:app_id" content="1401488693436528">

      <meta content="https://avatars1.githubusercontent.com/u/1227083?v=3&amp;s=400" name="twitter:image:src" /><meta content="@github" name="twitter:site" /><meta content="summary" name="twitter:card" /><meta content="sefakilic/coursera-repdata" name="twitter:title" /><meta content="coursera-repdata - Peer Assessment 1 for Reproducible Research" name="twitter:description" />
      <meta content="https://avatars1.githubusercontent.com/u/1227083?v=3&amp;s=400" property="og:image" /><meta content="GitHub" property="og:site_name" /><meta content="object" property="og:type" /><meta content="sefakilic/coursera-repdata" property="og:title" /><meta content="https://github.com/sefakilic/coursera-repdata" property="og:url" /><meta content="coursera-repdata - Peer Assessment 1 for Reproducible Research" property="og:description" />
      <meta name="browser-stats-url" content="https://api.github.com/_private/browser/stats">
    <meta name="browser-errors-url" content="https://api.github.com/_private/browser/errors">
    <link rel="assets" href="https://assets-cdn.github.com/">
    <link rel="web-socket" href="wss://live.github.com/_sockets/MTkzNjgwMTE6NmVjZmM1NTU3YjJlZWM1YjZjMDAzOGM3MmM2NzRhMTc6Y2ViMWNiZGIxYjNkZGI3Nzg2ZWI3ZTQ2Nzc3ZWZhZjQ0MWQ3OTFhOTgyOGRjODk1YWY1NGU3OWQ3OWVmMjdkMA==--adb84b3ea0c726a8d08d62b844925011f49aa225">
    <meta name="pjax-timeout" content="1000">
    <link rel="sudo-modal" href="/sessions/sudo_modal">

    <meta name="msapplication-TileImage" content="/windows-tile.png">
    <meta name="msapplication-TileColor" content="#ffffff">
    <meta name="selected-link" value="repo_source" data-pjax-transient>

    <meta name="google-site-verification" content="KT5gs8h0wvaagLKAVWq8bbeNwnZZK1r1XQysX3xurLU">
<meta name="google-site-verification" content="ZzhVyEFwb7w3e0-uOTltm8Jsck2F5StVihD0exw2fsA">
    <meta name="google-analytics" content="UA-3769691-2">

<meta content="collector.githubapp.com" name="octolytics-host" /><meta content="github" name="octolytics-app-id" /><meta content="CA3BE73D:6CA4:AB3BF18:57A2FCEC" name="octolytics-dimension-request_id" /><meta content="19368011" name="octolytics-actor-id" /><meta content="anuragnagaich" name="octolytics-actor-login" /><meta content="528915d4755387a0f816342d6785e0fcf88df8ce1ec13217dc018c49dec768be" name="octolytics-actor-hash" />
<meta content="/&lt;user-name&gt;/&lt;repo-name&gt;/blob/show" data-pjax-transient="true" name="analytics-location" />



  <meta class="js-ga-set" name="dimension1" content="Logged In">



        <meta name="hostname" content="github.com">
    <meta name="user-login" content="anuragnagaich">

        <meta name="expected-hostname" content="github.com">
      <meta name="js-proxy-site-detection-payload" content="YWJhMDA4MTdhNDVjOWIwY2FiZGFiYzA2MWYwNWM5YThhNGU0MTNjOGJiNzMxNWMyYzMwNmRkM2ZiODM2ZWY0Ynx7InJlbW90ZV9hZGRyZXNzIjoiMjAyLjU5LjIzMS42MSIsInJlcXVlc3RfaWQiOiJDQTNCRTczRDo2Q0E0OkFCM0JGMTg6NTdBMkZDRUMiLCJ0aW1lc3RhbXAiOjE0NzAyOTkzNzh9">


      <link rel="mask-icon" href="https://assets-cdn.github.com/pinned-octocat.svg" color="#4078c0">
      <link rel="icon" type="image/x-icon" href="https://assets-cdn.github.com/favicon.ico">

    <meta name="html-safe-nonce" content="d12cd1e3efb4189234a88f2f401ece2b9f93c8d6">
    <meta content="c20406b7487cf93f3c8cb059b6c353a468d7aa1f" name="form-nonce" />

    <meta http-equiv="x-pjax-version" content="b4e59d67217e844deb4e18e89b24fd1d">
    

      
  <meta name="description" content="coursera-repdata - Peer Assessment 1 for Reproducible Research">
  <meta name="go-import" content="github.com/sefakilic/coursera-repdata git https://github.com/sefakilic/coursera-repdata.git">

  <meta content="1227083" name="octolytics-dimension-user_id" /><meta content="sefakilic" name="octolytics-dimension-user_login" /><meta content="19899531" name="octolytics-dimension-repository_id" /><meta content="sefakilic/coursera-repdata" name="octolytics-dimension-repository_nwo" /><meta content="true" name="octolytics-dimension-repository_public" /><meta content="true" name="octolytics-dimension-repository_is_fork" /><meta content="16709733" name="octolytics-dimension-repository_parent_id" /><meta content="rdpeng/RepData_PeerAssessment1" name="octolytics-dimension-repository_parent_nwo" /><meta content="16709733" name="octolytics-dimension-repository_network_root_id" /><meta content="rdpeng/RepData_PeerAssessment1" name="octolytics-dimension-repository_network_root_nwo" />
  <link href="https://github.com/sefakilic/coursera-repdata/commits/master.atom" rel="alternate" title="Recent Commits to coursera-repdata:master" type="application/atom+xml">


      <link rel="canonical" href="https://github.com/sefakilic/coursera-repdata/blob/master/project1/PA1_template.md" data-pjax-transient>
  </head>


  <body class="logged-in  env-production windows vis-public fork page-blob">
    <div id="js-pjax-loader-bar" class="pjax-loader-bar"></div>
    <a href="#start-of-content" tabindex="1" class="accessibility-aid js-skip-to-content">Skip to content</a>

    
    
    



        <div class="header header-logged-in true" role="banner">
  <div class="container clearfix">

    <a class="header-logo-invertocat" href="https://github.com/" data-hotkey="g d" aria-label="Homepage" data-ga-click="Header, go to dashboard, icon:logo">
  <svg aria-hidden="true" class="octicon octicon-mark-github" height="28" version="1.1" viewBox="0 0 16 16" width="28"><path d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0 0 16 8c0-4.42-3.58-8-8-8z"></path></svg>
</a>


        <div class="header-search scoped-search site-scoped-search js-site-search" role="search">
  <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/sefakilic/coursera-repdata/search" class="js-site-search-form" data-scoped-search-url="/sefakilic/coursera-repdata/search" data-unscoped-search-url="/search" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
    <label class="form-control header-search-wrapper js-chromeless-input-container">
      <div class="header-search-scope">This repository</div>
      <input type="text"
        class="form-control header-search-input js-site-search-focus js-site-search-field is-clearable"
        data-hotkey="s"
        name="q"
        placeholder="Search"
        aria-label="Search this repository"
        data-unscoped-placeholder="Search GitHub"
        data-scoped-placeholder="Search"
        autocapitalize="off">
    </label>
</form></div>


      <ul class="header-nav left" role="navigation">
        <li class="header-nav-item">
          <a href="/pulls" class="js-selected-navigation-item header-nav-link" data-ga-click="Header, click, Nav menu - item:pulls context:user" data-hotkey="g p" data-selected-links="/pulls /pulls/assigned /pulls/mentioned /pulls">
            Pull requests
</a>        </li>
        <li class="header-nav-item">
          <a href="/issues" class="js-selected-navigation-item header-nav-link" data-ga-click="Header, click, Nav menu - item:issues context:user" data-hotkey="g i" data-selected-links="/issues /issues/assigned /issues/mentioned /issues">
            Issues
</a>        </li>
          <li class="header-nav-item">
            <a class="header-nav-link" href="https://gist.github.com/" data-ga-click="Header, go to gist, text:gist">Gist</a>
          </li>
      </ul>

    
<ul class="header-nav user-nav right" id="user-links">
  <li class="header-nav-item">
    

  </li>

  <li class="header-nav-item dropdown js-menu-container">
    <a class="header-nav-link tooltipped tooltipped-s js-menu-target" href="/new"
       aria-label="Create new…"
       data-ga-click="Header, create new, icon:add">
      <svg aria-hidden="true" class="octicon octicon-plus left" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M12 9H7v5H5V9H0V7h5V2h2v5h5z"></path></svg>
      <span class="dropdown-caret"></span>
    </a>

    <div class="dropdown-menu-content js-menu-content">
      <ul class="dropdown-menu dropdown-menu-sw">
        
<a class="dropdown-item" href="/new" data-ga-click="Header, create new repository">
  New repository
</a>

  <a class="dropdown-item" href="/new/import" data-ga-click="Header, import a repository">
    Import repository
  </a>


  <a class="dropdown-item" href="/organizations/new" data-ga-click="Header, create new organization">
    New organization
  </a>




      </ul>
    </div>
  </li>

  <li class="header-nav-item dropdown js-menu-container">
    <a class="header-nav-link name tooltipped tooltipped-sw js-menu-target" href="/anuragnagaich"
       aria-label="View profile and more"
       data-ga-click="Header, show menu, icon:avatar">
      <img alt="@anuragnagaich" class="avatar" height="20" src="https://avatars3.githubusercontent.com/u/19368011?v=3&amp;s=40" width="20" />
      <span class="dropdown-caret"></span>
    </a>

    <div class="dropdown-menu-content js-menu-content">
      <div class="dropdown-menu dropdown-menu-sw">
        <div class="dropdown-header header-nav-current-user css-truncate">
          Signed in as <strong class="css-truncate-target">anuragnagaich</strong>
        </div>

        <div class="dropdown-divider"></div>

        <a class="dropdown-item" href="/anuragnagaich" data-ga-click="Header, go to profile, text:your profile">
          Your profile
        </a>
        <a class="dropdown-item" href="/stars" data-ga-click="Header, go to starred repos, text:your stars">
          Your stars
        </a>
        <a class="dropdown-item" href="/explore" data-ga-click="Header, go to explore, text:explore">
          Explore
        </a>
          <a class="dropdown-item" href="/integrations" data-ga-click="Header, go to integrations, text:integrations">
            Integrations
          </a>
        <a class="dropdown-item" href="https://help.github.com" data-ga-click="Header, go to help, text:help">
          Help
        </a>


        <div class="dropdown-divider"></div>

        <a class="dropdown-item" href="/settings/profile" data-ga-click="Header, go to settings, icon:settings">
          Settings
        </a>

        <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/logout" class="logout-form" data-form-nonce="c20406b7487cf93f3c8cb059b6c353a468d7aa1f" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="htytJ+YlZEi5jPc6ffDzjFE78bWaZE9nY8vwk4/BB/rhr/d4FifNvsNunS4mHxEkyVX0/9ytKEjKQHm0687G5w==" /></div>
          <button class="dropdown-item dropdown-signout" data-ga-click="Header, sign out, icon:logout">
            Sign out
          </button>
</form>      </div>
    </div>
  </li>
</ul>


    
  </div>
</div>


      


    <div id="start-of-content" class="accessibility-aid"></div>

      <div id="js-flash-container">
</div>


    <div role="main">
        <div itemscope itemtype="http://schema.org/SoftwareSourceCode">
    <div id="js-repo-pjax-container" data-pjax-container>
      
<div class="pagehead repohead instapaper_ignore readability-menu experiment-repo-nav">
  <div class="container repohead-details-container">

    

<ul class="pagehead-actions">

  <li>
        <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/notifications/subscribe" class="js-social-container" data-autosubmit="true" data-form-nonce="c20406b7487cf93f3c8cb059b6c353a468d7aa1f" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="gOBWB6m5yj6ZPuJe1Wx16rtjrxyWdAxNh5+mFYAMXQOyxmeLXoxSOJ+Lnqg5/9wbxAU64Z+nqbbFUtADZehZ/g==" /></div>      <input class="form-control" id="repository_id" name="repository_id" type="hidden" value="19899531" />

        <div class="select-menu js-menu-container js-select-menu">
          <a href="/sefakilic/coursera-repdata/subscription"
            class="btn btn-sm btn-with-count select-menu-button js-menu-target" role="button" tabindex="0" aria-haspopup="true"
            data-ga-click="Repository, click Watch settings, action:blob#show">
            <span class="js-select-button">
              <svg aria-hidden="true" class="octicon octicon-eye" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"></path></svg>
              Watch
            </span>
          </a>
          <a class="social-count js-social-count" href="/sefakilic/coursera-repdata/watchers">
            3
          </a>

        <div class="select-menu-modal-holder">
          <div class="select-menu-modal subscription-menu-modal js-menu-content" aria-hidden="true">
            <div class="select-menu-header js-navigation-enable" tabindex="-1">
              <svg aria-label="Close" class="octicon octicon-x js-menu-close" height="16" role="img" version="1.1" viewBox="0 0 12 16" width="12"><path d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48z"></path></svg>
              <span class="select-menu-title">Notifications</span>
            </div>

              <div class="select-menu-list js-navigation-container" role="menu">

                <div class="select-menu-item js-navigation-item selected" role="menuitem" tabindex="0">
                  <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"></path></svg>
                  <div class="select-menu-item-text">
                    <input checked="checked" id="do_included" name="do" type="radio" value="included" />
                    <span class="select-menu-item-heading">Not watching</span>
                    <span class="description">Be notified when participating or @mentioned.</span>
                    <span class="js-select-button-text hidden-select-button-text">
                      <svg aria-hidden="true" class="octicon octicon-eye" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"></path></svg>
                      Watch
                    </span>
                  </div>
                </div>

                <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
                  <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"></path></svg>
                  <div class="select-menu-item-text">
                    <input id="do_subscribed" name="do" type="radio" value="subscribed" />
                    <span class="select-menu-item-heading">Watching</span>
                    <span class="description">Be notified of all conversations.</span>
                    <span class="js-select-button-text hidden-select-button-text">
                      <svg aria-hidden="true" class="octicon octicon-eye" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"></path></svg>
                      Unwatch
                    </span>
                  </div>
                </div>

                <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
                  <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"></path></svg>
                  <div class="select-menu-item-text">
                    <input id="do_ignore" name="do" type="radio" value="ignore" />
                    <span class="select-menu-item-heading">Ignoring</span>
                    <span class="description">Never be notified.</span>
                    <span class="js-select-button-text hidden-select-button-text">
                      <svg aria-hidden="true" class="octicon octicon-mute" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M8 2.81v10.38c0 .67-.81 1-1.28.53L3 10H1c-.55 0-1-.45-1-1V7c0-.55.45-1 1-1h2l3.72-3.72C7.19 1.81 8 2.14 8 2.81zm7.53 3.22l-1.06-1.06-1.97 1.97-1.97-1.97-1.06 1.06L11.44 8 9.47 9.97l1.06 1.06 1.97-1.97 1.97 1.97 1.06-1.06L13.56 8l1.97-1.97z"></path></svg>
                      Stop ignoring
                    </span>
                  </div>
                </div>

              </div>

            </div>
          </div>
        </div>
</form>
  </li>

  <li>
    
  <div class="js-toggler-container js-social-container starring-container ">

    <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/sefakilic/coursera-repdata/unstar" class="starred" data-form-nonce="c20406b7487cf93f3c8cb059b6c353a468d7aa1f" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="DeU41bgQqiw3UIm5DfoT8cPNUiUOs+ZxNdPCuukfVutVq+w6LcrHxsj4Aaa18RKVemGOZSH/4b6/dHSDGFvSeg==" /></div>
      <button
        class="btn btn-sm btn-with-count js-toggler-target"
        aria-label="Unstar this repository" title="Unstar sefakilic/coursera-repdata"
        data-ga-click="Repository, click unstar button, action:blob#show; text:Unstar">
        <svg aria-hidden="true" class="octicon octicon-star" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path d="M14 6l-4.9-.64L7 1 4.9 5.36 0 6l3.6 3.26L2.67 14 7 11.67 11.33 14l-.93-4.74z"></path></svg>
        Unstar
      </button>
        <a class="social-count js-social-count" href="/sefakilic/coursera-repdata/stargazers">
          2
        </a>
</form>
    <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/sefakilic/coursera-repdata/star" class="unstarred" data-form-nonce="c20406b7487cf93f3c8cb059b6c353a468d7aa1f" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="gqn+XAXAG6h8AoFnJnAqo9snSFJn213bERxTKaPhv31jO/OVXVtRMicdn0J00FB3+oSmImLvJlBOpYiwR7VlTg==" /></div>
      <button
        class="btn btn-sm btn-with-count js-toggler-target"
        aria-label="Star this repository" title="Star sefakilic/coursera-repdata"
        data-ga-click="Repository, click star button, action:blob#show; text:Star">
        <svg aria-hidden="true" class="octicon octicon-star" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path d="M14 6l-4.9-.64L7 1 4.9 5.36 0 6l3.6 3.26L2.67 14 7 11.67 11.33 14l-.93-4.74z"></path></svg>
        Star
      </button>
        <a class="social-count js-social-count" href="/sefakilic/coursera-repdata/stargazers">
          2
        </a>
</form>  </div>

  </li>

  <li>
          <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/sefakilic/coursera-repdata/fork" class="btn-with-count" data-form-nonce="c20406b7487cf93f3c8cb059b6c353a468d7aa1f" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="p5w00l8cMg7d/o66jCSK15ahMC5qBPBMlC8bPAeuWRZjqthCQgGndtS3eMEPZK2nR/xI+ZImlt3gCb6iqt+RmQ==" /></div>
            <button
                type="submit"
                class="btn btn-sm btn-with-count"
                data-ga-click="Repository, show fork modal, action:blob#show; text:Fork"
                title="Fork your own copy of sefakilic/coursera-repdata to your account"
                aria-label="Fork your own copy of sefakilic/coursera-repdata to your account">
              <svg aria-hidden="true" class="octicon octicon-repo-forked" height="16" version="1.1" viewBox="0 0 10 16" width="10"><path d="M8 1a1.993 1.993 0 0 0-1 3.72V6L5 8 3 6V4.72A1.993 1.993 0 0 0 2 1a1.993 1.993 0 0 0-1 3.72V6.5l3 3v1.78A1.993 1.993 0 0 0 5 15a1.993 1.993 0 0 0 1-3.72V9.5l3-3V4.72A1.993 1.993 0 0 0 8 1zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3 10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3-10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"></path></svg>
              Fork
            </button>
</form>
    <a href="/sefakilic/coursera-repdata/network" class="social-count">
      24,582
    </a>
  </li>
</ul>

    <h1 class="public ">
  <svg aria-hidden="true" class="octicon octicon-repo-forked" height="16" version="1.1" viewBox="0 0 10 16" width="10"><path d="M8 1a1.993 1.993 0 0 0-1 3.72V6L5 8 3 6V4.72A1.993 1.993 0 0 0 2 1a1.993 1.993 0 0 0-1 3.72V6.5l3 3v1.78A1.993 1.993 0 0 0 5 15a1.993 1.993 0 0 0 1-3.72V9.5l3-3V4.72A1.993 1.993 0 0 0 8 1zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3 10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3-10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"></path></svg>
  <span class="author" itemprop="author"><a href="/sefakilic" class="url fn" rel="author">sefakilic</a></span><!--
--><span class="path-divider">/</span><!--
--><strong itemprop="name"><a href="/sefakilic/coursera-repdata" data-pjax="#js-repo-pjax-container">coursera-repdata</a></strong>

    <span class="fork-flag">
      <span class="text">forked from <a href="/rdpeng/RepData_PeerAssessment1">rdpeng/RepData_PeerAssessment1</a></span>
    </span>
</h1>

  </div>
  <div class="container">
    
<nav class="reponav js-repo-nav js-sidenav-container-pjax"
     itemscope
     itemtype="http://schema.org/BreadcrumbList"
     role="navigation"
     data-pjax="#js-repo-pjax-container">

  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
    <a href="/sefakilic/coursera-repdata" aria-selected="true" class="js-selected-navigation-item selected reponav-item" data-hotkey="g c" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches /sefakilic/coursera-repdata" itemprop="url">
      <svg aria-hidden="true" class="octicon octicon-code" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path d="M9.5 3L8 4.5 11.5 8 8 11.5 9.5 13 14 8 9.5 3zm-5 0L0 8l4.5 5L6 11.5 2.5 8 6 4.5 4.5 3z"></path></svg>
      <span itemprop="name">Code</span>
      <meta itemprop="position" content="1">
</a>  </span>


  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
    <a href="/sefakilic/coursera-repdata/pulls" class="js-selected-navigation-item reponav-item" data-hotkey="g p" data-selected-links="repo_pulls /sefakilic/coursera-repdata/pulls" itemprop="url">
      <svg aria-hidden="true" class="octicon octicon-git-pull-request" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M11 11.28V5c-.03-.78-.34-1.47-.94-2.06C9.46 2.35 8.78 2.03 8 2H7V0L4 3l3 3V4h1c.27.02.48.11.69.31.21.2.3.42.31.69v6.28A1.993 1.993 0 0 0 10 15a1.993 1.993 0 0 0 1-3.72zm-1 2.92c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zM4 3c0-1.11-.89-2-2-2a1.993 1.993 0 0 0-1 3.72v6.56A1.993 1.993 0 0 0 2 15a1.993 1.993 0 0 0 1-3.72V4.72c.59-.34 1-.98 1-1.72zm-.8 10c0 .66-.55 1.2-1.2 1.2-.65 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"></path></svg>
      <span itemprop="name">Pull requests</span>
      <span class="counter">0</span>
      <meta itemprop="position" content="3">
</a>  </span>

    <a href="/sefakilic/coursera-repdata/wiki" class="js-selected-navigation-item reponav-item" data-hotkey="g w" data-selected-links="repo_wiki /sefakilic/coursera-repdata/wiki">
      <svg aria-hidden="true" class="octicon octicon-book" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M3 5h4v1H3V5zm0 3h4V7H3v1zm0 2h4V9H3v1zm11-5h-4v1h4V5zm0 2h-4v1h4V7zm0 2h-4v1h4V9zm2-6v9c0 .55-.45 1-1 1H9.5l-1 1-1-1H2c-.55 0-1-.45-1-1V3c0-.55.45-1 1-1h5.5l1 1 1-1H15c.55 0 1 .45 1 1zm-8 .5L7.5 3H2v9h6V3.5zm7-.5H9.5l-.5.5V12h6V3z"></path></svg>
      Wiki
</a>

  <a href="/sefakilic/coursera-repdata/pulse" class="js-selected-navigation-item reponav-item" data-selected-links="pulse /sefakilic/coursera-repdata/pulse">
    <svg aria-hidden="true" class="octicon octicon-pulse" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path d="M11.5 8L8.8 5.4 6.6 8.5 5.5 1.6 2.38 8H0v2h3.6l.9-1.8.9 5.4L9 8.5l1.6 1.5H14V8z"></path></svg>
    Pulse
</a>
  <a href="/sefakilic/coursera-repdata/graphs" class="js-selected-navigation-item reponav-item" data-selected-links="repo_graphs repo_contributors /sefakilic/coursera-repdata/graphs">
    <svg aria-hidden="true" class="octicon octicon-graph" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M16 14v1H0V0h1v14h15zM5 13H3V8h2v5zm4 0H7V3h2v10zm4 0h-2V6h2v7z"></path></svg>
    Graphs
</a>

</nav>

  </div>
</div>

<div class="container new-discussion-timeline experiment-repo-nav">
  <div class="repository-content">

    

<a href="/sefakilic/coursera-repdata/blob/887120ed7a37211dd2d2bdc05dbe0e81e0e1ae7d/project1/PA1_template.md" class="hidden js-permalink-shortcut" data-hotkey="y">Permalink</a>

<!-- blob contrib key: blob_contributors:v21:8a4aa3e01c1a68b226587289c2ddf6f0 -->

<div class="file-navigation js-zeroclipboard-container">
  
<div class="select-menu branch-select-menu js-menu-container js-select-menu left">
  <button class="btn btn-sm select-menu-button js-menu-target css-truncate" data-hotkey="w"
    title="master"
    type="button" aria-label="Switch branches or tags" tabindex="0" aria-haspopup="true">
    <i>Branch:</i>
    <span class="js-select-button css-truncate-target">master</span>
  </button>

  <div class="select-menu-modal-holder js-menu-content js-navigation-container" data-pjax aria-hidden="true">

    <div class="select-menu-modal">
      <div class="select-menu-header">
        <svg aria-label="Close" class="octicon octicon-x js-menu-close" height="16" role="img" version="1.1" viewBox="0 0 12 16" width="12"><path d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48z"></path></svg>
        <span class="select-menu-title">Switch branches/tags</span>
      </div>

      <div class="select-menu-filters">
        <div class="select-menu-text-filter">
          <input type="text" aria-label="Filter branches/tags" id="context-commitish-filter-field" class="form-control js-filterable-field js-navigation-enable" placeholder="Filter branches/tags">
        </div>
        <div class="select-menu-tabs">
          <ul>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="branches" data-filter-placeholder="Filter branches/tags" class="js-select-menu-tab" role="tab">Branches</a>
            </li>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="tags" data-filter-placeholder="Find a tag…" class="js-select-menu-tab" role="tab">Tags</a>
            </li>
          </ul>
        </div>
      </div>

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="branches" role="menu">

        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


            <a class="select-menu-item js-navigation-item js-navigation-open selected"
               href="/sefakilic/coursera-repdata/blob/master/project1/PA1_template.md"
               data-name="master"
               data-skip-pjax="true"
               rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"></path></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text" title="master">
                master
              </span>
            </a>
        </div>

          <div class="select-menu-no-results">Nothing to show</div>
      </div>

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="tags">
        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


        </div>

        <div class="select-menu-no-results">Nothing to show</div>
      </div>

    </div>
  </div>
</div>

  <div class="btn-group right">
    <a href="/sefakilic/coursera-repdata/find/master"
          class="js-pjax-capture-input btn btn-sm"
          data-pjax
          data-hotkey="t">
      Find file
    </a>
    <button aria-label="Copy file path to clipboard" class="js-zeroclipboard btn btn-sm zeroclipboard-button tooltipped tooltipped-s" data-copied-hint="Copied!" type="button">Copy path</button>
  </div>
  <div class="breadcrumb js-zeroclipboard-target">
    <span class="repo-root js-repo-root"><span class="js-path-segment"><a href="/sefakilic/coursera-repdata"><span>coursera-repdata</span></a></span></span><span class="separator">/</span><span class="js-path-segment"><a href="/sefakilic/coursera-repdata/tree/master/project1"><span>project1</span></a></span><span class="separator">/</span><strong class="final-path">PA1_template.md</strong>
  </div>
</div>


  <div class="commit-tease">
      <span class="right">
        <a class="commit-tease-sha" href="/sefakilic/coursera-repdata/commit/a294c1c2856357eb6f345902dd359b0814b386b0" data-pjax>
          a294c1c
        </a>
        <relative-time datetime="2014-05-18T15:05:57Z">May 18, 2014</relative-time>
      </span>
      <div>
        <img alt="@sefakilic" class="avatar" height="20" src="https://avatars0.githubusercontent.com/u/1227083?v=3&amp;s=40" width="20" />
        <a href="/sefakilic" class="user-mention" rel="author">sefakilic</a>
          <a href="/sefakilic/coursera-repdata/commit/a294c1c2856357eb6f345902dd359b0814b386b0" class="message" data-pjax="true" title="peer assessment 1">peer assessment 1</a>
      </div>

    <div class="commit-tease-contributors">
      <button type="button" class="btn-link muted-link contributors-toggle" data-facebox="#blob_contributors_box">
        <strong>1</strong>
         contributor
      </button>
      
    </div>

    <div id="blob_contributors_box" style="display:none">
      <h2 class="facebox-header" data-facebox-id="facebox-header">Users who have contributed to this file</h2>
      <ul class="facebox-user-list" data-facebox-id="facebox-description">
          <li class="facebox-user-list-item">
            <img alt="@sefakilic" height="24" src="https://avatars2.githubusercontent.com/u/1227083?v=3&amp;s=48" width="24" />
            <a href="/sefakilic">sefakilic</a>
          </li>
      </ul>
    </div>
  </div>

<div class="file">
  <div class="file-header">
  <div class="file-actions">

    <div class="btn-group">
      <a href="/sefakilic/coursera-repdata/raw/master/project1/PA1_template.md" class="btn btn-sm " id="raw-url">Raw</a>
        <a href="/sefakilic/coursera-repdata/blame/master/project1/PA1_template.md" class="btn btn-sm js-update-url-with-hash">Blame</a>
      <a href="/sefakilic/coursera-repdata/commits/master/project1/PA1_template.md" class="btn btn-sm " rel="nofollow">History</a>
    </div>

        <a class="btn-octicon tooltipped tooltipped-nw"
           href="github-windows://openRepo/https://github.com/sefakilic/coursera-repdata?branch=master&amp;filepath=project1%2FPA1_template.md"
           aria-label="Open this file in GitHub Desktop"
           data-ga-click="Repository, open with desktop, type:windows">
            <svg aria-hidden="true" class="octicon octicon-device-desktop" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M15 2H1c-.55 0-1 .45-1 1v9c0 .55.45 1 1 1h5.34c-.25.61-.86 1.39-2.34 2h8c-1.48-.61-2.09-1.39-2.34-2H15c.55 0 1-.45 1-1V3c0-.55-.45-1-1-1zm0 9H1V3h14v8z"></path></svg>
        </a>

        <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/sefakilic/coursera-repdata/edit/master/project1/PA1_template.md" class="inline-form js-update-url-with-hash" data-form-nonce="c20406b7487cf93f3c8cb059b6c353a468d7aa1f" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="rfFH2HSe/3nlv4X6UblYzeZejztBr7Iz6VbL9pikgKNO/xW+jl61sB/+NOZ2F77HjfGb+mBRuZe1eDFgIs7EYA==" /></div>
          <button class="btn-octicon tooltipped tooltipped-nw" type="submit"
            aria-label="Edit the file in your fork of this project" data-hotkey="e" data-disable-with>
            <svg aria-hidden="true" class="octicon octicon-pencil" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path d="M0 12v3h3l8-8-3-3-8 8zm3 2H1v-2h1v1h1v1zm10.3-9.3L12 6 9 3l1.3-1.3a.996.996 0 0 1 1.41 0l1.59 1.59c.39.39.39 1.02 0 1.41z"></path></svg>
          </button>
</form>        <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/sefakilic/coursera-repdata/delete/master/project1/PA1_template.md" class="inline-form" data-form-nonce="c20406b7487cf93f3c8cb059b6c353a468d7aa1f" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="81HJ+t0zd3mNRONcrEliyPn+9MpbvysQOYmXUpmpCS7fE7pIk8svVHm9a8yDmqlAzntHBxUS8RqxBFFRjba7Tw==" /></div>
          <button class="btn-octicon btn-octicon-danger tooltipped tooltipped-nw" type="submit"
            aria-label="Delete the file in your fork of this project" data-disable-with>
            <svg aria-hidden="true" class="octicon octicon-trashcan" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M11 2H9c0-.55-.45-1-1-1H5c-.55 0-1 .45-1 1H2c-.55 0-1 .45-1 1v1c0 .55.45 1 1 1v9c0 .55.45 1 1 1h7c.55 0 1-.45 1-1V5c.55 0 1-.45 1-1V3c0-.55-.45-1-1-1zm-1 12H3V5h1v8h1V5h1v8h1V5h1v8h1V5h1v9zm1-10H2V3h9v1z"></path></svg>
          </button>
</form>  </div>

  <div class="file-info">
      160 lines (113 sloc)
      <span class="file-info-divider"></span>
    3.81 KB
  </div>
</div>

  
  <div id="readme" class="readme blob instapaper_body">
    <article class="markdown-body entry-content" itemprop="text"><h1><a id="user-content-reproducible-research-peer-assessment-1" class="anchor" href="#reproducible-research-peer-assessment-1" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Reproducible Research: Peer Assessment 1</h1>

<h2><a id="user-content-loading-and-preprocessing-the-data" class="anchor" href="#loading-and-preprocessing-the-data" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Loading and preprocessing the data</h2>

<div class="highlight highlight-source-r"><pre>unzip(<span class="pl-v">zipfile</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>activity.zip<span class="pl-pds">"</span></span>)
<span class="pl-smi">data</span> <span class="pl-k">&lt;-</span> read.csv(<span class="pl-s"><span class="pl-pds">"</span>activity.csv<span class="pl-pds">"</span></span>)</pre></div>

<h2><a id="user-content-what-is-mean-total-number-of-steps-taken-per-day" class="anchor" href="#what-is-mean-total-number-of-steps-taken-per-day" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>What is mean total number of steps taken per day?</h2>

<div class="highlight highlight-source-r"><pre>library(<span class="pl-smi">ggplot2</span>)
<span class="pl-smi">total.steps</span> <span class="pl-k">&lt;-</span> tapply(<span class="pl-smi">data</span><span class="pl-k">$</span><span class="pl-smi">steps</span>, <span class="pl-smi">data</span><span class="pl-k">$</span><span class="pl-smi">date</span>, <span class="pl-v">FUN</span> <span class="pl-k">=</span> <span class="pl-smi">sum</span>, <span class="pl-v">na.rm</span> <span class="pl-k">=</span> <span class="pl-c1">TRUE</span>)
qplot(<span class="pl-smi">total.steps</span>, <span class="pl-v">binwidth</span> <span class="pl-k">=</span> <span class="pl-c1">1000</span>, <span class="pl-v">xlab</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>total number of steps taken each day<span class="pl-pds">"</span></span>)</pre></div>

<p><a href="/sefakilic/coursera-repdata/blob/master/project1/figure/unnamed-chunk-1.png" target="_blank"><img src="/sefakilic/coursera-repdata/raw/master/project1/figure/unnamed-chunk-1.png" alt="plot of chunk unnamed-chunk-1" style="max-width:100%;"></a> </p>

<div class="highlight highlight-source-r"><pre>mean(<span class="pl-smi">total.steps</span>, <span class="pl-v">na.rm</span> <span class="pl-k">=</span> <span class="pl-c1">TRUE</span>)</pre></div>

<pre><code>## [1] 9354
</code></pre>

<div class="highlight highlight-source-r"><pre>median(<span class="pl-smi">total.steps</span>, <span class="pl-v">na.rm</span> <span class="pl-k">=</span> <span class="pl-c1">TRUE</span>)</pre></div>

<pre><code>## [1] 10395
</code></pre>

<h2><a id="user-content-what-is-the-average-daily-activity-pattern" class="anchor" href="#what-is-the-average-daily-activity-pattern" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>What is the average daily activity pattern?</h2>

<div class="highlight highlight-source-r"><pre>library(<span class="pl-smi">ggplot2</span>)
<span class="pl-smi">averages</span> <span class="pl-k">&lt;-</span> aggregate(<span class="pl-v">x</span> <span class="pl-k">=</span> <span class="pl-k">list</span>(<span class="pl-v">steps</span> <span class="pl-k">=</span> <span class="pl-smi">data</span><span class="pl-k">$</span><span class="pl-smi">steps</span>), <span class="pl-v">by</span> <span class="pl-k">=</span> <span class="pl-k">list</span>(<span class="pl-v">interval</span> <span class="pl-k">=</span> <span class="pl-smi">data</span><span class="pl-k">$</span><span class="pl-smi">interval</span>), 
    <span class="pl-v">FUN</span> <span class="pl-k">=</span> <span class="pl-smi">mean</span>, <span class="pl-v">na.rm</span> <span class="pl-k">=</span> <span class="pl-c1">TRUE</span>)
ggplot(<span class="pl-v">data</span> <span class="pl-k">=</span> <span class="pl-smi">averages</span>, aes(<span class="pl-v">x</span> <span class="pl-k">=</span> <span class="pl-smi">interval</span>, <span class="pl-v">y</span> <span class="pl-k">=</span> <span class="pl-smi">steps</span>)) <span class="pl-k">+</span> geom_line() <span class="pl-k">+</span> xlab(<span class="pl-s"><span class="pl-pds">"</span>5-minute interval<span class="pl-pds">"</span></span>) <span class="pl-k">+</span> 
    ylab(<span class="pl-s"><span class="pl-pds">"</span>average number of steps taken<span class="pl-pds">"</span></span>)</pre></div>

<p><a href="/sefakilic/coursera-repdata/blob/master/project1/figure/unnamed-chunk-2.png" target="_blank"><img src="/sefakilic/coursera-repdata/raw/master/project1/figure/unnamed-chunk-2.png" alt="plot of chunk unnamed-chunk-2" style="max-width:100%;"></a> </p>

<p>On average across all the days in the dataset, the 5-minute interval contains
the maximum number of steps?</p>

<div class="highlight highlight-source-r"><pre><span class="pl-smi">averages</span>[which.max(<span class="pl-smi">averages</span><span class="pl-k">$</span><span class="pl-smi">steps</span>), ]</pre></div>

<pre><code>##     interval steps
## 104      835 206.2
</code></pre>

<h2><a id="user-content-imputing-missing-values" class="anchor" href="#imputing-missing-values" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Imputing missing values</h2>

<p>There are many days/intervals where there are missing values (coded as <code>NA</code>). The presence of missing days may introduce bias into some calculations or summaries of the data.</p>

<div class="highlight highlight-source-r"><pre><span class="pl-smi">missing</span> <span class="pl-k">&lt;-</span> is.na(<span class="pl-smi">data</span><span class="pl-k">$</span><span class="pl-smi">steps</span>)
<span class="pl-c"># How many missing</span>
table(<span class="pl-smi">missing</span>)</pre></div>

<pre><code>## missing
## FALSE  TRUE 
## 15264  2304
</code></pre>

<p>All of the missing values are filled in with mean value for that 5-minute
interval.</p>

<div class="highlight highlight-source-r"><pre><span class="pl-c"># Replace each missing value with the mean value of its 5-minute interval</span>
<span class="pl-en">fill.value</span> <span class="pl-k">&lt;-</span> <span class="pl-k">function</span>(<span class="pl-smi">steps</span>, <span class="pl-smi">interval</span>) {
    <span class="pl-smi">filled</span> <span class="pl-k">&lt;-</span> <span class="pl-c1">NA</span>
    <span class="pl-k">if</span> (<span class="pl-k">!</span>is.na(<span class="pl-smi">steps</span>)) 
        <span class="pl-smi">filled</span> <span class="pl-k">&lt;-</span> c(<span class="pl-smi">steps</span>) <span class="pl-k">else</span> <span class="pl-smi">filled</span> <span class="pl-k">&lt;-</span> (<span class="pl-smi">averages</span>[<span class="pl-smi">averages</span><span class="pl-k">$</span><span class="pl-smi">interval</span> <span class="pl-k">==</span> <span class="pl-smi">interval</span>, <span class="pl-s"><span class="pl-pds">"</span>steps<span class="pl-pds">"</span></span>])
    <span class="pl-k">return</span>(<span class="pl-smi">filled</span>)
}
<span class="pl-smi">filled.data</span> <span class="pl-k">&lt;-</span> <span class="pl-smi">data</span>
<span class="pl-smi">filled.data</span><span class="pl-k">$</span><span class="pl-smi">steps</span> <span class="pl-k">&lt;-</span> mapply(<span class="pl-smi">fill.value</span>, <span class="pl-smi">filled.data</span><span class="pl-k">$</span><span class="pl-smi">steps</span>, <span class="pl-smi">filled.data</span><span class="pl-k">$</span><span class="pl-smi">interval</span>)</pre></div>

<p>Now, using the filled data set, let's make a histogram of the total number of steps taken each day and calculate the mean and median total number of steps.</p>

<div class="highlight highlight-source-r"><pre><span class="pl-smi">total.steps</span> <span class="pl-k">&lt;-</span> tapply(<span class="pl-smi">filled.data</span><span class="pl-k">$</span><span class="pl-smi">steps</span>, <span class="pl-smi">filled.data</span><span class="pl-k">$</span><span class="pl-smi">date</span>, <span class="pl-v">FUN</span> <span class="pl-k">=</span> <span class="pl-smi">sum</span>)
qplot(<span class="pl-smi">total.steps</span>, <span class="pl-v">binwidth</span> <span class="pl-k">=</span> <span class="pl-c1">1000</span>, <span class="pl-v">xlab</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>total number of steps taken each day<span class="pl-pds">"</span></span>)</pre></div>

<p><a href="/sefakilic/coursera-repdata/blob/master/project1/figure/unnamed-chunk-5.png" target="_blank"><img src="/sefakilic/coursera-repdata/raw/master/project1/figure/unnamed-chunk-5.png" alt="plot of chunk unnamed-chunk-5" style="max-width:100%;"></a> </p>

<div class="highlight highlight-source-r"><pre>mean(<span class="pl-smi">total.steps</span>)</pre></div>

<pre><code>## [1] 10766
</code></pre>

<div class="highlight highlight-source-r"><pre>median(<span class="pl-smi">total.steps</span>)</pre></div>

<pre><code>## [1] 10766
</code></pre>

<p>Mean and median values are higher after imputing missing data. The reason is
that in the original data, there are some days with <code>steps</code> values <code>NA</code> for 
any <code>interval</code>. The total number of steps taken in such days are set to 0s by
default. However, after replacing missing <code>steps</code> values with the mean <code>steps</code>
of associated <code>interval</code> value, these 0 values are removed from the histogram
of total number of steps taken each day.</p>

<h2><a id="user-content-are-there-differences-in-activity-patterns-between-weekdays-and-weekends" class="anchor" href="#are-there-differences-in-activity-patterns-between-weekdays-and-weekends" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Are there differences in activity patterns between weekdays and weekends?</h2>

<p>First, let's find the day of the week for each measurement in the dataset. In
this part, we use the dataset with the filled-in values.</p>

<div class="highlight highlight-source-r"><pre><span class="pl-en">weekday.or.weekend</span> <span class="pl-k">&lt;-</span> <span class="pl-k">function</span>(<span class="pl-smi">date</span>) {
    <span class="pl-smi">day</span> <span class="pl-k">&lt;-</span> weekdays(<span class="pl-smi">date</span>)
    <span class="pl-k">if</span> (<span class="pl-smi">day</span> <span class="pl-k">%in%</span> c(<span class="pl-s"><span class="pl-pds">"</span>Monday<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>Tuesday<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>Wednesday<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>Thursday<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>Friday<span class="pl-pds">"</span></span>)) 
        <span class="pl-k">return</span>(<span class="pl-s"><span class="pl-pds">"</span>weekday<span class="pl-pds">"</span></span>) <span class="pl-k">else</span> <span class="pl-k">if</span> (<span class="pl-smi">day</span> <span class="pl-k">%in%</span> c(<span class="pl-s"><span class="pl-pds">"</span>Saturday<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>Sunday<span class="pl-pds">"</span></span>)) 
        <span class="pl-k">return</span>(<span class="pl-s"><span class="pl-pds">"</span>weekend<span class="pl-pds">"</span></span>) <span class="pl-k">else</span> stop(<span class="pl-s"><span class="pl-pds">"</span>invalid date<span class="pl-pds">"</span></span>)
}
<span class="pl-smi">filled.data</span><span class="pl-k">$</span><span class="pl-smi">date</span> <span class="pl-k">&lt;-</span> as.Date(<span class="pl-smi">filled.data</span><span class="pl-k">$</span><span class="pl-smi">date</span>)
<span class="pl-smi">filled.data</span><span class="pl-k">$</span><span class="pl-smi">day</span> <span class="pl-k">&lt;-</span> sapply(<span class="pl-smi">filled.data</span><span class="pl-k">$</span><span class="pl-smi">date</span>, <span class="pl-v">FUN</span> <span class="pl-k">=</span> <span class="pl-smi">weekday.or.weekend</span>)</pre></div>

<p>Now, let's make a panel plot containing plots of average number of steps taken
on weekdays and weekends.</p>

<div class="highlight highlight-source-r"><pre><span class="pl-smi">averages</span> <span class="pl-k">&lt;-</span> aggregate(<span class="pl-smi">steps</span> <span class="pl-k">~</span> <span class="pl-smi">interval</span> <span class="pl-k">+</span> <span class="pl-smi">day</span>, <span class="pl-v">data</span> <span class="pl-k">=</span> <span class="pl-smi">filled.data</span>, <span class="pl-smi">mean</span>)
ggplot(<span class="pl-smi">averages</span>, aes(<span class="pl-smi">interval</span>, <span class="pl-smi">steps</span>)) <span class="pl-k">+</span> geom_line() <span class="pl-k">+</span> facet_grid(<span class="pl-smi">day</span> <span class="pl-k">~</span> .) <span class="pl-k">+</span> 
    xlab(<span class="pl-s"><span class="pl-pds">"</span>5-minute interval<span class="pl-pds">"</span></span>) <span class="pl-k">+</span> ylab(<span class="pl-s"><span class="pl-pds">"</span>Number of steps<span class="pl-pds">"</span></span>)</pre></div>

<p><a href="/sefakilic/coursera-repdata/blob/master/project1/figure/unnamed-chunk-7.png" target="_blank"><img src="/sefakilic/coursera-repdata/raw/master/project1/figure/unnamed-chunk-7.png" alt="plot of chunk unnamed-chunk-7" style="max-width:100%;"></a> </p>
</article>
  </div>

</div>

<button type="button" data-facebox="#jump-to-line" data-facebox-class="linejump" data-hotkey="l" class="hidden">Jump to Line</button>
<div id="jump-to-line" style="display:none">
  <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="" class="js-jump-to-line-form" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
    <input class="form-control linejump-input js-jump-to-line-field" type="text" placeholder="Jump to line&hellip;" aria-label="Jump to line" autofocus>
    <button type="submit" class="btn">Go</button>
</form></div>

  </div>
  <div class="modal-backdrop js-touch-events"></div>
</div>


    </div>
  </div>

    </div>

        <div class="container site-footer-container">
  <div class="site-footer" role="contentinfo">
    <ul class="site-footer-links right">
        <li><a href="https://github.com/contact" data-ga-click="Footer, go to contact, text:contact">Contact GitHub</a></li>
      <li><a href="https://developer.github.com" data-ga-click="Footer, go to api, text:api">API</a></li>
      <li><a href="https://training.github.com" data-ga-click="Footer, go to training, text:training">Training</a></li>
      <li><a href="https://shop.github.com" data-ga-click="Footer, go to shop, text:shop">Shop</a></li>
        <li><a href="https://github.com/blog" data-ga-click="Footer, go to blog, text:blog">Blog</a></li>
        <li><a href="https://github.com/about" data-ga-click="Footer, go to about, text:about">About</a></li>

    </ul>

    <a href="https://github.com" aria-label="Homepage" class="site-footer-mark" title="GitHub">
      <svg aria-hidden="true" class="octicon octicon-mark-github" height="24" version="1.1" viewBox="0 0 16 16" width="24"><path d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0 0 16 8c0-4.42-3.58-8-8-8z"></path></svg>
</a>
    <ul class="site-footer-links">
      <li>&copy; 2016 <span title="0.09574s from github-fe136-cp1-prd.iad.github.net">GitHub</span>, Inc.</li>
        <li><a href="https://github.com/site/terms" data-ga-click="Footer, go to terms, text:terms">Terms</a></li>
        <li><a href="https://github.com/site/privacy" data-ga-click="Footer, go to privacy, text:privacy">Privacy</a></li>
        <li><a href="https://github.com/security" data-ga-click="Footer, go to security, text:security">Security</a></li>
        <li><a href="https://status.github.com/" data-ga-click="Footer, go to status, text:status">Status</a></li>
        <li><a href="https://help.github.com" data-ga-click="Footer, go to help, text:help">Help</a></li>
    </ul>
  </div>
</div>



    

    <div id="ajax-error-message" class="ajax-error-message flash flash-error">
      <svg aria-hidden="true" class="octicon octicon-alert" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M8.865 1.52c-.18-.31-.51-.5-.87-.5s-.69.19-.87.5L.275 13.5c-.18.31-.18.69 0 1 .19.31.52.5.87.5h13.7c.36 0 .69-.19.86-.5.17-.31.18-.69.01-1L8.865 1.52zM8.995 13h-2v-2h2v2zm0-3h-2V6h2v4z"></path></svg>
      <button type="button" class="flash-close js-flash-close js-ajax-error-dismiss" aria-label="Dismiss error">
        <svg aria-hidden="true" class="octicon octicon-x" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48z"></path></svg>
      </button>
      You can't perform that action at this time.
    </div>


      
      <script crossorigin="anonymous" integrity="sha256-lS0UrBYsb28ycXWIL2saRkW/eq3Js2zNUtUPxvNMhWg=" src="https://assets-cdn.github.com/assets/frameworks-952d14ac162c6f6f327175882f6b1a4645bf7aadc9b36ccd52d50fc6f34c8568.js"></script>
      <script async="async" crossorigin="anonymous" integrity="sha256-Ol4+RUXH6FSw5isaIzU6RpZdDjJksZs7T3df9m3JaJo=" src="https://assets-cdn.github.com/assets/github-3a5e3e4545c7e854b0e62b1a23353a46965d0e3264b19b3b4f775ff66dc9689a.js"></script>
      
      
      
      
      
      
    <div class="js-stale-session-flash stale-session-flash flash flash-warn flash-banner hidden">
      <svg aria-hidden="true" class="octicon octicon-alert" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M8.865 1.52c-.18-.31-.51-.5-.87-.5s-.69.19-.87.5L.275 13.5c-.18.31-.18.69 0 1 .19.31.52.5.87.5h13.7c.36 0 .69-.19.86-.5.17-.31.18-.69.01-1L8.865 1.52zM8.995 13h-2v-2h2v2zm0-3h-2V6h2v4z"></path></svg>
      <span class="signed-in-tab-flash">You signed in with another tab or window. <a href="">Reload</a> to refresh your session.</span>
      <span class="signed-out-tab-flash">You signed out in another tab or window. <a href="">Reload</a> to refresh your session.</span>
    </div>
    <div class="facebox" id="facebox" style="display:none;">
  <div class="facebox-popup">
    <div class="facebox-content" role="dialog" aria-labelledby="facebox-header" aria-describedby="facebox-description">
    </div>
    <button type="button" class="facebox-close js-facebox-close" aria-label="Close modal">
      <svg aria-hidden="true" class="octicon octicon-x" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48z"></path></svg>
    </button>
  </div>
</div>

  </body>
</html>

