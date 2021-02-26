<div class="container-xl clearfix new-discussion-timeline px-3 px-md-4 px-lg-5">
  <div id="repo-content-pjax-container" class="repository-content ">


  

<div>
  


    <a class="d-none js-permalink-shortcut" data-hotkey="y" href="/durgeshsamariya/awesome-github-profile-readme-templates/blob/ece5780de54f5b156e232ef9f3ac0d04f186b798/Bgstatic.md">Permalink</a>

    <!-- blob contrib key: blob_contributors:v22:d0d4082776c9ec60d443e1c957813974988075fce7cf3f9061ddd3900446742c -->

    <div class="d-flex flex-items-start flex-shrink-0 pb-3 flex-wrap flex-md-nowrap flex-justify-between flex-md-justify-start">
      
<div class="position-relative">
  <details class="details-reset details-overlay mr-0 mb-0 " id="branch-select-menu">
    <summary class="btn css-truncate" data-hotkey="w" title="Switch branches or tags">
      <svg class="octicon octicon-git-branch text-gray" height="16" viewBox="0 0 16 16" version="1.1" width="16" aria-hidden="true"><path fill-rule="evenodd" d="M11.75 2.5a.75.75 0 100 1.5.75.75 0 000-1.5zm-2.25.75a2.25 2.25 0 113 2.122V6A2.5 2.5 0 0110 8.5H6a1 1 0 00-1 1v1.128a2.251 2.251 0 11-1.5 0V5.372a2.25 2.25 0 111.5 0v1.836A2.492 2.492 0 016 7h4a1 1 0 001-1v-.628A2.25 2.25 0 019.5 3.25zM4.25 12a.75.75 0 100 1.5.75.75 0 000-1.5zM3.5 3.25a.75.75 0 111.5 0 .75.75 0 01-1.5 0z"></path></svg>
      <span class="css-truncate-target" data-menu-button="">master</span>
      <span class="dropdown-caret"></span>
    </summary>

      <div class="SelectMenu">
  <div class="SelectMenu-modal">
    <header class="SelectMenu-header">
      <span class="SelectMenu-title">Switch branches/tags</span>
      <button class="SelectMenu-closeButton" type="button" data-toggle-for="branch-select-menu"><svg aria-label="Close menu" aria-hidden="false" class="octicon octicon-x" height="16" viewBox="0 0 16 16" version="1.1" width="16"><path fill-rule="evenodd" d="M3.72 3.72a.75.75 0 011.06 0L8 6.94l3.22-3.22a.75.75 0 111.06 1.06L9.06 8l3.22 3.22a.75.75 0 11-1.06 1.06L8 9.06l-3.22 3.22a.75.75 0 01-1.06-1.06L6.94 8 3.72 4.78a.75.75 0 010-1.06z"></path></svg></button>
    </header>

    <input-demux data-action="tab-container-change:input-demux#storeInput tab-container-changed:input-demux#updateInput" data-catalyst="">
      <tab-container class="d-flex flex-column js-branches-tags-tabs" style="min-height: 0;">
        <div class="SelectMenu-filter">
          <input data-target="input-demux.source" id="context-commitish-filter-field" class="SelectMenu-input form-control" aria-owns="ref-list-branches" data-controls-ref-menu-id="ref-list-branches" autofocus="" autocomplete="off" aria-label="Filter branches/tags" placeholder="Filter branches/tags" type="text">
        </div>

        <div class="SelectMenu-tabs" role="tablist" data-target="input-demux.control">
          <button class="SelectMenu-tab" type="button" role="tab" aria-selected="true" tabindex="0">Branches</button>
          <button class="SelectMenu-tab" type="button" role="tab" aria-selected="false" tabindex="-1">Tags</button>
        </div>

        <div role="tabpanel" id="ref-list-branches" data-filter-placeholder="Filter branches/tags" class="d-flex flex-column flex-auto overflow-auto" tabindex="">
          <ref-selector type="branch" data-targets="input-demux.sinks" data-action="
              input-entered:ref-selector#inputEntered
              tab-selected:ref-selector#tabSelected
              focus-list:ref-selector#focusFirstListMember
            " query-endpoint="/durgeshsamariya/awesome-github-profile-readme-templates/refs" cache-key="v0:1598713665.0" current-committish="bWFzdGVy" default-branch="bWFzdGVy" name-with-owner="ZHVyZ2VzaHNhbWFyaXlhL2F3ZXNvbWUtZ2l0aHViLXByb2ZpbGUtcmVhZG1lLXRlbXBsYXRlcw==" data-catalyst="">

            <template data-target="ref-selector.noMatchTemplate">
                <div class="SelectMenu-message">Nothing to show</div>
            </template>

            <!-- TODO: this max-height is necessary or else the branch list won't scroll.  why? -->
            <div data-target="ref-selector.listContainer" role="menu" class="SelectMenu-list" style="max-height: 330px">
              <div class="SelectMenu-loading pt-3 pb-0" aria-label="Menu is loading">
                <svg style="box-sizing: content-box; color: var(--color-icon-primary);" viewBox="0 0 16 16" fill="none" width="32" height="32">
  <circle cx="8" cy="8" r="7" stroke="currentColor" stroke-opacity="0.25" stroke-width="2" vector-effect="non-scaling-stroke"></circle>
  <path d="M15 8a7.002 7.002 0 00-7-7" stroke="currentColor" stroke-width="2" stroke-linecap="round" vector-effect="non-scaling-stroke">
    <animateTransform attributeName="transform" type="rotate" from="0 8 8" to="360 8 8" dur="1s" repeatCount="indefinite"></animateTransform>
  </path>
