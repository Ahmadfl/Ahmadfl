<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
		<title>مكتب العجلان للمحاماة &#8211; العجلان للمحاماة</title>
<meta name='robots' content='max-image-preview:large' />
<link rel='dns-prefetch' href='//www.googletagmanager.com' />
<link rel="alternate" type="application/rss+xml" title="مكتب العجلان للمحاماة &raquo; Feed" href="https://alajlanlaw.com/feed/" />
<link rel="alternate" type="application/rss+xml" title="مكتب العجلان للمحاماة &raquo; Comments Feed" href="https://alajlanlaw.com/comments/feed/" />
		<!-- This site uses the Google Analytics by MonsterInsights plugin v8.23.1 - Using Analytics tracking - https://www.monsterinsights.com/ -->
							<script src="//www.googletagmanager.com/gtag/js?id=G-7EEWLHHDD5"  data-cfasync="false" data-wpfc-render="false" async></script>
			<script data-cfasync="false" data-wpfc-render="false">
				var mi_version = '8.23.1';
				var mi_track_user = true;
				var mi_no_track_reason = '';
				
								var disableStrs = [
										'ga-disable-G-7EEWLHHDD5',
									];

				/* Function to detect opted out users */
				function __gtagTrackerIsOptedOut() {
					for (var index = 0; index < disableStrs.length; index++) {
						if (document.cookie.indexOf(disableStrs[index] + '=true') > -1) {
							return true;
						}
					}

					return false;
				}

				/* Disable tracking if the opt-out cookie exists. */
				if (__gtagTrackerIsOptedOut()) {
					for (var index = 0; index < disableStrs.length; index++) {
						window[disableStrs[index]] = true;
					}
				}

				/* Opt-out function */
				function __gtagTrackerOptout() {
					for (var index = 0; index < disableStrs.length; index++) {
						document.cookie = disableStrs[index] + '=true; expires=Thu, 31 Dec 2099 23:59:59 UTC; path=/';
						window[disableStrs[index]] = true;
					}
				}

				if ('undefined' === typeof gaOptout) {
					function gaOptout() {
						__gtagTrackerOptout();
					}
				}
								window.dataLayer = window.dataLayer || [];

				window.MonsterInsightsDualTracker = {
					helpers: {},
					trackers: {},
				};
				if (mi_track_user) {
					function __gtagDataLayer() {
						dataLayer.push(arguments);
					}

					function __gtagTracker(type, name, parameters) {
						if (!parameters) {
							parameters = {};
						}

						if (parameters.send_to) {
							__gtagDataLayer.apply(null, arguments);
							return;
						}

						if (type === 'event') {
														parameters.send_to = monsterinsights_frontend.v4_id;
							var hookName = name;
							if (typeof parameters['event_category'] !== 'undefined') {
								hookName = parameters['event_category'] + ':' + name;
							}

							if (typeof MonsterInsightsDualTracker.trackers[hookName] !== 'undefined') {
								MonsterInsightsDualTracker.trackers[hookName](parameters);
							} else {
								__gtagDataLayer('event', name, parameters);
							}
							
						} else {
							__gtagDataLayer.apply(null, arguments);
						}
					}

					__gtagTracker('js', new Date());
					__gtagTracker('set', {
						'developer_id.dZGIzZG': true,
											});
										__gtagTracker('config', 'G-7EEWLHHDD5', {"forceSSL":"true","link_attribution":"true"} );
															window.gtag = __gtagTracker;										(function () {
						/* https://developers.google.com/analytics/devguides/collection/analyticsjs/ */
						/* ga and __gaTracker compatibility shim. */
						var noopfn = function () {
							return null;
						};
						var newtracker = function () {
							return new Tracker();
						};
						var Tracker = function () {
							return null;
						};
						var p = Tracker.prototype;
						p.get = noopfn;
						p.set = noopfn;
						p.send = function () {
							var args = Array.prototype.slice.call(arguments);
							args.unshift('send');
							__gaTracker.apply(null, args);
						};
						var __gaTracker = function () {
							var len = arguments.length;
							if (len === 0) {
								return;
							}
							var f = arguments[len - 1];
							if (typeof f !== 'object' || f === null || typeof f.hitCallback !== 'function') {
								if ('send' === arguments[0]) {
									var hitConverted, hitObject = false, action;
									if ('event' === arguments[1]) {
										if ('undefined' !== typeof arguments[3]) {
											hitObject = {
												'eventAction': arguments[3],
												'eventCategory': arguments[2],
												'eventLabel': arguments[4],
												'value': arguments[5] ? arguments[5] : 1,
											}
										}
									}
									if ('pageview' === arguments[1]) {
										if ('undefined' !== typeof arguments[2]) {
											hitObject = {
												'eventAction': 'page_view',
												'page_path': arguments[2],
											}
										}
									}
									if (typeof arguments[2] === 'object') {
										hitObject = arguments[2];
									}
									if (typeof arguments[5] === 'object') {
										Object.assign(hitObject, arguments[5]);
									}
									if ('undefined' !== typeof arguments[1].hitType) {
										hitObject = arguments[1];
										if ('pageview' === hitObject.hitType) {
											hitObject.eventAction = 'page_view';
										}
									}
									if (hitObject) {
										action = 'timing' === arguments[1].hitType ? 'timing_complete' : hitObject.eventAction;
										hitConverted = mapArgs(hitObject);
										__gtagTracker('event', action, hitConverted);
									}
								}
								return;
							}

							function mapArgs(args) {
								var arg, hit = {};
								var gaMap = {
									'eventCategory': 'event_category',
									'eventAction': 'event_action',
									'eventLabel': 'event_label',
									'eventValue': 'event_value',
									'nonInteraction': 'non_interaction',
									'timingCategory': 'event_category',
									'timingVar': 'name',
									'timingValue': 'value',
									'timingLabel': 'event_label',
									'page': 'page_path',
									'location': 'page_location',
									'title': 'page_title',
									'referrer' : 'page_referrer',
								};
								for (arg in args) {
																		if (!(!args.hasOwnProperty(arg) || !gaMap.hasOwnProperty(arg))) {
										hit[gaMap[arg]] = args[arg];
									} else {
										hit[arg] = args[arg];
									}
								}
								return hit;
							}

							try {
								f.hitCallback();
							} catch (ex) {
							}
						};
						__gaTracker.create = newtracker;
						__gaTracker.getByName = newtracker;
						__gaTracker.getAll = function () {
							return [];
						};
						__gaTracker.remove = noopfn;
						__gaTracker.loaded = true;
						window['__gaTracker'] = __gaTracker;
					})();
									} else {
										console.log("");
					(function () {
						function __gtagTracker() {
							return null;
						}

						window['__gtagTracker'] = __gtagTracker;
						window['gtag'] = __gtagTracker;
					})();
									}
			</script>
				<!-- / Google Analytics by MonsterInsights -->
		<script>
