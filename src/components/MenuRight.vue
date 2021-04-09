<template>
	<div class="menu-right art-menu-bar">
		<div class="art-menu-bar-frame">
			<!-- menu bar header -->
			<div class="art-menu-bar-header">
				<!-- menu bar button -->
				<a class="art-menu-bar-btn" href="#.">
					<v-icon>mdi mdi-menu</v-icon>
					<!-- icon -->
				</a>
				<!-- menu bar button end -->
			</div>
			<!-- menu bar header end -->

			<!-- current page title -->
			<div class="art-current-page">
				<a href="/nazar/arter-demo/home.html">Home</a>
			</div>
			<!-- current page title end -->

			<!-- scroll frame -->
			<div class="art-scroll-frame">
				<!-- menu -->
				<nav id="swupMenu" data-swup="1">
					<!-- menu list -->
					<ul class="main-menu">
						<!-- menu item -->
						<li class="menu-item current-menu-item">
							<a href="/nazar/arter-demo/home.html">Home</a>
						</li>
						<!-- menu item -->

						<!-- menu item -->
						<li class="menu-item">
							<a href="/nazar/arter-demo/history.html">History</a>
						</li>
						<!-- menu item -->
						<li class="menu-item">
							<a href="/nazar/arter-demo/contact.html">Contact</a>
						</li>
						<!-- menu item -->
						<li class="menu-item menu-item-has-children">
							<a href="#.">Blog</a>
							<!-- sub menu -->
							<ul class="sub-menu">
								<!-- lvl 2 nav link -->
								<li class="menu-item">
									<a href="/nazar/arter-demo/blog-2-col.html">2 column</a>
								</li>
								<!-- lvl 2 nav link -->
								<li class="menu-item">
									<a href="/nazar/arter-demo/blog-3-col.html">3 column</a>
								</li>
								<!-- lvl 2 nav link -->
								<li class="menu-item">
									<a href="/nazar/arter-demo/blog-post.html">Publication</a>
								</li>
							</ul>
							<!-- sub menu end -->
						</li>
						<!-- menu item -->
						<li class="menu-item">
							<a href="onepage.html" target="_blank">Onepage</a>
						</li>
					</ul>
					<!-- menu list end -->
				</nav>
				<!-- menu end -->

				<!-- language change -->
				<ul class="art-language-change">
					<!-- language item -->
					<li>
						<a href="#.">FR</a>
					</li>
					<!-- language item -->
					<li class="art-active-lang">
						<a href="#.">EN</a>
					</li>
				</ul>
				<!-- language change end -->
			</div>
			<!-- scroll frame end -->
		</div>
	</div>
</template>

<script>
export default {};
</script>

<style lang="sass">
#app .container-main .menu-right
    background: #20202a
    width: 230px
    height: calc(100vh - 30px)
    position: absolute
    z-index: 99
    right: -152px
    top: 0
    bottom: 0
    -webkit-box-shadow: 0 3px 8px 0 rgba(15, 15, 20, 0.2)
    box-shadow: 0 3px 8px 0 rgba(15, 15, 20, 0.2)
    -webkit-transition: 0.55s ease-in-out
    transition: 0.55s ease-in-out

#app .container-main .menu-right .art-menu-bar a:first-child
    visibility: visible
    opacity: 1
    display: block

#app .container-main .menu-right .art-menu-bar-frame
    position: relative

#app .container-main .menu-right .art-menu-bar-frame .art-menu-bar-header
    width: 100%
    height: 70px
    display: -webkit-box
    display: -ms-flexbox
    display: flex
    -webkit-box-pack: start
    -ms-flex-pack: start
    justify-content: flex-start
    -webkit-box-align: center
    -ms-flex-align: center
    align-items: center
    position: absolute
    top: 0
    left: 0
    z-index: 9
    -webkit-box-shadow: 0 1px 4px 0 rgba(15, 15, 20, 0.1)
    box-shadow: 0 1px 4px 0 rgba(15, 15, 20, 0.1)
    background: linear-gradient(159deg, rgba(37, 37, 50, 0.98) 0%, rgba(35, 35, 45, 0.98) 100%)

#app .container-main .menu-right .art-menu-bar-frame .art-menu-bar-header .art-menu-bar-btn
    pointer-events: all

#app .container-main .menu-right .art-menu-bar .art-current-page
    width: 200px
    -webkit-transform: rotate(90deg)
    transform: rotate(90deg)
    color: #fafafc
    position: absolute
    overflow: hidden
    top: 200px
    opacity: 1
    left: -62px
    text-transform: uppercase
    font-size: 11px
    opacity: 1
    letter-spacing: 1px
    font-weight: 500
    -webkit-transition: 0.4s ease-in-out
    transition: 0.4s ease-in-out
</style>