</svg>
              </div>
            </div>

            <template data-target="ref-selector.itemTemplate">
              <a href="https://github.com/durgeshsamariya/awesome-github-profile-readme-templates/blob/{{ urlEncodedRefName }}/Bgstatic.md" class="SelectMenu-item" role="menuitemradio" rel="nofollow" aria-checked="{{ isCurrent }}" data-index="{{ index }}">
                <svg class="octicon octicon-check SelectMenu-icon SelectMenu-icon--check" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path></svg>
                <span class="flex-1 css-truncate css-truncate-overflow {{ isFilteringClass }}">{{ refName }}</span>
                <span hidden="{{ isNotDefault }}" class="Label Label--secondary flex-self-start">default</span> 
              </a>
            </template>
            <footer class="SelectMenu-footer"><a href="/durgeshsamariya/awesome-github-profile-readme-templates/branches">View all branches</a></footer>
          </ref-selector>

        </div>

        <div role="tabpanel" id="tags-menu" data-filter-placeholder="Find a tag" class="d-flex flex-column flex-auto overflow-auto" tabindex="" hidden="">
          <ref-selector type="tag" data-action="
              input-entered:ref-selector#inputEntered
              tab-selected:ref-selector#tabSelected
              focus-list:ref-selector#focusFirstListMember
            " data-targets="input-demux.sinks" query-endpoint="/durgeshsamariya/awesome-github-profile-readme-templates/refs" cache-key="v0:1598713665.0" current-committish="bWFzdGVy" default-branch="bWFzdGVy" name-with-owner="ZHVyZ2VzaHNhbWFyaXlhL2F3ZXNvbWUtZ2l0aHViLXByb2ZpbGUtcmVhZG1lLXRlbXBsYXRlcw==" data-catalyst="">

            <template data-target="ref-selector.noMatchTemplate">
              <div class="SelectMenu-message" data-index="{{ index }}">Nothing to show</div>
            </template>

            <template data-target="ref-selector.itemTemplate">
              <a href="https://github.com/durgeshsamariya/awesome-github-profile-readme-templates/blob/{{ urlEncodedRefName }}/Bgstatic.md" class="SelectMenu-item" role="menuitemradio" rel="nofollow" aria-checked="{{ isCurrent }}" data-index="{{ index }}">
                <svg class="octicon octicon-check SelectMenu-icon SelectMenu-icon--check" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path></svg>
                <span class="flex-1 css-truncate css-truncate-overflow {{ isFilteringClass }}">{{ refName }}</span>
                <span hidden="{{ isNotDefault }}" class="Label Label--secondary flex-self-start">default</span>
              </a>
            </template>
            <div data-target="ref-selector.listContainer" role="menu" class="SelectMenu-list" style="max-height: 330px">
              <div class="SelectMenu-loading pt-3 pb-0" aria-label="Menu is loading">
                <svg style="box-sizing: content-box; color: var(--color-icon-primary);" viewBox="0 0 16 16" fill="none" width="32" height="32">
  <circle cx="8" cy="8" r="7" stroke="currentColor" stroke-opacity="0.25" stroke-width="2" vector-effect="non-scaling-stroke"></circle>
  <path d="M15 8a7.002 7.002 0 00-7-7" stroke="currentColor" stroke-width="2" stroke-linecap="round" vector-effect="non-scaling-stroke">
    <animateTransform attributeName="transform" type="rotate" from="0 8 8" to="360 8 8" dur="1s" repeatCount="indefinite"></animateTransform>
  </path>
</svg>
              </div>
            </div>
            <footer class="SelectMenu-footer"><a href="/durgeshsamariya/awesome-github-profile-readme-templates/tags">View all tags</a></footer>
          </ref-selector>
        </div>
      </tab-container>
    </input-demux>
  </div>
</div>

  </details>