window._wpemojiSettings = {"baseUrl":"https:\/\/s.w.org\/images\/core\/emoji\/14.0.0\/72x72\/","ext":".png","svgUrl":"https:\/\/s.w.org\/images\/core\/emoji\/14.0.0\/svg\/","svgExt":".svg","source":{"concatemoji":"https:\/\/alajlanlaw.com\/wp-includes\/js\/wp-emoji-release.min.js?ver=6.4.2"}};
/*! This file is auto-generated */
!function(i,n){var o,s,e;function c(e){try{var t={supportTests:e,timestamp:(new Date).valueOf()};sessionStorage.setItem(o,JSON.stringify(t))}catch(e){}}function p(e,t,n){e.clearRect(0,0,e.canvas.width,e.canvas.height),e.fillText(t,0,0);var t=new Uint32Array(e.getImageData(0,0,e.canvas.width,e.canvas.height).data),r=(e.clearRect(0,0,e.canvas.width,e.canvas.height),e.fillText(n,0,0),new Uint32Array(e.getImageData(0,0,e.canvas.width,e.canvas.height).data));return t.every(function(e,t){return e===r[t]})}function u(e,t,n){switch(t){case"flag":return n(e,"\ud83c\udff3\ufe0f\u200d\u26a7\ufe0f","\ud83c\udff3\ufe0f\u200b\u26a7\ufe0f")?!1:!n(e,"\ud83c\uddfa\ud83c\uddf3","\ud83c\uddfa\u200b\ud83c\uddf3")&&!n(e,"\ud83c\udff4\udb40\udc67\udb40\udc62\udb40\udc65\udb40\udc6e\udb40\udc67\udb40\udc7f","\ud83c\udff4\u200b\udb40\udc67\u200b\udb40\udc62\u200b\udb40\udc65\u200b\udb40\udc6e\u200b\udb40\udc67\u200b\udb40\udc7f");case"emoji":return!n(e,"\ud83e\udef1\ud83c\udffb\u200d\ud83e\udef2\ud83c\udfff","\ud83e\udef1\ud83c\udffb\u200b\ud83e\udef2\ud83c\udfff")}return!1}function f(e,t,n){var r="undefined"!=typeof WorkerGlobalScope&&self instanceof WorkerGlobalScope?new OffscreenCanvas(300,150):i.createElement("canvas"),a=r.getContext("2d",{willReadFrequently:!0}),o=(a.textBaseline="top",a.font="600 32px Arial",{});return e.forEach(function(e){o[e]=t(a,e,n)}),o}function t(e){var t=i.createElement("script");t.src=e,t.defer=!0,i.head.appendChild(t)}"undefined"!=typeof Promise&&(o="wpEmojiSettingsSupports",s=["flag","emoji"],n.supports={everything:!0,everythingExceptFlag:!0},e=new Promise(function(e){i.addEventListener("DOMContentLoaded",e,{once:!0})}),new Promise(function(t){var n=function(){try{var e=JSON.parse(sessionStorage.getItem(o));if("object"==typeof e&&"number"==typeof e.timestamp&&(new Date).valueOf()<e.timestamp+604800&&"object"==typeof e.supportTests)return e.supportTests}catch(e){}return null}();if(!n){if("undefined"!=typeof Worker&&"undefined"!=typeof OffscreenCanvas&&"undefined"!=typeof URL&&URL.createObjectURL&&"undefined"!=typeof Blob)try{var e="postMessage("+f.toString()+"("+[JSON.stringify(s),u.toString(),p.toString()].join(",")+"));",r=new Blob([e],{type:"text/javascript"}),a=new Worker(URL.createObjectURL(r),{name:"wpTestEmojiSupports"});return void(a.onmessage=function(e){c(n=e.data),a.terminate(),t(n)})}catch(e){}c(n=f(s,u,p))}t(n)}).then(function(e){for(var t in e)n.supports[t]=e[t],n.supports.everything=n.supports.everything&&n.supports[t],"flag"!==t&&(n.supports.everythingExceptFlag=n.supports.everythingExceptFlag&&n.supports[t]);n.supports.everythingExceptFlag=n.supports.everythingExceptFlag&&!n.supports.flag,n.DOMReady=!1,n.readyCallback=function(){n.DOMReady=!0}}).then(function(){return e}).then(function(){var e;n.supports.everything||(n.readyCallback(),(e=n.source||{}).concatemoji?t(e.concatemoji):e.wpemoji&&e.twemoji&&(t(e.twemoji),t(e.wpemoji)))}))}((window,document),window._wpemojiSettings);
</script>
<link rel='stylesheet' id='swiper-css' href='https://alajlanlaw.com/wp-content/plugins/testimonials-carousel-elementor/assets/css/swiper.min.css?ver=6.4.2' type='text/css' media='all' />
<style id='wp-emoji-styles-inline-css' type='text/css'>

	img.wp-smiley, img.emoji {
		display: inline !important;
		border: none !important;
		box-shadow: none !important;
		height: 1em !important;
		width: 1em !important;
		margin: 0 0.07em !important;
		vertical-align: -0.1em !important;
		background: none !important;
		padding: 0 !important;
	}