</div>

      <h2 id="blob-path" class="breadcrumb flex-auto min-width-0 text-normal mx-0 mx-md-3 width-full width-md-auto flex-order-1 flex-md-order-none mt-3 mt-md-0">
        <span class="js-repo-root text-bold"><span class="js-path-segment d-inline-block wb-break-all"><a data-pjax="true" href="/durgeshsamariya/awesome-github-profile-readme-templates"><span>awesome-github-profile-readme-templates</span></a></span></span><span class="separator">/</span><strong class="final-path">Bgstatic.md</strong>
      </h2>
      <a href="/durgeshsamariya/awesome-github-profile-readme-templates/find/master" class="js-pjax-capture-input btn mr-2 d-none d-md-block" data-pjax="" data-hotkey="t">
        Go to file
      </a>

      <details id="blob-more-options-details" class="details-overlay details-reset position-relative">
  <summary role="button" type="button" class="btn ">
    <svg aria-label="More options" class="octicon octicon-kebab-horizontal" height="16" viewBox="0 0 16 16" version="1.1" width="16" role="img"><path d="M8 9a1.5 1.5 0 100-3 1.5 1.5 0 000 3zM1.5 9a1.5 1.5 0 100-3 1.5 1.5 0 000 3zm13 0a1.5 1.5 0 100-3 1.5 1.5 0 000 3z"></path></svg>
</summary>  <div>
    <ul class="dropdown-menu dropdown-menu-sw">
            <li class="d-block d-md-none">
              <a class="dropdown-item d-flex flex-items-baseline" data-hydro-click="{&quot;event_type&quot;:&quot;repository.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;FIND_FILE_BUTTON&quot;,&quot;repository_id&quot;:291293670,&quot;originating_url&quot;:&quot;https://github.com/durgeshsamariya/awesome-github-profile-readme-templates/blob/master/Bgstatic.md?_pjax=%23repo-content-pjax-container&quot;,&quot;user_id&quot;:54537482}}" data-hydro-click-hmac="896f8db4a901a1e73a9bd646418f4fc51890d56ff70fce48e0e551b21b907849" data-ga-click="Repository, find file, location:repo overview" data-hotkey="t" data-pjax="true" href="/durgeshsamariya/awesome-github-profile-readme-templates/find/master">
                <span class="flex-auto">Go to file</span>
                <span class="text-small text-gray" aria-hidden="true">T</span>
</a>            </li>
            <li data-toggle-for="blob-more-options-details">
              <button type="button" data-toggle-for="jumpto-line-details-dialog" class="btn-link dropdown-item">
                <span class="d-flex flex-items-baseline">
                  <span class="flex-auto">Go to line</span>
                  <span class="text-small text-gray" aria-hidden="true">L</span>
                </span>
              </button>
            </li>
            <li class="dropdown-divider" role="none"></li>
            <li>
              <clipboard-copy value="Bgstatic.md" class="dropdown-item cursor-pointer" data-toggle-for="blob-more-options-details" tabindex="0" role="button">
                Copy path
              </clipboard-copy>
            </li>
          </ul>
</div></details>    </div>



    <div class="Box d-flex flex-column flex-shrink-0 mb-3">
      

  <div class="Box-header Box-header--blue Details js-details-container">
      <div class="d-flex flex-items-center">
        <span class="flex-shrink-0 ml-n1 mr-n1 mt-n1 mb-n1">
          <a rel="author" data-skip-pjax="true" data-hovercard-type="user" data-hovercard-url="/users/durgeshsamariya/hovercard" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/durgeshsamariya"><img class="avatar avatar-user" src="https://avatars.githubusercontent.com/u/16861529?s=48&amp;v=4" width="24" height="24" alt="@durgeshsamariya"></a>
        </span>
        <div class="flex-1 d-flex flex-items-center ml-3 min-width-0">
          <div class="css-truncate css-truncate-overflow">
            <a class="text-bold Link--primary" rel="author" data-hovercard-type="user" data-hovercard-url="/users/durgeshsamariya/hovercard" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/durgeshsamariya">durgeshsamariya</a>

              <span>
                <a data-pjax="true" title="Bgstatic's profile added." class="Link--secondary" href="/durgeshsamariya/awesome-github-profile-readme-templates/commit/87b6a827a39fac2bafee3293ec4c6b72cf6b054b">Bgstatic's profile added.</a>
              </span>
          </div>


          <span class="ml-2">
            
          </span>
        </div>
        <div class="ml-3 d-flex flex-shrink-0 flex-items-center flex-justify-end text-gray no-wrap">
          <span class="d-none d-md-inline">
            <span>Latest commit</span>
            <a class="text-small text-mono Link--secondary" href="/durgeshsamariya/awesome-github-profile-readme-templates/commit/87b6a827a39fac2bafee3293ec4c6b72cf6b054b" data-pjax="">87b6a82</a>
            <span itemprop="dateModified"><relative-time datetime="2020-09-23T11:55:27Z" class="no-wrap" title="Sep 23, 2020, 1:55 PM GMT+2">on Sep 23, 2020</relative-time></span>
          </span>

          <a data-pjax="" href="/durgeshsamariya/awesome-github-profile-readme-templates/commits/master/Bgstatic.md" class="ml-3 no-wrap Link--primary no-underline">
            <svg class="octicon octicon-history text-gray" height="16" viewBox="0 0 16 16" version="1.1" width="16" aria-hidden="true"><path fill-rule="evenodd" d="M1.643 3.143L.427 1.927A.25.25 0 000 2.104V5.75c0 .138.112.25.25.25h3.646a.25.25 0 00.177-.427L2.715 4.215a6.5 6.5 0 11-1.18 4.458.75.75 0 10-1.493.154 8.001 8.001 0 101.6-5.684zM7.75 4a.75.75 0 01.75.75v2.992l2.028.812a.75.75 0 01-.557 1.392l-2.5-1A.75.75 0 017 8.25v-3.5A.75.75 0 017.75 4z"></path></svg>
            <span class="d-none d-sm-inline">
              <strong>History</strong>
            </span>
          </a>
        </div>
      </div>

  </div>

  <div class="Box-body d-flex flex-items-center flex-auto border-bottom-0 flex-wrap">
    <details class="details-reset details-overlay details-overlay-dark lh-default text-gray-dark float-left mr-3" id="blob_contributors_box">
      <summary class="Link--primary" role="button">
        <svg class="octicon octicon-people text-gray" height="16" viewBox="0 0 16 16" version="1.1" width="16" aria-hidden="true"><path fill-rule="evenodd" d="M5.5 3.5a2 2 0 100 4 2 2 0 000-4zM2 5.5a3.5 3.5 0 115.898 2.549 5.507 5.507 0 013.034 4.084.75.75 0 11-1.482.235 4.001 4.001 0 00-7.9 0 .75.75 0 01-1.482-.236A5.507 5.507 0 013.102 8.05 3.49 3.49 0 012 5.5zM11 4a.75.75 0 100 1.5 1.5 1.5 0 01.666 2.844.75.75 0 00-.416.672v.352a.75.75 0 00.574.73c1.2.289 2.162 1.2 2.522 2.372a.75.75 0 101.434-.44 5.01 5.01 0 00-2.56-3.012A3 3 0 0011 4z"></path></svg>
        <strong>1</strong>
        
        contributor
      </summary>
      <details-dialog class="Box Box--overlay d-flex flex-column anim-fade-in fast" aria-label="Users who have contributed to this file" src="/durgeshsamariya/awesome-github-profile-readme-templates/contributors-list/master/Bgstatic.md" preload="" role="dialog" aria-modal="true">
        <div class="Box-header">
          <button class="Box-btn-octicon btn-octicon float-right" type="button" aria-label="Close dialog" data-close-dialog="">
            <svg class="octicon octicon-x" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M3.72 3.72a.75.75 0 011.06 0L8 6.94l3.22-3.22a.75.75 0 111.06 1.06L9.06 8l3.22 3.22a.75.75 0 11-1.06 1.06L8 9.06l-3.22 3.22a.75.75 0 01-1.06-1.06L6.94 8 3.72 4.78a.75.75 0 010-1.06z"></path></svg>
          </button>
          <h3 class="Box-title">
            Users who have contributed to this file
          </h3>
        </div>
        <include-fragment>
          <svg style="box-sizing: content-box; color: var(--color-icon-primary);" viewBox="0 0 16 16" fill="none" width="32" height="32" class="my-3 mx-auto d-block">
  <circle cx="8" cy="8" r="7" stroke="currentColor" stroke-opacity="0.25" stroke-width="2" vector-effect="non-scaling-stroke"></circle>
  <path d="M15 8a7.002 7.002 0 00-7-7" stroke="currentColor" stroke-width="2" stroke-linecap="round" vector-effect="non-scaling-stroke">
    <animateTransform attributeName="transform" type="rotate" from="0 8 8" to="360 8 8" dur="1s" repeatCount="indefinite"></animateTransform>
  </path>
</svg>
        </include-fragment>
      </details-dialog>
    </details>
  </div>
    </div>






    <div class="Box mt-3 position-relative
      ">
      