</style>
<style id='classic-theme-styles-inline-css' type='text/css'>
/*! This file is auto-generated */
.wp-block-button__link{color:#fff;background-color:#32373c;border-radius:9999px;box-shadow:none;text-decoration:none;padding:calc(.667em + 2px) calc(1.333em + 2px);font-size:1.125em}.wp-block-file__button{background:#32373c;color:#fff;text-decoration:none}
</style>
<style id='global-styles-inline-css' type='text/css'>
body{--wp--preset--color--black: #000000;--wp--preset--color--cyan-bluish-gray: #abb8c3;--wp--preset--color--white: #ffffff;--wp--preset--color--pale-pink: #f78da7;--wp--preset--color--vivid-red: #cf2e2e;--wp--preset--color--luminous-vivid-orange: #ff6900;--wp--preset--color--luminous-vivid-amber: #fcb900;--wp--preset--color--light-green-cyan: #7bdcb5;--wp--preset--color--vivid-green-cyan: #00d084;--wp--preset--color--pale-cyan-blue: #8ed1fc;--wp--preset--color--vivid-cyan-blue: #0693e3;--wp--preset--color--vivid-purple: #9b51e0;--wp--preset--gradient--vivid-cyan-blue-to-vivid-purple: linear-gradient(135deg,rgba(6,147,227,1) 0%,rgb(155,81,224) 100%);--wp--preset--gradient--light-green-cyan-to-vivid-green-cyan: linear-gradient(135deg,rgb(122,220,180) 0%,rgb(0,208,130) 100%);--wp--preset--gradient--luminous-vivid-amber-to-luminous-vivid-orange: linear-gradient(135deg,rgba(252,185,0,1) 0%,rgba(255,105,0,1) 100%);--wp--preset--gradient--luminous-vivid-orange-to-vivid-red: linear-gradient(135deg,rgba(255,105,0,1) 0%,rgb(207,46,46) 100%);--wp--preset--gradient--very-light-gray-to-cyan-bluish-gray: linear-gradient(135deg,rgb(238,238,238) 0%,rgb(169,184,195) 100%);--wp--preset--gradient--cool-to-warm-spectrum: linear-gradient(135deg,rgb(74,234,220) 0%,rgb(151,120,209) 20%,rgb(207,42,186) 40%,rgb(238,44,130) 60%,rgb(251,105,98) 80%,rgb(254,248,76) 100%);--wp--preset--gradient--blush-light-purple: linear-gradient(135deg,rgb(255,206,236) 0%,rgb(152,150,240) 100%);--wp--preset--gradient--blush-bordeaux: linear-gradient(135deg,rgb(254,205,165) 0%,rgb(254,45,45) 50%,rgb(107,0,62) 100%);--wp--preset--gradient--luminous-dusk: linear-gradient(135deg,rgb(255,203,112) 0%,rgb(199,81,192) 50%,rgb(65,88,208) 100%);--wp--preset--gradient--pale-ocean: linear-gradient(135deg,rgb(255,245,203) 0%,rgb(182,227,212) 50%,rgb(51,167,181) 100%);--wp--preset--gradient--electric-grass: linear-gradient(135deg,rgb(202,248,128) 0%,rgb(113,206,126) 100%);--wp--preset--gradient--midnight: linear-gradient(135deg,rgb(2,3,129) 0%,rgb(40,116,252) 100%);--wp--preset--font-size--small: 13px;--wp--preset--font-size--medium: 20px;--wp--preset--font-size--large: 36px;--wp--preset--font-size--x-large: 42px;--wp--preset--spacing--20: 0.44rem;--wp--preset--spacing--30: 0.67rem;--wp--preset--spacing--40: 1rem;--wp--preset--spacing--50: 1.5rem;--wp--preset--spacing--60: 2.25rem;--wp--preset--spacing--70: 3.38rem;--wp--preset--spacing--80: 5.06rem;--wp--preset--shadow--natural: 6px 6px 9px rgba(0, 0, 0, 0.2);--wp--preset--shadow--deep: 12px 12px 50px rgba(0, 0, 0, 0.4);--wp--preset--shadow--sharp: 6px 6px 0px rgba(0, 0, 0, 0.2);--wp--preset--shadow--outlined: 6px 6px 0px -3px rgba(255, 255, 255, 1), 6px 6px rgba(0, 0, 0, 1);--wp--preset--shadow--crisp: 6px 6px 0px rgba(0, 0, 0, 1);}:where(.is-layout-flex){gap: 0.5em;}:where(.is-layout-grid){gap: 0.5em;}body .is-layout-flow > .alignleft{float: left;margin-inline-start: 0;margin-inline-end: 2em;}body .is-layout-flow > .alignright{float: right;margin-inline-start: 2em;margin-inline-end: 0;}body .is-layout-flow > .aligncenter{margin-left: auto !important;margin-right: auto !important;}body .is-layout-constrained > .alignleft{float: left;margin-inline-start: 0;margin-inline-end: 2em;}body .is-layout-constrained > .alignright{float: right;margin-inline-start: 2em;margin-inline-end: 0;}body .is-layout-constrained > .aligncenter{margin-left: auto !important;margin-right: auto !important;}body .is-layout-constrained > :where(:not(.alignleft):not(.alignright):not(.alignfull)){max-width: var(--wp--style--global--content-size);margin-left: auto !important;margin-right: auto !important;}body .is-layout-constrained > .alignwide{max-width: var(--wp--style--global--wide-size);}body .is-layout-flex{display: flex;}body .is-layout-flex{flex-wrap: wrap;align-items: center;}body .is-layout-flex > *{margin: 0;}body .is-layout-grid{display: grid;}body .is-layout-grid > *{margin: 0;}:where(.wp-block-columns.is-layout-flex){gap: 2em;}:where(.wp-block-columns.is-layout-grid){gap: 2em;}:where(.wp-block-post-template.is-layout-flex){gap: 1.25em;}:where(.wp-block-post-template.is-layout-grid){gap: 1.25em;}.has-black-color{color: var(--wp--preset--color--black) !important;}.has-cyan-bluish-gray-color{color: var(--wp--preset--color--cyan-bluish-gray) !important;}.has-white-color{color: var(--wp--preset--color--white) !important;}.has-pale-pink-color{color: var(--wp--preset--color--pale-pink) !important;}.has-vivid-red-color{color: var(--wp--preset--color--vivid-red) !important;}.has-luminous-vivid-orange-color{color: var(--wp--preset--color--luminous-vivid-orange) !important;}.has-luminous-vivid-amber-color{color: var(--wp--preset--color--luminous-vivid-amber) !important;}.has-light-green-cyan-color{color: var(--wp--preset--color--light-green-cyan) !important;}.has-vivid-green-cyan-color{color: var(--wp--preset--color--vivid-green-cyan) !important;}.has-pale-cyan-blue-color{color: var(--wp--preset--color--pale-cyan-blue) !important;}.has-vivid-cyan-blue-color{color: var(--wp--preset--color--vivid-cyan-blue) !important;}.has-vivid-purple-color{color: var(--wp--preset--color--vivid-purple) !important;}.has-black-background-color{background-color: var(--wp--preset--color--black) !important;}.has-cyan-bluish-gray-background-color{background-color: var(--wp--preset--color--cyan-bluish-gray) !important;}.has-white-background-color{background-color: var(--wp--preset--color--white) !important;}.has-pale-pink-background-color{background-color: var(--wp--preset--color--pale-pink) !important;}.has-vivid-red-background-color{background-color: var(--wp--preset--color--vivid-red) !important;}.has-luminous-vivid-orange-background-color{background-color: var(--wp--preset--color--luminous-vivid-orange) !important;}.has-luminous-vivid-amber-background-color{background-color: var(--wp--preset--color--luminous-vivid-amber) !important;}.has-light-green-cyan-background-color{background-color: var(--wp--preset--color--light-green-cyan) !important;}.has-vivid-green-cyan-background-color{background-color: var(--wp--preset--color--vivid-green-cyan) !important;}.has-pale-cyan-blue-background-color{background-color: var(--wp--preset--color--pale-cyan-blue) !important;}.has-vivid-cyan-blue-background-color{background-color: var(--wp--preset--color--vivid-cyan-blue) !important;}.has-vivid-purple-background-color{background-color: var(--wp--preset--color--vivid-purple) !important;}.has-black-border-color{border-color: var(--wp--preset--color--black) !important;}.has-cyan-bluish-gray-border-color{border-color: var(--wp--preset--color--cyan-bluish-gray) !important;}.has-white-border-color{border-color: var(--wp--preset--color--white) !important;}.has-pale-pink-border-color{border-color: var(--wp--preset--color--pale-pink) !important;}.has-vivid-red-border-color{border-color: var(--wp--preset--color--vivid-red) !important;}.has-luminous-vivid-orange-border-color{border-color: var(--wp--preset--color--luminous-vivid-orange) !important;}.has-luminous-vivid-amber-border-color{border-color: var(--wp--preset--color--luminous-vivid-amber) !important;}.has-light-green-cyan-border-color{border-color: var(--wp--preset--color--light-green-cyan) !important;}.has-vivid-green-cyan-border-color{border-color: var(--wp--preset--color--vivid-green-cyan) !important;}.has-pale-cyan-blue-border-color{border-color: var(--wp--preset--color--pale-cyan-blue) !important;}.has-vivid-cyan-blue-border-color{border-color: var(--wp--preset--color--vivid-cyan-blue) !important;}.has-vivid-purple-border-color{border-color: var(--wp--preset--color--vivid-purple) !important;}.has-vivid-cyan-blue-to-vivid-purple-gradient-background{background: var(--wp--preset--gradient--vivid-cyan-blue-to-vivid-purple) !important;}.has-light-green-cyan-to-vivid-green-cyan-gradient-background{background: var(--wp--preset--gradient--light-green-cyan-to-vivid-green-cyan) !important;}.has-luminous-vivid-amber-to-luminous-vivid-orange-gradient-background{background: var(--wp--preset--gradient--luminous-vivid-amber-to-luminous-vivid-orange) !important;}.has-luminous-vivid-orange-to-vivid-red-gradient-background{background: var(--wp--preset--gradient--luminous-vivid-orange-to-vivid-red) !important;}.has-very-light-gray-to-cyan-bluish-gray-gradient-background{background: var(--wp--preset--gradient--very-light-gray-to-cyan-bluish-gray) !important;}.has-cool-to-warm-spectrum-gradient-background{background: var(--wp--preset--gradient--cool-to-warm-spectrum) !important;}.has-blush-light-purple-gradient-background{background: var(--wp--preset--gradient--blush-light-purple) !important;}.has-blush-bordeaux-gradient-background{background: var(--wp--preset--gradient--blush-bordeaux) !important;}.has-luminous-dusk-gradient-background{background: var(--wp--preset--gradient--luminous-dusk) !important;}.has-pale-ocean-gradient-background{background: var(--wp--preset--gradient--pale-ocean) !important;}.has-electric-grass-gradient-background{background: var(--wp--preset--gradient--electric-grass) !important;}.has-midnight-gradient-background{background: var(--wp--preset--gradient--midnight) !important;}.has-small-font-size{font-size: var(--wp--preset--font-size--small) !important;}.has-medium-font-size{font-size: var(--wp--preset--font-size--medium) !important;}.has-large-font-size{font-size: var(--wp--preset--font-size--large) !important;}.has-x-large-font-size{font-size: var(--wp--preset--font-size--x-large) !important;}
.wp-block-navigation a:where(:not(.wp-element-button)){color: inherit;}
:where(.wp-block-post-template.is-layout-flex){gap: 1.25em;}:where(.wp-block-post-template.is-layout-grid){gap: 1.25em;}
:where(.wp-block-columns.is-layout-flex){gap: 2em;}:where(.wp-block-columns.is-layout-grid){gap: 2em;}
.wp-block-pullquote{font-size: 1.5em;line-height: 1.6;}
</style>
<link rel='stylesheet' id='wpforms-modern-full-css' href='https://alajlanlaw.com/wp-content/plugins/wpforms-lite/assets/css/frontend/modern/wpforms-full.min.css?ver=1.8.6.2' type='text/css' media='all' />
<link rel='stylesheet' id='hello-elementor-css' href='https://alajlanlaw.com/wp-content/themes/hello-elementor/style.min.css?ver=3.0.0' type='text/css' media='all' />
<link rel='stylesheet' id='hello-elementor-theme-style-css' href='https://alajlanlaw.com/wp-content/themes/hello-elementor/theme.min.css?ver=3.0.0' type='text/css' media='all' />
<link rel='stylesheet' id='hello-elementor-header-footer-css' href='https://alajlanlaw.com/wp-content/themes/hello-elementor/header-footer.min.css?ver=3.0.0' type='text/css' media='all' />
<link rel='stylesheet' id='elementor-frontend-css' href='https://alajlanlaw.com/wp-content/plugins/elementor/assets/css/frontend-lite.min.css?ver=3.18.3' type='text/css' media='all' />
<link rel='stylesheet' id='elementor-post-6-css' href='https://alajlanlaw.com/wp-content/uploads/elementor/css/post-6.css?ver=1705265691' type='text/css' media='all' />
<link rel='stylesheet' id='elementor-global-css' href='https://alajlanlaw.com/wp-content/uploads/elementor/css/global.css?ver=1705266271' type='text/css' media='all' />
<link rel='stylesheet' id='elementor-post-7-css' href='https://alajlanlaw.com/wp-content/uploads/elementor/css/post-7.css?ver=1705418103' type='text/css' media='all' />
<link rel='stylesheet' id='google-fonts-1-css' href='https://fonts.googleapis.com/css?family=Roboto%3A100%2C100italic%2C200%2C200italic%2C300%2C300italic%2C400%2C400italic%2C500%2C500italic%2C600%2C600italic%2C700%2C700italic%2C800%2C800italic%2C900%2C900italic%7CRoboto+Slab%3A100%2C100italic%2C200%2C200italic%2C300%2C300italic%2C400%2C400italic%2C500%2C500italic%2C600%2C600italic%2C700%2C700italic%2C800%2C800italic%2C900%2C900italic%7CTajawal%3A100%2C100italic%2C200%2C200italic%2C300%2C300italic%2C400%2C400italic%2C500%2C500italic%2C600%2C600italic%2C700%2C700italic%2C800%2C800italic%2C900%2C900italic%7CRubik%3A100%2C100italic%2C200%2C200italic%2C300%2C300italic%2C400%2C400italic%2C500%2C500italic%2C600%2C600italic%2C700%2C700italic%2C800%2C800italic%2C900%2C900italic&#038;display=swap&#038;ver=6.4.2' type='text/css' media='all' />
<link rel="preconnect" href="https://fonts.gstatic.com/" crossorigin><script src="https://alajlanlaw.com/wp-content/plugins/google-analytics-for-wordpress/assets/js/frontend-gtag.min.js?ver=8.23.1" id="monsterinsights-frontend-script-js"></script>
<script data-cfasync="false" data-wpfc-render="false" id='monsterinsights-frontend-script-js-extra'>var monsterinsights_frontend = {"js_events_tracking":"true","download_extensions":"doc,pdf,ppt,zip,xls,docx,pptx,xlsx","inbound_paths":"[{\"path\":\"\\\/go\\\/\",\"label\":\"affiliate\"},{\"path\":\"\\\/recommend\\\/\",\"label\":\"affiliate\"}]","home_url":"https:\/\/alajlanlaw.com","hash_tracking":"false","v4_id":"G-7EEWLHHDD5"};</script>

<!-- Google Analytics snippet added by Site Kit -->
<script src="https://www.googletagmanager.com/gtag/js?id=GT-M63D73P" id="google_gtagjs-js" async></script>
<script id="google_gtagjs-js-after">
window.dataLayer = window.dataLayer || [];function gtag(){dataLayer.push(arguments);}
gtag('set', 'linker', {"domains":["alajlanlaw.com"]} );
gtag("js", new Date());
gtag("set", "developer_id.dZTNiMT", true);
gtag("config", "GT-M63D73P");
</script>

<!-- End Google Analytics snippet added by Site Kit -->
<link rel="https://api.w.org/" href="https://alajlanlaw.com/wp-json/" /><link rel="alternate" type="application/json" href="https://alajlanlaw.com/wp-json/wp/v2/pages/7" /><link rel="EditURI" type="application/rsd+xml" title="RSD" href="https://alajlanlaw.com/xmlrpc.php?rsd" />
<meta name="generator" content="WordPress 6.4.2" />
<link rel="canonical" href="https://alajlanlaw.com/" />
<link rel='shortlink' href='https://alajlanlaw.com/' />
<link rel="alternate" type="application/json+oembed" href="https://alajlanlaw.com/wp-json/oembed/1.0/embed?url=https%3A%2F%2Falajlanlaw.com%2F" />
<link rel="alternate" type="text/xml+oembed" href="https://alajlanlaw.com/wp-json/oembed/1.0/embed?url=https%3A%2F%2Falajlanlaw.com%2F&#038;format=xml" />
<meta name="generator" content="Site Kit by Google 1.118.0" />
<!-- Google AdSense snippet added by Site Kit -->
<meta name="google-adsense-platform-account" content="ca-host-pub-2644536267352236">
<meta name="google-adsense-platform-domain" content="sitekit.withgoogle.com">
<!-- End Google AdSense snippet added by Site Kit -->
<meta name="generator" content="Elementor 3.18.3; features: e_dom_optimization, e_optimized_assets_loading, e_optimized_css_loading, e_font_icon_svg, additional_custom_breakpoints, block_editor_assets_optimize, e_image_loading_optimization; settings: css_print_method-external, google_font-enabled, font_display-swap">

<!-- Google Tag Manager snippet added by Site Kit -->
<script>
			( function( w, d, s, l, i ) {
				w[l] = w[l] || [];
				w[l].push( {'gtm.start': new Date().getTime(), event: 'gtm.js'} );
				var f = d.getElementsByTagName( s )[0],
					j = d.createElement( s ), dl = l != 'dataLayer' ? '&l=' + l : '';
				j.async = true;
				j.src = 'https://www.googletagmanager.com/gtm.js?id=' + i + dl;
				f.parentNode.insertBefore( j, f );
			} )( window, document, 'script', 'dataLayer', 'GTM-55MQHDMG' );
			
</script>

<!-- End Google Tag Manager snippet added by Site Kit -->
<link rel="icon" href="https://alajlanlaw.com/wp-content/uploads/2024/01/cropped-logo-1-32x32.webp" sizes="32x32" />
<link rel="icon" href="https://alajlanlaw.com/wp-content/uploads/2024/01/cropped-logo-1-192x192.webp" sizes="192x192" />
<link rel="apple-touch-icon" href="https://alajlanlaw.com/wp-content/uploads/2024/01/cropped-logo-1-180x180.webp" />
<meta name="msapplication-TileImage" content="https://alajlanlaw.com/wp-content/uploads/2024/01/cropped-logo-1-270x270.webp" />
<style id="wpforms-css-vars-root">
				:root {
					--wpforms-field-border-radius: 3px;
--wpforms-field-background-color: #ffffff;
--wpforms-field-border-color: rgba( 0, 0, 0, 0.25 );
--wpforms-field-text-color: rgba( 0, 0, 0, 0.7 );
--wpforms-label-color: rgba( 0, 0, 0, 0.85 );
--wpforms-label-sublabel-color: rgba( 0, 0, 0, 0.55 );
--wpforms-label-error-color: #d63637;
--wpforms-button-border-radius: 3px;
--wpforms-button-background-color: #066aab;
--wpforms-button-text-color: #ffffff;
--wpforms-field-size-input-height: 43px;
--wpforms-field-size-input-spacing: 15px;
--wpforms-field-size-font-size: 16px;
--wpforms-field-size-line-height: 19px;
--wpforms-field-size-padding-h: 14px;
--wpforms-field-size-checkbox-size: 16px;
--wpforms-field-size-sublabel-spacing: 5px;
--wpforms-field-size-icon-size: 1;
--wpforms-label-size-font-size: 16px;
--wpforms-label-size-line-height: 19px;
--wpforms-label-size-sublabel-font-size: 14px;
--wpforms-label-size-sublabel-line-height: 17px;
--wpforms-button-size-font-size: 17px;
--wpforms-button-size-height: 41px;
--wpforms-button-size-padding-h: 15px;
--wpforms-button-size-margin-top: 10px;

				}
			</style>	<meta name="viewport" content="width=device-width, initial-scale=1.0, viewport-fit=cover" /></head>
<body class="home page-template page-template-elementor_canvas page page-id-7 elementor-default elementor-template-canvas elementor-kit-6 elementor-page elementor-page-7">
			<!-- Google Tag Manager (noscript) snippet added by Site Kit -->
		<noscript>
			<iframe src="https://www.googletagmanager.com/ns.html?id=GTM-55MQHDMG" height="0" width="0" style="display:none;visibility:hidden"></iframe>
		</noscript>
		<!-- End Google Tag Manager (noscript) snippet added by Site Kit -->
				<div data-elementor-type="wp-post" data-elementor-id="7" class="elementor elementor-7">
							<div class="elementor-element elementor-element-617098e e-flex e-con-boxed e-con e-parent" data-id="617098e" data-element_type="container" id="mainhead" data-settings="{&quot;background_background&quot;:&quot;classic&quot;,&quot;content_width&quot;:&quot;boxed&quot;}" data-core-v316-plus="true">
					<div class="e-con-inner">
		<div class="elementor-element elementor-element-4b996d8 e-con-full e-flex e-con e-child" data-id="4b996d8" data-element_type="container" data-settings="{&quot;content_width&quot;:&quot;full&quot;}">
				<div class="elementor-element elementor-element-bdb5d96 elementor-widget elementor-widget-image" data-id="bdb5d96" data-element_type="widget" data-widget_type="image.default">
				<div class="elementor-widget-container">
			<style>/*! elementor - v3.18.0 - 20-12-2023 */
.elementor-widget-image{text-align:center}.elementor-widget-image a{display:inline-block}.elementor-widget-image a img[src$=".svg"]{width:48px}.elementor-widget-image img{vertical-align:middle;display:inline-block}</style>												<img decoding="async" src="https://alajlanlaw.com/wp-content/uploads/elementor/thumbs/redlogo-qibflj3grh6t284d9ihch5dhbki0kcczb402he2qv2.png" title="redlogo" alt="redlogo" loading="lazy" />															</div>
				</div>
				</div>
		<div class="elementor-element elementor-element-fd8352e e-con-full e-flex e-con e-child" data-id="fd8352e" data-element_type="container" data-settings="{&quot;content_width&quot;:&quot;full&quot;}">
				<div class="elementor-element elementor-element-a10cb17 elementor-widget elementor-widget-heading" data-id="a10cb17" data-element_type="widget" data-widget_type="heading.default">
				<div class="elementor-widget-container">
			<style>/*! elementor - v3.18.0 - 20-12-2023 */
.elementor-heading-title{padding:0;margin:0;line-height:1}.elementor-widget-heading .elementor-heading-title[class*=elementor-size-]>a{color:inherit;font-size:inherit;line-height:inherit}.elementor-widget-heading .elementor-heading-title.elementor-size-small{font-size:15px}.elementor-widget-heading .elementor-heading-title.elementor-size-medium{font-size:19px}.elementor-widget-heading .elementor-heading-title.elementor-size-large{font-size:29px}.elementor-widget-heading .elementor-heading-title.elementor-size-xl{font-size:39px}.elementor-widget-heading .elementor-heading-title.elementor-size-xxl{font-size:59px}</style><h2 class="elementor-heading-title elementor-size-default">مكتب العجلان للمحاماة</h2>		</div>
				</div>
				<div class="elementor-element elementor-element-900f0dc elementor-widget elementor-widget-heading" data-id="900f0dc" data-element_type="widget" data-widget_type="heading.default">
				<div class="elementor-widget-container">
			<h2 class="elementor-heading-title elementor-size-default">محامي دولي مختص في قضايا الجرائم الالكترونية</h2>		</div>
				</div>
				<div class="elementor-element elementor-element-fb3d29e elementor-widget elementor-widget-mdp-modalier-elementor" data-id="fb3d29e" data-element_type="widget" id="formmodal" data-widget_type="mdp-modalier-elementor.default">
				<div class="elementor-widget-container">
			
        <div id="mdp-modalier-contactus"
             class="mdp-modalier-container-fb3d29e mdp-modalier-box"
             data-post-id="7"
             data-widget-id="fb3d29e"
             data-type="section"
             data-typeEvents="timeout"
             data-modalierScroll="0"
             data-modalierTimeout="20000"
             data-fullscreen="false"
             data-animation="fade"
             data-animationSpeed="300"
             data-closeViaKeypress="false"
             data-displayCloseButton="false"
             data-closeViaOverlay="true"
             data-popupTitle=""
             data-closeText=""
             data-closeAriaLabel=""
             data-galleryActiveClass=""
             data-outerControls="false"
             data-width="500"
             data-height="900"
             data-background-contactus="#00000000"
             data-opacity="0.7"
             data-openLimit="0"
             data-contentSource="contactus"
                     >

        <div style="text-align: ;"><a href="#contactus" class="mpd-modalier-button contactus mdp-display-none"></a></div>        </div>

        
        <script>
            document.addEventListener('DOMContentLoaded', function () {

                let sectionID = document.querySelectorAll( '#contactus' );
                for( let i = 0; sectionID.length - 1 >= i; i++ ){
                    let classContains = sectionID[i].classList.contains( 'contactus');
                    if( classContains !== undefined  ){
                        sectionID[i].classList.remove( 'contactus' );
                    }
                }

                                sessionStorage.setItem( 'mdp-launches-contactus', 0 );
                
	            
                var observer_fb3d29e = new MutationObserver( list => {

                    let widthDevice, heightDevice;

                    if( list[0].target.attributes[1] !== undefined ){
                        let newDevice = list[0].target.attributes[1].nodeValue;

                        if( newDevice === 'desktop' ){
                            widthDevice  = 500;
                            heightDevice = 900;
                        }else if( newDevice === 'tablet' ){
                            widthDevice  = 400;
                            heightDevice = 450;
                        } else if( newDevice === 'mobile' ){
                            widthDevice  = 300;
                            heightDevice = 700;
                        }

                        window.Modalier( 'contactus', widthDevice, heightDevice );

                    }

                } );

                observer_fb3d29e.observe( document.body, { attributes: true });

            } );

        </script>

        		</div>
				</div>
				<div class="elementor-element elementor-element-e684288 elementor-widget elementor-widget-image" data-id="e684288" data-element_type="widget" data-settings="{&quot;_animation_mobile&quot;:&quot;slideInUp&quot;}" data-widget_type="image.default">
				<div class="elementor-widget-container">
															<img fetchpriority="high" decoding="async" width="507" height="492" src="https://alajlanlaw.com/wp-content/uploads/2024/01/WhatsApp_Image_2022-10-02_at_15.36.17__1_-removebg-preview.webp" class="attachment-large size-large wp-image-28" alt="" srcset="https://alajlanlaw.com/wp-content/uploads/2024/01/WhatsApp_Image_2022-10-02_at_15.36.17__1_-removebg-preview.webp 507w, https://alajlanlaw.com/wp-content/uploads/2024/01/WhatsApp_Image_2022-10-02_at_15.36.17__1_-removebg-preview-300x291.webp 300w" sizes="(max-width: 507px) 100vw, 507px" />															</div>
				</div>
				<div class="elementor-element elementor-element-4ae91d2 elementor-align-center elementor-widget elementor-widget-button" data-id="4ae91d2" data-element_type="widget" data-widget_type="button.default">
				<div class="elementor-widget-container">
					<div class="elementor-button-wrapper">
			<a class="elementor-button elementor-button-link elementor-size-sm" href="#maincontactform" id="bt">
						<span class="elementor-button-content-wrapper">
						<span class="elementor-button-icon elementor-align-icon-right">
				<svg aria-hidden="true" class="e-font-icon-svg e-fas-mouse-pointer" viewBox="0 0 320 512" xmlns="http://www.w3.org/2000/svg"><path d="M302.189 329.126H196.105l55.831 135.993c3.889 9.428-.555 19.999-9.444 23.999l-49.165 21.427c-9.165 4-19.443-.571-23.332-9.714l-53.053-129.136-86.664 89.138C18.729 472.71 0 463.554 0 447.977V18.299C0 1.899 19.921-6.096 30.277 5.443l284.412 292.542c11.472 11.179 3.007 31.141-12.5 31.141z"></path></svg>			</span>
						<span class="elementor-button-text">سجل لنتواصل معك  </span>
		</span>
					</a>
		</div>
				</div>
				</div>
				</div>
		<div class="elementor-element elementor-element-6e89af1 e-con-full e-flex e-con e-child" data-id="6e89af1" data-element_type="container" data-settings="{&quot;content_width&quot;:&quot;full&quot;}">
				<div class="elementor-element elementor-element-762ece3 elementor-widget elementor-widget-html" data-id="762ece3" data-element_type="widget" data-widget_type="html.default">
				<div class="elementor-widget-container">
			<style>
    #mainhead
    {
        direction:rtl;
    }
    #bt
    {
        direction:ltr;
    }
    #aboutcontent
    {
        direction:rtl;
    }
    .e-con-inner
    {
        direction:rtl;
    }
    .e-con-inner #contactform
    {
        
    }
    
  .e-con-inner   .elementor-heading-title
    {
        text-align:center;
    }
    .wpcf7 form.failed .wpcf7-response-output, .wpcf7 form.aborted .wpcf7-response-output
    {
            border-color: #5cb85c;
    text-align: center;
    font-family: 'Tajawal';
    font-weight:bold;
    }
    #formmodal
    {
       
    }
</style>
		</div>
				</div>
				</div>
		<div class="elementor-element elementor-element-77aba12 e-con-full e-flex e-con e-child" data-id="77aba12" data-element_type="container" data-settings="{&quot;content_width&quot;:&quot;full&quot;}">
				<div class="elementor-element elementor-element-6e0854b elementor-widget elementor-widget-counter" data-id="6e0854b" data-element_type="widget" data-widget_type="counter.default">
				<div class="elementor-widget-container">
			<style>/*! elementor - v3.18.0 - 20-12-2023 */
.elementor-counter .elementor-counter-number-wrapper{display:flex;font-size:69px;font-weight:600;line-height:1}.elementor-counter .elementor-counter-number-prefix,.elementor-counter .elementor-counter-number-suffix{flex-grow:1;white-space:pre-wrap}.elementor-counter .elementor-counter-number-prefix{text-align:right}.elementor-counter .elementor-counter-number-suffix{text-align:left}.elementor-counter .elementor-counter-title{text-align:center;font-size:19px;font-weight:400;line-height:2.5}</style>		<div class="elementor-counter">
			<div class="elementor-counter-number-wrapper">
				<span class="elementor-counter-number-prefix"></span>
				<span class="elementor-counter-number" data-duration="2000" data-to-value="2467" data-from-value="0" data-delimiter=",">0</span>
				<span class="elementor-counter-number-suffix"></span>
			</div>
					</div>
				</div>
				</div>
				<div class="elementor-element elementor-element-0e7a9c2 elementor-widget elementor-widget-heading" data-id="0e7a9c2" data-element_type="widget" data-widget_type="heading.default">
				<div class="elementor-widget-container">
			<h2 class="elementor-heading-title elementor-size-default">زبائن في السنة الأخيرة</h2>		</div>
				</div>
				</div>
		<div class="elementor-element elementor-element-7e53382 e-con-full e-flex e-con e-child" data-id="7e53382" data-element_type="container" data-settings="{&quot;content_width&quot;:&quot;full&quot;}">
				<div class="elementor-element elementor-element-0be7542 elementor-widget elementor-widget-counter" data-id="0be7542" data-element_type="widget" data-widget_type="counter.default">
				<div class="elementor-widget-container">
					<div class="elementor-counter">
			<div class="elementor-counter-number-wrapper">
				<span class="elementor-counter-number-prefix"></span>
				<span class="elementor-counter-number" data-duration="2000" data-to-value="152" data-from-value="0" data-delimiter=",">0</span>
				<span class="elementor-counter-number-suffix"></span>
			</div>
					</div>
				</div>
				</div>
				<div class="elementor-element elementor-element-2ecd38b elementor-widget elementor-widget-heading" data-id="2ecd38b" data-element_type="widget" data-widget_type="heading.default">
				<div class="elementor-widget-container">
			<h2 class="elementor-heading-title elementor-size-default">القضايا المحلولة في الشهر الأخير</h2>		</div>
				</div>
				</div>
		<div class="elementor-element elementor-element-f954220 e-con-full e-flex e-con e-child" data-id="f954220" data-element_type="container" data-settings="{&quot;content_width&quot;:&quot;full&quot;}">
				<div class="elementor-element elementor-element-3bf14ee elementor-widget elementor-widget-counter" data-id="3bf14ee" data-element_type="widget" data-widget_type="counter.default">
				<div class="elementor-widget-container">
					<div class="elementor-counter">
			<div class="elementor-counter-number-wrapper">
				<span class="elementor-counter-number-prefix"></span>
				<span class="elementor-counter-number" data-duration="2000" data-to-value="13" data-from-value="0" data-delimiter=",">0</span>
				<span class="elementor-counter-number-suffix"></span>
			</div>
					</div>
				</div>
				</div>
				<div class="elementor-element elementor-element-fb0b956 elementor-widget elementor-widget-heading" data-id="fb0b956" data-element_type="widget" data-widget_type="heading.default">
				<div class="elementor-widget-container">
			<h2 class="elementor-heading-title elementor-size-default">طاقم محامين متخصصين</h2>		</div>
				</div>
				</div>
					</div>
				</div>
		<div class="elementor-element elementor-element-4624952 e-flex e-con-boxed e-con e-parent" data-id="4624952" data-element_type="container" data-settings="{&quot;background_background&quot;:&quot;classic&quot;,&quot;content_width&quot;:&quot;boxed&quot;}" data-core-v316-plus="true">
					<div class="e-con-inner">
		<div class="elementor-element elementor-element-6073d26 e-con-full e-flex e-con e-child" data-id="6073d26" data-element_type="container" data-settings="{&quot;content_width&quot;:&quot;full&quot;}">
		<div class="elementor-element elementor-element-4d46a85 e-con-full e-flex e-con e-child" data-id="4d46a85" data-element_type="container" data-settings="{&quot;content_width&quot;:&quot;full&quot;,&quot;background_background&quot;:&quot;classic&quot;}">
				<div class="elementor-element elementor-element-171c4fa elementor-widget elementor-widget-heading" data-id="171c4fa" data-element_type="widget" data-widget_type="heading.default">
				<div class="elementor-widget-container">
			<h2 class="elementor-heading-title elementor-size-default">خدماتنا</h2>		</div>
				</div>
				</div>
				<div class="elementor-element elementor-element-8305d23 elementor-widget elementor-widget-heading" data-id="8305d23" data-element_type="widget" data-widget_type="heading.default">
				<div class="elementor-widget-container">
			<h2 class="elementor-heading-title elementor-size-default">نسعد دائما لتقدمة الافضل لزبائننا
</h2>		</div>
				</div>
				</div>
		<div class="elementor-element elementor-element-cbaf569 e-con-full e-flex e-con e-child" data-id="cbaf569" data-element_type="container" data-settings="{&quot;content_width&quot;:&quot;full&quot;}">
				<div class="elementor-element elementor-element-2079032 elementor-view-default elementor-widget elementor-widget-icon" data-id="2079032" data-element_type="widget" data-widget_type="icon.default">
				<div class="elementor-widget-container">
					<div class="elementor-icon-wrapper">
			<div class="elementor-icon">
			<svg aria-hidden="true" class="e-font-icon-svg e-far-money-bill-alt" viewBox="0 0 640 512" xmlns="http://www.w3.org/2000/svg"><path d="M320 144c-53.02 0-96 50.14-96 112 0 61.85 42.98 112 96 112 53 0 96-50.13 96-112 0-61.86-42.98-112-96-112zm40 168c0 4.42-3.58 8-8 8h-64c-4.42 0-8-3.58-8-8v-16c0-4.42 3.58-8 8-8h16v-55.44l-.47.31a7.992 7.992 0 0 1-11.09-2.22l-8.88-13.31a7.992 7.992 0 0 1 2.22-11.09l15.33-10.22a23.99 23.99 0 0 1 13.31-4.03H328c4.42 0 8 3.58 8 8v88h16c4.42 0 8 3.58 8 8v16zM608 64H32C14.33 64 0 78.33 0 96v320c0 17.67 14.33 32 32 32h576c17.67 0 32-14.33 32-32V96c0-17.67-14.33-32-32-32zm-16 272c-35.35 0-64 28.65-64 64H112c0-35.35-28.65-64-64-64V176c35.35 0 64-28.65 64-64h416c0 35.35 28.65 64 64 64v160z"></path></svg>			</div>
		</div>
				</div>
				</div>
				<div class="elementor-element elementor-element-21660a1 elementor-widget elementor-widget-heading" data-id="21660a1" data-element_type="widget" data-widget_type="heading.default">
				<div class="elementor-widget-container">
			<h2 class="elementor-heading-title elementor-size-default">قضايا غسيل الأموال
</h2>		</div>
				</div>
				<div class="elementor-element elementor-element-6dfc832 elementor-align-center elementor-widget elementor-widget-button" data-id="6dfc832" data-element_type="widget" data-widget_type="button.default">
				<div class="elementor-widget-container">
					<div class="elementor-button-wrapper">
			<a class="elementor-button elementor-button-link elementor-size-sm" href="/قضايا-غسيل-الأموال">
						<span class="elementor-button-content-wrapper">
						<span class="elementor-button-text">اقرأ المزيد</span>
		</span>
					</a>
		</div>
				</div>
				</div>
				</div>
		<div class="elementor-element elementor-element-9e574ff e-con-full e-flex e-con e-child" data-id="9e574ff" data-element_type="container" data-settings="{&quot;content_width&quot;:&quot;full&quot;}">
				<div class="elementor-element elementor-element-995de9d elementor-view-default elementor-widget elementor-widget-icon" data-id="995de9d" data-element_type="widget" data-widget_type="icon.default">
				<div class="elementor-widget-container">
					<div class="elementor-icon-wrapper">
			<div class="elementor-icon">
			<svg aria-hidden="true" class="e-font-icon-svg e-far-chart-bar" viewBox="0 0 512 512" xmlns="http://www.w3.org/2000/svg"><path d="M396.8 352h22.4c6.4 0 12.8-6.4 12.8-12.8V108.8c0-6.4-6.4-12.8-12.8-12.8h-22.4c-6.4 0-12.8 6.4-12.8 12.8v230.4c0 6.4 6.4 12.8 12.8 12.8zm-192 0h22.4c6.4 0 12.8-6.4 12.8-12.8V140.8c0-6.4-6.4-12.8-12.8-12.8h-22.4c-6.4 0-12.8 6.4-12.8 12.8v198.4c0 6.4 6.4 12.8 12.8 12.8zm96 0h22.4c6.4 0 12.8-6.4 12.8-12.8V204.8c0-6.4-6.4-12.8-12.8-12.8h-22.4c-6.4 0-12.8 6.4-12.8 12.8v134.4c0 6.4 6.4 12.8 12.8 12.8zM496 400H48V80c0-8.84-7.16-16-16-16H16C7.16 64 0 71.16 0 80v336c0 17.67 14.33 32 32 32h464c8.84 0 16-7.16 16-16v-16c0-8.84-7.16-16-16-16zm-387.2-48h22.4c6.4 0 12.8-6.4 12.8-12.8v-70.4c0-6.4-6.4-12.8-12.8-12.8h-22.4c-6.4 0-12.8 6.4-12.8 12.8v70.4c0 6.4 6.4 12.8 12.8 12.8z"></path></svg>			</div>
		</div>
				</div>
				</div>
				<div class="elementor-element elementor-element-1eaad63 elementor-widget elementor-widget-heading" data-id="1eaad63" data-element_type="widget" data-widget_type="heading.default">
				<div class="elementor-widget-container">
			<h2 class="elementor-heading-title elementor-size-default">قضايا تداول الفوركس
</h2>		</div>
				</div>
				<div class="elementor-element elementor-element-e5d75ec elementor-align-center elementor-widget elementor-widget-button" data-id="e5d75ec" data-element_type="widget" data-widget_type="button.default">
				<div class="elementor-widget-container">
					<div class="elementor-button-wrapper">
			<a class="elementor-button elementor-button-link elementor-size-sm" href="/قضايا-تداول-الفوركس">
						<span class="elementor-button-content-wrapper">
						<span class="elementor-button-text">اقرأ المزيد</span>
		</span>
					</a>
		</div>
				</div>
				</div>
				</div>
		<div class="elementor-element elementor-element-330a777 e-con-full e-flex e-con e-child" data-id="330a777" data-element_type="container" data-settings="{&quot;content_width&quot;:&quot;full&quot;}">
				<div class="elementor-element elementor-element-7c3865f elementor-view-default elementor-widget elementor-widget-icon" data-id="7c3865f" data-element_type="widget" data-widget_type="icon.default">
				<div class="elementor-widget-container">
					<div class="elementor-icon-wrapper">
			<div class="elementor-icon">
			<svg aria-hidden="true" class="e-font-icon-svg e-fas-theater-masks" viewBox="0 0 640 512" xmlns="http://www.w3.org/2000/svg"><path d="M206.86 245.15c-35.88 10.45-59.95 41.2-57.53 74.1 11.4-12.72 28.81-23.7 49.9-30.92l7.63-43.18zM95.81 295L64.08 115.49c-.29-1.62.28-2.62.24-2.65 57.76-32.06 123.12-49.01 189.01-49.01 1.61 0 3.23.17 4.85.19 13.95-13.47 31.73-22.83 51.59-26 18.89-3.02 38.05-4.55 57.18-5.32-9.99-13.95-24.48-24.23-41.77-27C301.27 1.89 277.24 0 253.32 0 176.66 0 101.02 19.42 33.2 57.06 9.03 70.48-3.92 98.48 1.05 126.58l31.73 179.51c14.23 80.52 136.33 142.08 204.45 142.08 3.59 0 6.75-.46 10.01-.8-13.52-17.08-28.94-40.48-39.5-67.58-47.61-12.98-106.06-51.62-111.93-84.79zm97.55-137.46c-.73-4.12-2.23-7.87-4.07-11.4-8.25 8.91-20.67 15.75-35.32 18.32-14.65 2.58-28.67.4-39.48-5.17-.52 3.94-.64 7.98.09 12.1 3.84 21.7 24.58 36.19 46.34 32.37 21.75-3.82 36.28-24.52 32.44-46.22zM606.8 120.9c-88.98-49.38-191.43-67.41-291.98-51.35-27.31 4.36-49.08 26.26-54.04 54.36l-31.73 179.51c-15.39 87.05 95.28 196.27 158.31 207.35 63.03 11.09 204.47-53.79 219.86-140.84l31.73-179.51c4.97-28.11-7.98-56.11-32.15-69.52zm-273.24 96.8c3.84-21.7 24.58-36.19 46.34-32.36 21.76 3.83 36.28 24.52 32.45 46.22-.73 4.12-2.23 7.87-4.07 11.4-8.25-8.91-20.67-15.75-35.32-18.32-14.65-2.58-28.67-.4-39.48 5.17-.53-3.95-.65-7.99.08-12.11zm70.47 198.76c-55.68-9.79-93.52-59.27-89.04-112.9 20.6 25.54 56.21 46.17 99.49 53.78 43.28 7.61 83.82.37 111.93-16.6-14.18 51.94-66.71 85.51-122.38 75.72zm130.3-151.34c-8.25-8.91-20.68-15.75-35.33-18.32-14.65-2.58-28.67-.4-39.48 5.17-.52-3.94-.64-7.98.09-12.1 3.84-21.7 24.58-36.19 46.34-32.37 21.75 3.83 36.28 24.52 32.45 46.22-.73 4.13-2.23 7.88-4.07 11.4z"></path></svg>			</div>
		</div>
				</div>
				</div>
				<div class="elementor-element elementor-element-8469779 elementor-widget elementor-widget-heading" data-id="8469779" data-element_type="widget" data-widget_type="heading.default">
				<div class="elementor-widget-container">
			<h2 class="elementor-heading-title elementor-size-default">قضايا الجرائم الإلكترونية</h2>		</div>
				</div>
				<div class="elementor-element elementor-element-083833e elementor-align-center elementor-widget elementor-widget-button" data-id="083833e" data-element_type="widget" data-widget_type="button.default">
				<div class="elementor-widget-container">
					<div class="elementor-button-wrapper">
			<a class="elementor-button elementor-button-link elementor-size-sm" href="/قضايا-الجرائم-الإلكترونية">
						<span class="elementor-button-content-wrapper">
						<span class="elementor-button-text">اقرأ المزيد</span>
		</span>
					</a>
		</div>
				</div>
				</div>
				</div>
		<div class="elementor-element elementor-element-e15e944 e-con-full e-flex e-con e-child" data-id="e15e944" data-element_type="container" data-settings="{&quot;content_width&quot;:&quot;full&quot;}">
				<div class="elementor-element elementor-element-b72b410 elementor-view-default elementor-widget elementor-widget-icon" data-id="b72b410" data-element_type="widget" data-widget_type="icon.default">
				<div class="elementor-widget-container">
					<div class="elementor-icon-wrapper">
			<div class="elementor-icon">
			<svg aria-hidden="true" class="e-font-icon-svg e-fas-laptop-house" viewBox="0 0 640 512" xmlns="http://www.w3.org/2000/svg"><path d="M272,288H208a16,16,0,0,1-16-16V208a16,16,0,0,1,16-16h64a16,16,0,0,1,16,16v37.12C299.11,232.24,315,224,332.8,224H469.74l6.65-7.53A16.51,16.51,0,0,0,480,207a16.31,16.31,0,0,0-4.75-10.61L416,144V48a16,16,0,0,0-16-16H368a16,16,0,0,0-16,16V87.3L263.5,8.92C258,4,247.45,0,240.05,0s-17.93,4-23.47,8.92L4.78,196.42A16.15,16.15,0,0,0,0,207a16.4,16.4,0,0,0,3.55,9.39L22.34,237.7A16.22,16.22,0,0,0,33,242.48,16.51,16.51,0,0,0,42.34,239L64,219.88V384a32,32,0,0,0,32,32H272ZM629.33,448H592V288c0-17.67-12.89-32-28.8-32H332.8c-15.91,0-28.8,14.33-28.8,32V448H266.67A10.67,10.67,0,0,0,256,458.67v10.66A42.82,42.82,0,0,0,298.6,512H597.4A42.82,42.82,0,0,0,640,469.33V458.67A10.67,10.67,0,0,0,629.33,448ZM544,448H352V304H544Z"></path></svg>			</div>
		</div>
				</div>
				</div>
				<div class="elementor-element elementor-element-1a42d29 elementor-widget elementor-widget-heading" data-id="1a42d29" data-element_type="widget" data-widget_type="heading.default">
				<div class="elementor-widget-container">
			<h2 class="elementor-heading-title elementor-size-default">قضايا النصب و الإحتيال</h2>		</div>
				</div>
				<div class="elementor-element elementor-element-d41160f elementor-align-center elementor-widget elementor-widget-button" data-id="d41160f" data-element_type="widget" data-widget_type="button.default">
				<div class="elementor-widget-container">
					<div class="elementor-button-wrapper">
			<a class="elementor-button elementor-button-link elementor-size-sm" href="/قضايا-النصب-و-الإحتيال">
						<span class="elementor-button-content-wrapper">
						<span class="elementor-button-text">اقرأ المزيد</span>
		</span>
					</a>
		</div>
				</div>
				</div>
				</div>
		<div class="elementor-element elementor-element-0c3bf76 e-con-full e-flex e-con e-child" data-id="0c3bf76" data-element_type="container" data-settings="{&quot;content_width&quot;:&quot;full&quot;}">
				<div class="elementor-element elementor-element-bff6040 elementor-view-default elementor-widget elementor-widget-icon" data-id="bff6040" data-element_type="widget" data-widget_type="icon.default">
				<div class="elementor-widget-container">
					<div class="elementor-icon-wrapper">
			<div class="elementor-icon">
			<svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="489" height="489" viewBox="0 0 489 489"><image x="16" y="36" width="457" height="435" xlink:href="data:img/png;base64,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"></image></svg>			</div>
		</div>
				</div>
				</div>
				<div class="elementor-element elementor-element-93df964 elementor-widget elementor-widget-heading" data-id="93df964" data-element_type="widget" data-widget_type="heading.default">
				<div class="elementor-widget-container">
			<h2 class="elementor-heading-title elementor-size-default">قضايا الإحتيال التجارية - المالية - العقارية
</h2>		</div>
				</div>
				<div class="elementor-element elementor-element-1571d27 elementor-align-center elementor-widget elementor-widget-button" data-id="1571d27" data-element_type="widget" data-widget_type="button.default">
				<div class="elementor-widget-container">
					<div class="elementor-button-wrapper">
			<a class="elementor-button elementor-button-link elementor-size-sm" href="/قضايا-الإحتيال-التجارية-المالية-العق/">
						<span class="elementor-button-content-wrapper">
						<span class="elementor-button-text">اقرأ المزيد</span>
		</span>
					</a>
		</div>
				</div>
				</div>
				</div>
					</div>
				</div>
		<div class="elementor-element elementor-element-5462fc3 e-flex e-con-boxed e-con e-parent" data-id="5462fc3" data-element_type="container" id="aboutcontent" data-settings="{&quot;background_background&quot;:&quot;classic&quot;,&quot;content_width&quot;:&quot;boxed&quot;}" data-core-v316-plus="true">
					<div class="e-con-inner">
		<div class="elementor-element elementor-element-cabbb69 e-con-full e-flex e-con e-child" data-id="cabbb69" data-element_type="container" data-settings="{&quot;content_width&quot;:&quot;full&quot;}">
				<div class="elementor-element elementor-element-7d88b2d elementor-widget elementor-widget-image" data-id="7d88b2d" data-element_type="widget" data-widget_type="image.default">
				<div class="elementor-widget-container">
															<img decoding="async" width="800" height="600" src="https://alajlanlaw.com/wp-content/uploads/2024/01/pngwing.com_.webp" class="attachment-large size-large wp-image-76" alt="" srcset="https://alajlanlaw.com/wp-content/uploads/2024/01/pngwing.com_.webp 800w, https://alajlanlaw.com/wp-content/uploads/2024/01/pngwing.com_-300x225.webp 300w, https://alajlanlaw.com/wp-content/uploads/2024/01/pngwing.com_-768x576.webp 768w" sizes="(max-width: 800px) 100vw, 800px" />															</div>
				</div>
				</div>
		<div class="elementor-element elementor-element-d58ad2c e-con-full e-flex e-con e-child" data-id="d58ad2c" data-element_type="container" data-settings="{&quot;content_width&quot;:&quot;full&quot;}">
				<div class="elementor-element elementor-element-78b4254 elementor-widget elementor-widget-heading" data-id="78b4254" data-element_type="widget" data-widget_type="heading.default">
				<div class="elementor-widget-container">
			<h2 class="elementor-heading-title elementor-size-default">من نحن</h2>		</div>
				</div>
				<div class="elementor-element elementor-element-e1570e7 elementor-widget-mobile__width-inherit elementor-widget elementor-widget-heading" data-id="e1570e7" data-element_type="widget" data-widget_type="heading.default">
				<div class="elementor-widget-container">
			<h2 class="elementor-heading-title elementor-size-default">مكتب العجلان – مختص في تقديم حلول بقضايا الجرائم الإلكترونية واسترجاع الأموال من الشركات الوهمية النصابة

</h2>		</div>
				</div>
				<div class="elementor-element elementor-element-3a2c6fe elementor-widget elementor-widget-heading" data-id="3a2c6fe" data-element_type="widget" id="maincontent" data-widget_type="heading.default">
				<div class="elementor-widget-container">
			<h2 class="elementor-heading-title elementor-size-default">مكتب العجلان للمحاماة، هو مكتب محاماة دولي أثبت بجدارة خلال السنوات الماضية في العمل بالمجال القانوني وفي تقديم حلول بقضايا الجرائم الالكترونية . منذ البداية حرص السيد فهد العجلان على بناء سمعة طيبة مع عملائه، هذه السمعة كانت نتيجة عمل فريق المكتب الدؤوب على استرجاع أموال العملاء المنهوبة من شركات النصب والاحتيال المنتشرة عبر النت في الآونة الأخيرة.

</h2>		</div>
				</div>
				<div class="elementor-element elementor-element-ac881ab elementor-widget elementor-widget-html"