<div class="Box-header py-2 d-flex flex-column flex-shrink-0 flex-md-row flex-md-items-center">
  <div class="text-mono f6 flex-auto pr-3 flex-order-2 flex-md-order-1 mt-2 mt-md-0">

      93 lines (65 sloc)
      <span class="file-info-divider"></span>
    4.59 KB
  </div>

  <div class="d-flex py-1 py-md-0 flex-auto flex-order-1 flex-md-order-2 flex-sm-grow-0 flex-justify-between">

    <div class="BtnGroup">
      <a href="/durgeshsamariya/awesome-github-profile-readme-templates/raw/master/Bgstatic.md" id="raw-url" role="button" class="btn btn-sm BtnGroup-item ">Raw</a>
        <a href="/durgeshsamariya/awesome-github-profile-readme-templates/blame/master/Bgstatic.md" data-hotkey="b" role="button" class="btn js-update-url-with-hash btn-sm BtnGroup-item ">Blame</a>
    </div>

    <div>
          <a class="btn-octicon tooltipped tooltipped-nw js-remove-unless-platform" data-platforms="windows,mac" href="https://desktop.github.com" aria-label="Open this file in GitHub Desktop" data-ga-click="Repository, open with desktop">
              <svg class="octicon octicon-device-desktop" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M1.75 2.5h12.5a.25.25 0 01.25.25v7.5a.25.25 0 01-.25.25H1.75a.25.25 0 01-.25-.25v-7.5a.25.25 0 01.25-.25zM14.25 1H1.75A1.75 1.75 0 000 2.75v7.5C0 11.216.784 12 1.75 12h3.727c-.1 1.041-.52 1.872-1.292 2.757A.75.75 0 004.75 16h6.5a.75.75 0 00.565-1.243c-.772-.885-1.193-1.716-1.292-2.757h3.727A1.75 1.75 0 0016 10.25v-7.5A1.75 1.75 0 0014.25 1zM9.018 12H6.982a5.72 5.72 0 01-.765 2.5h3.566a5.72 5.72 0 01-.765-2.5z"></path></svg>
          </a>

          <!-- '"` --><!-- </textarea></xmp> --><form class="inline-form js-update-url-with-hash" action="/durgeshsamariya/awesome-github-profile-readme-templates/edit/master/Bgstatic.md" accept-charset="UTF-8" method="post"><input type="hidden" name="authenticity_token" value="cqCFL8cXNof7Kl1x3aSyI0g2eepvMiZBdf1LhsIIGBhdPIcOruGA4q9C7FOpyp9mLEfyEi4XS5IsxgkLOo6qhA==">
            <button class="btn-octicon tooltipped tooltipped-nw" type="submit" aria-label="Fork this project and edit the file" data-hotkey="e" data-disable-with="">
              <svg class="octicon octicon-pencil" height="16" viewBox="0 0 16 16" version="1.1" width="16" aria-hidden="true"><path fill-rule="evenodd" d="M11.013 1.427a1.75 1.75 0 012.474 0l1.086 1.086a1.75 1.75 0 010 2.474l-8.61 8.61c-.21.21-.47.364-.756.445l-3.251.93a.75.75 0 01-.927-.928l.929-3.25a1.75 1.75 0 01.445-.758l8.61-8.61zm1.414 1.06a.25.25 0 00-.354 0L10.811 3.75l1.439 1.44 1.263-1.263a.25.25 0 000-.354l-1.086-1.086zM11.189 6.25L9.75 4.81l-6.286 6.287a.25.25 0 00-.064.108l-.558 1.953 1.953-.558a.249.249 0 00.108-.064l6.286-6.286z"></path></svg>
            </button>
</form>
          <!-- '"` --><!-- </textarea></xmp> --><form class="inline-form" action="/durgeshsamariya/awesome-github-profile-readme-templates/delete/master/Bgstatic.md" accept-charset="UTF-8" method="post"><input type="hidden" name="authenticity_token" value="Y0Q/e68i+rpCU2Uk+pvWSt5lnw9W7zjG3gSGzi9dgovURHalb0FZ7MA5bqS5iy2lMh/Lm7Rb3P+NUSpfj7Wj6w==">
            <button class="btn-octicon btn-octicon-danger tooltipped tooltipped-nw" type="submit" aria-label="Fork this project and delete the file" data-disable-with="">
              <svg class="octicon octicon-trashcan" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M6.5 1.75a.25.25 0 01.25-.25h2.5a.25.25 0 01.25.25V3h-3V1.75zm4.5 0V3h2.25a.75.75 0 010 1.5H2.75a.75.75 0 010-1.5H5V1.75C5 .784 5.784 0 6.75 0h2.5C10.216 0 11 .784 11 1.75zM4.496 6.675a.75.75 0 10-1.492.15l.66 6.6A1.75 1.75 0 005.405 15h5.19c.9 0 1.652-.681 1.741-1.576l.66-6.6a.75.75 0 00-1.492-.149l-.66 6.6a.25.25 0 01-.249.225h-5.19a.25.25 0 01-.249-.225l-.66-6.6z"></path></svg>
            </button>
</form>    </div>
  </div>
</div>

      
  <div id="readme" class="Box-body readme blob js-code-block-container p-5 p-xl-6 gist-border-0">
    <article class="markdown-body entry-content container-lg" itemprop="text"><h1><a id="user-content-hi-there-im-bilgehan---aka-bgstatic-" class="anchor" aria-hidden="true" href="#hi-there-im-bilgehan---aka-bgstatic-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Hi there, I'm Bilgehan - aka <a href="http://bilgehangecici.site/" rel="nofollow">Bgstatic</a> <a target="_blank" rel="noopener noreferrer" href="https://camo.githubusercontent.com/7390f3bfa3f4d9a87252f67bce55626f086731af2c79ede13768ce9231918427/68747470733a2f2f6d656469612e74656e6f722e636f6d2f696d616765732f33623338386665303364613237316432363734666166383565623763336663642f74656e6f722e676966"><img width="30px" src="https://camo.githubusercontent.com/7390f3bfa3f4d9a87252f67bce55626f086731af2c79ede13768ce9231918427/68747470733a2f2f6d656469612e74656e6f722e636f6d2f696d616765732f33623338386665303364613237316432363734666166383565623763336663642f74656e6f722e676966" data-canonical-src="https://media.tenor.com/images/3b388fe03da271d2674faf85eb7c3fcd/tenor.gif" style="max-width:100%;"></a></h1>
<p><a target="_blank" rel="noopener noreferrer" href="https://camo.githubusercontent.com/5fca3db52c463447c36cbf864b01eac247219e56ce24dc0169a66c62ae53a481/68747470733a2f2f6d656469612e67697068792e636f6d2f6d656469612f6475334a336358797a686a3735494f6776412f67697068792e676966"><img align="right" alt="GIF" height="160px" src="https://camo.githubusercontent.com/5fca3db52c463447c36cbf864b01eac247219e56ce24dc0169a66c62ae53a481/68747470733a2f2f6d656469612e67697068792e636f6d2f6d656469612f6475334a336358797a686a3735494f6776412f67697068792e676966" data-canonical-src="https://media.giphy.com/media/du3J3cXyzhj75IOgvA/giphy.gif" style="max-width:100%;"></a></p>
<h2><a id="user-content-im-a-computer-science-and-engineering-student" class="anchor" aria-hidden="true" href="#im-a-computer-science-and-engineering-student"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>I'm a Computer Science and Engineering Student</h2>
<ul>
<li><g-emoji class="g-emoji" alias="man_technologist" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f468-1f4bb.png">👨‍💻</g-emoji> I’m currently working on Alita Discord Bot.</li>
<li><g-emoji class="g-emoji" alias="books" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f4da.png">📚</g-emoji> I’m currently learning everything. <g-emoji class="g-emoji" alias="sweat_smile" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f605.png">😅</g-emoji></li>
<li>💪🏼 Future Goals: Make a succesful discord bot.</li>

</ul>
<hr>
<p><a target="_blank" rel="noopener noreferrer" href="https://camo.githubusercontent.com/1fafb7e1b9d5369a835bfd5280e3e762f07023ca2d8c2fad9d104ceee2253842/68747470733a2f2f6d656469612e67697068792e636f6d2f6d656469612f4a3542315938515a6e7a5858624c514942752f67697068792e676966"><img align="right" alt="GIF" height="170px" src="https://camo.githubusercontent.com/1fafb7e1b9d5369a835bfd5280e3e762f07023ca2d8c2fad9d104ceee2253842/68747470733a2f2f6d656469612e67697068792e636f6d2f6d656469612f4a3542315938515a6e7a5858624c514942752f67697068792e676966" data-canonical-src="https://media.giphy.com/media/J5B1Y8QZnzXXbLQIBu/giphy.gif" style="max-width:100%;"></a></p>
<h3><a id="user-content-spotify-playing-" class="anchor" aria-hidden="true" href="#spotify-playing-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Spotify Playing <g-emoji class="g-emoji" alias="headphones" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f3a7.png">🎧</g-emoji></h3>
<p><a href="https://open.spotify.com/user/11153360645" rel="nofollow"><img src="https://camo.githubusercontent.com/defd2fd15e6c1674452424df873781cf784a940dca15f21022062e7069f64d39/68747470733a2f2f6e6f7661746f72656d2e62677374617469632e76657263656c2e6170702f6170692f73706f74696679" alt="Spotify" data-canonical-src="https://novatorem.bgstatic.vercel.app/api/spotify" style="max-width:100%;"></a></p>





<hr>
<h3><a id="user-content-languages-and-tools-" class="anchor" aria-hidden="true" href="#languages-and-tools-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Languages and Tools <g-emoji class="g-emoji" alias="hammer_and_wrench" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f6e0.png">🛠</g-emoji></h3>
<p>

<a target="_blank" rel="noopener noreferrer" href="https://camo.githubusercontent.com/5e1e74e61d73ef1087f34c4841e05f94b46e16da7312e262fe2e9e728d8e77ce/687474703a2f2f696d672e736869656c64732e696f2f62616467652f2d507974686f6e2d3337373641423f7374796c653d666c61742d737175617265266c6f676f3d707974686f6e266c6f676f436f6c6f723d666666666666"><img src="https://camo.githubusercontent.com/5e1e74e61d73ef1087f34c4841e05f94b46e16da7312e262fe2e9e728d8e77ce/687474703a2f2f696d672e736869656c64732e696f2f62616467652f2d507974686f6e2d3337373641423f7374796c653d666c61742d737175617265266c6f676f3d707974686f6e266c6f676f436f6c6f723d666666666666" alt="Python" data-canonical-src="http://img.shields.io/badge/-Python-3776AB?style=flat-square&amp;logo=python&amp;logoColor=ffffff" style="max-width:100%;"></a>
<a target="_blank" rel="noopener noreferrer" href="https://camo.githubusercontent.com/a1309b252e82434062012a8073fa9fc1416a96289b7ca11555577b9fbe1cf03e/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f2d4a6176615363726970742d2532334637444631433f7374796c653d666c61742d737175617265266c6f676f3d6a617661736372697074266c6f676f436f6c6f723d303030303030266c6162656c436f6c6f723d25323346374446314326636f6c6f723d253233464643453541"><img src="https://camo.githubusercontent.com/a1309b252e82434062012a8073fa9fc1416a96289b7ca11555577b9fbe1cf03e/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f2d4a6176615363726970742d2532334637444631433f7374796c653d666c61742d737175617265266c6f676f3d6a617661736372697074266c6f676f436f6c6f723d303030303030266c6162656c436f6c6f723d25323346374446314326636f6c6f723d253233464643453541" alt="JavaScript" data-canonical-src="https://img.shields.io/badge/-JavaScript-%23F7DF1C?style=flat-square&amp;logo=javascript&amp;logoColor=000000&amp;labelColor=%23F7DF1C&amp;color=%23FFCE5A" style="max-width:100%;"></a>

<a target="_blank" rel="noopener noreferrer" href="https://camo.githubusercontent.com/9a7c8c4ee62739436a191706be9f786a813dc377ce778522da198cb94874dc22/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f2d48544d4c352d2532334534344432373f7374796c653d666c61742d737175617265266c6f676f3d68746d6c35266c6f676f436f6c6f723d666666666666"><img src="https://camo.githubusercontent.com/9a7c8c4ee62739436a191706be9f786a813dc377ce778522da198cb94874dc22/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f2d48544d4c352d2532334534344432373f7374796c653d666c61742d737175617265266c6f676f3d68746d6c35266c6f676f436f6c6f723d666666666666" alt="HTML5" data-canonical-src="https://img.shields.io/badge/-HTML5-%23E44D27?style=flat-square&amp;logo=html5&amp;logoColor=ffffff" style="max-width:100%;"></a>
<a target="_blank" rel="noopener noreferrer" href="https://camo.githubusercontent.com/19d98ab99fe0a1a5c00ef27920be3ada8548f2476877db0598960ac2a5f8788d/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f2d435353332d2532333135373242363f7374796c653d666c61742d737175617265266c6f676f3d63737333"><img src="https://camo.githubusercontent.com/19d98ab99fe0a1a5c00ef27920be3ada8548f2476877db0598960ac2a5f8788d/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f2d435353332d2532333135373242363f7374796c653d666c61742d737175617265266c6f676f3d63737333" alt="CSS3" data-canonical-src="https://img.shields.io/badge/-CSS3-%231572B6?style=flat-square&amp;logo=css3" style="max-width:100%;"></a>


<a target="_blank" rel="noopener noreferrer" href="https://camo.githubusercontent.com/8c524f523ef3e6f319bc69a73409642542406df1d1348b8f32f106d0608d6cda/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f2d4d61726b646f776e2d3030303030303f7374796c653d666c61742d737175617265266c6f676f3d6d61726b646f776e"><img src="https://camo.githubusercontent.com/8c524f523ef3e6f319bc69a73409642542406df1d1348b8f32f106d0608d6cda/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f2d4d61726b646f776e2d3030303030303f7374796c653d666c61742d737175617265266c6f676f3d6d61726b646f776e" alt="Markdown" data-canonical-src="https://img.shields.io/badge/-Markdown-000000?style=flat-square&amp;logo=markdown" style="max-width:100%;"></a>
<a target="_blank" rel="noopener noreferrer" href="https://camo.githubusercontent.com/1da44bbbdf930b4d4c3148c845a34d954904b4d5e244fefe15f4b6c979509cd7/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f2d4e6f64656a732d3333393933333f7374796c653d666c61742d737175617265266c6f676f3d4e6f64652e6a73266c6f676f436f6c6f723d666666666666"><img src="https://camo.githubusercontent.com/1da44bbbdf930b4d4c3148c845a34d954904b4d5e244fefe15f4b6c979509cd7/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f2d4e6f64656a732d3333393933333f7374796c653d666c61742d737175617265266c6f676f3d4e6f64652e6a73266c6f676f436f6c6f723d666666666666" alt="Nodejs" data-canonical-src="https://img.shields.io/badge/-Nodejs-339933?style=flat-square&amp;logo=Node.js&amp;logoColor=ffffff" style="max-width:100%;"></a>
<a target="_blank" rel="noopener noreferrer" href="https://camo.githubusercontent.com/0fc9155456aa39c93d70ee1991ed81bd078a102ad38c2e455c941b09b179eead/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f2d6e706d2d4342333833373f7374796c653d666c61742d737175617265266c6f676f3d6e706d"><img src="https://camo.githubusercontent.com/0fc9155456aa39c93d70ee1991ed81bd078a102ad38c2e455c941b09b179eead/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f2d6e706d2d4342333833373f7374796c653d666c61742d737175617265266c6f676f3d6e706d" alt="Npm" data-canonical-src="https://img.shields.io/badge/-npm-CB3837?style=flat-square&amp;logo=npm" style="max-width:100%;"></a>

<a target="_blank" rel="noopener noreferrer" href="https://camo.githubusercontent.com/84252648d55f698d1a4e1a55c9a846d6bdebdc9e71b3a1e4c265e949ef67b9d9/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f2d53716c2532305365727665722d4343323932373f7374796c653d666c61742d737175617265266c6f676f3d6d6963726f736f66742d73716c2d736572766572266c6f676f436f6c6f723d666666666666"><img src="https://camo.githubusercontent.com/84252648d55f698d1a4e1a55c9a846d6bdebdc9e71b3a1e4c265e949ef67b9d9/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f2d53716c2532305365727665722d4343323932373f7374796c653d666c61742d737175617265266c6f676f3d6d6963726f736f66742d73716c2d736572766572266c6f676f436f6c6f723d666666666666" alt="Microsoft Sql Server" data-canonical-src="https://img.shields.io/badge/-Sql%20Server-CC2927?style=flat-square&amp;logo=microsoft-sql-server&amp;logoColor=ffffff" style="max-width:100%;"></a>


<a target="_blank" rel="noopener noreferrer" href="https://camo.githubusercontent.com/85dc47a56a4e73ae7b6e64b3b4416785497e74219ae179ae8faaaca10d5a78d9/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f2d4769744875622d3138313731373f7374796c653d666c61742d737175617265266c6f676f3d676974687562"><img src="https://camo.githubusercontent.com/85dc47a56a4e73ae7b6e64b3b4416785497e74219ae179ae8faaaca10d5a78d9/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f2d4769744875622d3138313731373f7374796c653d666c61742d737175617265266c6f676f3d676974687562" alt="GitHub" data-canonical-src="https://img.shields.io/badge/-GitHub-181717?style=flat-square&amp;logo=github" style="max-width:100%;"></a>
<a target="_blank" rel="noopener noreferrer" href="https://camo.githubusercontent.com/fe017e863574a253b32b43c18a9c5700c7b9946fe76585345148c658cb8d090d/687474703a2f2f696d672e736869656c64732e696f2f62616467652f2d5653253230436f64652d3030374143433f7374796c653d666c61742d737175617265266c6f676f3d76697375616c2d73747564696f2d636f6465266c6f676f436f6c6f723d666666666666"><img src="https://camo.githubusercontent.com/fe017e863574a253b32b43c18a9c5700c7b9946fe76585345148c658cb8d090d/687474703a2f2f696d672e736869656c64732e696f2f62616467652f2d5653253230436f64652d3030374143433f7374796c653d666c61742d737175617265266c6f676f3d76697375616c2d73747564696f2d636f6465266c6f676f436f6c6f723d666666666666" alt="VS Code" data-canonical-src="http://img.shields.io/badge/-VS%20Code-007ACC?style=flat-square&amp;logo=visual-studio-code&amp;logoColor=ffffff" style="max-width:100%;"></a>


<a target="_blank" rel="noopener noreferrer" href="https://camo.githubusercontent.com/6237d6c3bb6ad7fcb9b47d79bc786807b273945cc41f63e8557322177a69797e/687474703a2f2f696d672e736869656c64732e696f2f62616467652f2d57696e646f77732d3030373844363f7374796c653d666c61742d737175617265266c6f676f3d77696e646f7773266c6f676f436f6c6f723d666666666666"><img src="https://camo.githubusercontent.com/6237d6c3bb6ad7fcb9b47d79bc786807b273945cc41f63e8557322177a69797e/687474703a2f2f696d672e736869656c64732e696f2f62616467652f2d57696e646f77732d3030373844363f7374796c653d666c61742d737175617265266c6f676f3d77696e646f7773266c6f676f436f6c6f723d666666666666" alt="Windows" data-canonical-src="http://img.shields.io/badge/-Windows-0078D6?style=flat-square&amp;logo=windows&amp;logoColor=ffffff" style="max-width:100%;"></a></p>
<br>

<br>
  
  

<h3><a id="user-content-️-from-bgstatic" class="anchor" aria-hidden="true" href="#️-from-bgstatic"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a><g-emoji class="g-emoji" alias="star" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2b50.png">⭐️</g-emoji> From <a href="https://github.com/Cemzy">Cemzy</a></h3>
<hr>
<hr>
<p>Credit: <a href="https://github.com/Bgstatic">Bgstatic</a></p>
<p>Last Edited on: 26 February 2021</p>
</article>
  </div>

    </div>

  

  <details class="details-reset details-overlay details-overlay-dark" id="jumpto-line-details-dialog">
    <summary data-hotkey="l" aria-label="Jump to line" role="button"></summary>
    <details-dialog class="Box Box--overlay d-flex flex-column anim-fade-in fast linejump" aria-label="Jump to line" role="dialog" aria-modal="true">
      <!-- '"` --><!-- </textarea></xmp> --><form class="js-jump-to-line-form Box-body d-flex" action="" accept-charset="UTF-8" method="get">
        <input class="form-control flex-auto mr-3 linejump-input js-jump-to-line-field" type="text" placeholder="Jump to line…" aria-label="Jump to line" autofocus="">
        <button type="submit" class="btn" data-close-dialog="">Go</button>
</form>    </details-dialog>
  </details>


</div>













</div>
</div>
