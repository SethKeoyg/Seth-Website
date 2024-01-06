<html lang="en" style="--vh: 5.54px; --vw: 8.3px;"><head><link href="https://www.googletagmanager.com/gtm.js?id=GTM-PRM8BWR" rel="preload" as="script"><link rel="icon" href="https://cdn.now.gg/apps-content/common/img/favicon.ico"><link rel="icon" href="https://cdn.now.gg/apps-content/common/img/favicon-32.ico" sizes="32x32"><link rel="icon" href="https://cdn.now.gg/apps-content/common/img/favicon-48.ico" sizes="48X48"><link rel="icon" href="https://cdn.now.gg/apps-content/common/img/favicon-96.ico" sizes="96X96"><link rel="icon" href="https://cdn.now.gg/apps-content/common/img/favicon-192.ico" sizes="192x192"><link rel="preload" as="script" href="https://www.googletagservices.com/tag/js/gpt.js?v=1704501605"><link rel="preconnect" href="https://fonts.googleapis.com"><link rel="preconnect" href="https://cdn.now.gg"><link rel="preconnect" href="https://fonts.gstatic.com" crossorigin="crossOrigin"><meta name="msapplication-TileImage" content="https://cdn.now.gg/apps-content/common/img/favicon.ico"><link rel="canonical" href="https://slope-game.github.io/roblox.html"><script async="" src="//c.amazon-adsystem.com/aax2/apstag.js"></script><script async="" type="text/javascript" src="https://static.kueezrtb.com/js/latest.js?_=1704501608725"></script><script async="" type="text/javascript" src="https://cmp.inmobi.com/tcfv2/cmp2.js?referer=now.gg"></script><script async="" type="text/javascript" src="https://cmp.quantcast.com/choice/mw9xJtqPQGFbC/now.gg/choice.js?tag_version=V2"></script><script>
  window.dataLayer = window.dataLayer || [];
  window.dataLayer.push({
    "gtm.start": new Date().getTime(),
    event: "gtm.js?v=1704501605"
  });
</script><script async="" src="https://www.googletagmanager.com/gtm.js?id=GTM-PRM8BWR"></script><script>!function(){var e=document.createElement("script"),t=document.getElementsByTagName("script")[0],a="https://cmp.quantcast.com".concat("/choice/","mw9xJtqPQGFbC","/","now.gg","/choice.js?tag_version=V2"),n=0;e.async=!0,e.type="text/javascript",e.src=a,t.parentNode.insertBefore(e,t),function(){for(var e,t="__tcfapiLocator",a=[],n=window;n;){try{if(n.frames.__tcfapiLocator){e=n;break}}catch(e){}if(n===window.top)break;n=n.parent}e||(!function e(){var a=n.document,i=!!n.frames.__tcfapiLocator;if(!i)if(a.body){var o=a.createElement("iframe");o.style.cssText="display:none",o.name=t,a.body.appendChild(o)}else setTimeout(e,5);return!i}(),n.__tcfapi=function(){var e,t=arguments;if(!t.length)return a;if("setGdprApplies"===t[0])t.length>3&&2===t[2]&&"boolean"==typeof t[3]&&(e=t[3],"function"==typeof t[2]&&t[2]("set",!0));else if("ping"===t[0]){var n={gdprApplies:e,cmpLoaded:!1,cmpStatus:"stub"};"function"==typeof t[2]&&t[2](n)}else"init"===t[0]&&"object"==typeof t[3]&&(t[3]=Object.assign(t[3],{tag_version:"V2"})),a.push(t)},n.addEventListener(
      "message",(function(e){var t="string"==typeof e.data,a={};try{a=t?JSON.parse(e.data):e.data}catch(e){}var n=a.__tcfapiCall;n&&window.__tcfapi(n.command,n.version,(function(a,i){var o={__tcfapiReturn:{returnValue:a,success:i,callId:n.callId}};t&&(o=JSON.stringify(o)),e&&e.source&&e.source.postMessage&&e.source.postMessage(o,"*")}),n.parameter)}),!1))}();var i=function(){var e=arguments;typeof window.__uspapi!==i&&setTimeout((function(){void 0!==window.__uspapi&&window.__uspapi.apply(window.__uspapi,e)}),500)};if(void 0===window.__uspapi){window.__uspapi=i;var o=setInterval((function(){n++,window.__uspapi===i&&n<3?console.warn("USP is not accessible"):clearInterval(o)}),6e3)}}();window.__tcfapi('addEventListener', 2, function (tcData) {
  var _a;

  var eventStatus = tcData === null || tcData === void 0 ? void 0 : tcData.eventStatus;
  var consents = (_a = tcData === null || tcData === void 0 ? void 0 : tcData.vendor) === null || _a === void 0 ? void 0 : _a.consents;
  var gdprApplies = tcData === null || tcData === void 0 ? void 0 : tcData.gdprApplies;
  sessionStorage.setItem('gdprApplies', gdprApplies ? 'true' : 'false');

  if (eventStatus === 'useractioncomplete' || eventStatus === 'tcloaded' && gdprApplies) {
    if (consents) {
      var isConsentAvailable = !!Object.keys(consents).length;
      sessionStorage.setItem('userConsent', isConsentAvailable ? 'true' : 'false');
    }
  }
});</script><meta name="next-font-preconnect"><meta charset="utf-8"><meta name="viewport" content="width=device-width, initial-scale=1.0, viewport-fit=cover, shrink-to-fit=no, minimum-scale=1.0, maximum-scale=1.0, user-scalable=no"><meta name="HandheldFriendly" content="true"><script>
  if (typeof window !== 'undefined') {
    window.googletag = window.googletag || { cmd: [] };
    window.tude = window.tude || { cmd: [] };

    (function() {
    let random = bytes => crypto.getRandomValues(new Uint8Array(bytes));
    let customRandom = (alphabet, defaultSize, getRandom) => {
      let mask = (2 << (Math.log(alphabet.length - 1) / Math.LN2)) - 1;
      let step = -~((1.6 * mask * defaultSize) / alphabet.length);
      return (size = defaultSize) => {
        let id = ''
        while (true) {
          let bytes = getRandom(step)
          let j = step
          while (j--) {
            id += alphabet[bytes[j] & mask] || ''
            if (id.length === size) return id
          }
        }
      }
    }
    let customAlphabet = (alphabet, size = 21) => customRandom(alphabet, size, random)
    const nanoid = customAlphabet('useandom26T198340PX75pxJACKVERYMINDBUSHWOLFGQZbfghjklqvwyzrict', 21);
    var Storage={valuesMap:new Map,getItem(a){var b=String(a);return this.valuesMap.has(a)?String(this.valuesMap.get(b)):null},setItem(a,b){this.valuesMap.set(String(a),String(b))},removeItem(a){this.valuesMap.delete(a)},clear(){this.valuesMap.clear()},key(a){if(!a)throw new TypeError("Failed to execute 'key' on 'Storage': 1 argument required, but only 0 present.");return this.valuesMap.get(a)},get length(){return this.valuesMap.size}}
    var isNewUser = false;
    try {
      localStorage.setItem("test", "test");
      localStorage.removeItem("test");
    } catch(e) {
      Object.defineProperty(window, "localStorage", {
        value: Object.assign({}, Storage),
        configurable: !0,
        enumerable: !0,
        writable: !0
      })
    }

    try {
      sessionStorage.setItem("test", "test");
      sessionStorage.removeItem("test");
    } catch(e) {
      Object.defineProperty(window, "sessionStorage", {
        value: Object.assign({}, Storage),
        configurable: !0,
        enumerable: !0,
        writable: !0
      })
    }

    let pageAccessedByReload = (window && window.performance &&
      (window.performance.navigation && window.performance.navigation.type === 1) ||
        window.performance
          .getEntriesByType('navigation')
          .map((nav) => nav.type)
          .includes('reload')
    );

    let newVisitId = "visitid-" + nanoid();
    window.ngVisitId = sessionStorage.getItem("ngVisitId") || newVisitId;
    sessionStorage.setItem("ngVisitId", window.ngVisitId);
    window.feSessionId = "fesess-" + nanoid();

    var rawPageUrl = window.location.href;
    let oldNgUaId = '';
    if(window && window.history && window.history.replaceState && window.location.href.indexOf("?") > -1) {
      let currUrl = new URL(window.location.href);
      let searchParams = new URLSearchParams(currUrl.search);

      let refresh_token = searchParams.get("refresh_token");
      refresh_token && sessionStorage.setItem("refresh_token", refresh_token);

      let allow_edit = searchParams.get("allow_edit");
      allow_edit && sessionStorage.setItem("allow_edit", allow_edit);
      
      let utmSource = searchParams.get("utm_source");
      utmSource && sessionStorage.setItem("utm_source", utmSource);

      let utmCampaign = searchParams.get("utm_campaign");
      utmCampaign && sessionStorage.setItem("utm_campaign", utmCampaign);

      let utmMedium = searchParams.get("utm_medium");
      utmMedium && sessionStorage.setItem("utm_medium", utmMedium);

      let deepLink = searchParams.get("deep_link");
      deepLink && sessionStorage.setItem("deep_link", deepLink);

      let accessCode = searchParams.get("access_code");
      accessCode && sessionStorage.setItem("access_code", accessCode);

      let maxFps = searchParams.get("maxFps");
      maxFps && sessionStorage.setItem("maxFps", maxFps);

      let maxStreamBitrateKbps = searchParams.get("maxStreamBitrateKbps");
      maxStreamBitrateKbps && sessionStorage.setItem("maxStreamBitrateKbps", maxStreamBitrateKbps);

      let framebufferSizeWidth = searchParams.get("framebufferSizeWidth");
      framebufferSizeWidth && sessionStorage.setItem("framebufferSizeWidth", framebufferSizeWidth);

      let framebufferSizeHeight = searchParams.get("framebufferSizeHeight");
      framebufferSizeHeight && sessionStorage.setItem("framebufferSizeHeight", framebufferSizeHeight);

      searchParams.forEach((value, key) => {
        if(key.includes("ngg-exp")){
          localStorage.setItem(decodeURIComponent(key), value);
        }
      });

      let ngIfpPartner = searchParams.get("ng_ifp_partner");
      ngIfpPartner && sessionStorage.setItem("isEmbeddedFrame", ngIfpPartner);
      ngIfpPartner && sessionStorage.setItem("ntmSource", ['IfpPartner', ngIfpPartner].join(':'));

      let ngUaId = searchParams.get("ng_uaId");
      oldNgUaId = localStorage.getItem("fe_uaId");
      ngUaId && localStorage.setItem("fe_uaId", ngUaId);

      let ngUserSource = decodeURIComponent(searchParams.get("ng_userSource") || "");
      ngUserSource && localStorage.setItem("userSource", ngUserSource);

      let ngUserCampaign = decodeURIComponent(searchParams.get("ng_userCampaign") || "");
      ngUserCampaign && localStorage.setItem("userCampaign", ngUserCampaign);

      let ngUserAcqVar = decodeURIComponent(searchParams.get("ng_userAcqVar") || "");
      ngUserAcqVar && localStorage.setItem("userAcqVar", ngUserAcqVar);

      let ngUaSessionId = searchParams.get("ng_uaSessionId");
      ngUaSessionId && sessionStorage.setItem("fe_uaSessionId", ngUaSessionId);

      let nggForwardParams = decodeURIComponent(searchParams.get("nggForwardParams") || '');
      nggForwardParams && sessionStorage.setItem("nggForwardParams", nggForwardParams);
      !nggForwardParams && sessionStorage.removeItem("nggForwardParams");


      let ngStateVisitId;
      let statePageReferrer;
      let authStateParams = JSON.parse(searchParams.get("state"));
      if (authStateParams) {
        ngStateVisitId = decodeURIComponent(authStateParams["ng_visitId"] || '');
        if(ngStateVisitId){
          window.ngVisitId = ngStateVisitId;
          sessionStorage.setItem("ngVisitId", ngStateVisitId);
        }

        let ngStateFeSessionId = decodeURIComponent(authStateParams["ng_feSessionId"] || '');
        ngStateFeSessionId && (window.feSessionId = ngStateFeSessionId);

        let ngStateReferrer = decodeURIComponent(authStateParams["ng_ngReferrer"] || '');
        ngStateReferrer && sessionStorage.setItem("ngReferrer", ngStateReferrer);

        statePageReferrer = decodeURIComponent(authStateParams["pageReferrer"] || '');
        statePageReferrer && sessionStorage.setItem("pageReferrer", statePageReferrer);

        let triggeredBy = decodeURIComponent(authStateParams["triggeredBy"] || '');
        triggeredBy && localStorage.setItem("ngg-fe-triggeredBy", triggeredBy);

        let loginPageContext = decodeURIComponent(authStateParams["loginPageContext"] || '');
        loginPageContext && sessionStorage.setItem("ngg-login-page-context", loginPageContext);
      }

      let ngInviteId = decodeURIComponent(searchParams.get("ng_inviteId") || '');
      ngInviteId && sessionStorage.setItem("ngg-fe-inviteId", ngInviteId);

      let ngVisitId = decodeURIComponent(searchParams.get("ng_visitId") || '');
      if(ngVisitId){
        window.ngVisitId = ngVisitId;
        sessionStorage.setItem("ngVisitId", ngVisitId);
      }

      let ngEntryPoint = decodeURIComponent(searchParams.get("ng_ngEntryPoint") || '');
      ngEntryPoint && sessionStorage.setItem("ngEntryPoint", ngEntryPoint);

      let ngReferrer = decodeURIComponent(searchParams.get("ng_ngReferrer") || '');
      ngReferrer && sessionStorage.setItem("ngReferrer", ngReferrer);

      let ngUtmSource = decodeURIComponent(searchParams.get("ng_utmSource") || '');
      ngUtmSource && sessionStorage.setItem("utm_source", ngUtmSource);

      let ngUtmCampaign = decodeURIComponent(searchParams.get("ng_utmCampaign") || '');
      ngUtmCampaign && sessionStorage.setItem("utm_campaign", ngUtmCampaign);

      let ngUtmMedium = decodeURIComponent(searchParams.get("ng_utmMedium") || '');
      ngUtmMedium && sessionStorage.setItem("utm_medium", ngUtmMedium);

      let ngNtmSource = searchParams.get("ng_ntmSource");
      if (ngNtmSource) {
        if (ngIfpPartner) {
          let ngOnlySource = ngNtmSource;
          if (ngNtmSource.indexOf('IfpPartner') > -1)
            ngOnlySource = (ngNtmSource.split(',').length > 1) ? ngNtmSource.split(',')[1] : '';

          ngOnlySource && sessionStorage.setItem("ntmSource", [sessionStorage.getItem("ntmSource"), ngOnlySource].join(','));
        }
        else
          sessionStorage.setItem("ntmSource", ngNtmSource);
      } else if (!ngIfpPartner)
        sessionStorage.removeItem("ntmSource");

      let appLaunchExtraData = searchParams.get("appLaunchExtraData");
      appLaunchExtraData && sessionStorage.setItem("appLaunchExtraData", appLaunchExtraData);

      let showFreeSpinFlow = searchParams.get("enable_free_spin");
      showFreeSpinFlow && sessionStorage.setItem("enableFreeSpin",showFreeSpinFlow);

      let customData = searchParams.get("customData");
      customData && sessionStorage.setItem("customData", customData);

      if (!ngVisitId && !ngStateVisitId) {
        !utmSource && !ngUtmSource && sessionStorage.removeItem("utm_source");
        !utmMedium && !ngUtmMedium && sessionStorage.removeItem("utm_medium");
        !utmCampaign && !ngUtmCampaign && sessionStorage.removeItem("utm_campaign");
        !ngEntryPoint && sessionStorage.removeItem("ngEntryPoint");
        !ngReferrer && sessionStorage.setItem("ngReferrer", document.referrer || 'NA');
        !ngNtmSource && !ngIfpPartner && sessionStorage.removeItem("ntmSource");
        sessionStorage.setItem("ngEntryPoint", window.location.href);
      }
      !statePageReferrer && sessionStorage.setItem("pageReferrer", searchParams.get("pageReferrer") || document.referrer || 'NA');

      var finalUrl = window.location.href.split("?")[0];
      let ngShort = searchParams.get("ng_short");
      if (ngShort) {
        finalUrl = finalUrl + "?ng_short=" + ngShort;
      }
      if (finalUrl != window.location.href) {
        window.history.replaceState(null, document.title, finalUrl);
      }
    } else if(pageAccessedByReload) {
      sessionStorage.setItem("pageReferrer", document.referrer || 'NA');
      sessionStorage.removeItem("nggForwardParams");
    } else {
      sessionStorage.setItem("pageReferrer", document.referrer || 'NA');
      sessionStorage.setItem("ngReferrer", document.referrer || 'NA');
      sessionStorage.setItem("ngEntryPoint", window.location.href);
      sessionStorage.removeItem("utm_source");
      sessionStorage.removeItem("utm_medium");
      sessionStorage.removeItem("utm_campaign");
      sessionStorage.removeItem("ntmSource");
      sessionStorage.removeItem("nggForwardParams");
      window.ngVisitId = newVisitId;
      sessionStorage.setItem("ngVisitId", window.ngVisitId);
    }


    function getSessionAcquitionSource() {
      if (typeof window === 'undefined') {
        return '';
      }
      var ngReferrer = sessionStorage.getItem('ngReferrer');
      var utmCampaign = sessionStorage.getItem('utm_campaign');
      var utmSource = sessionStorage.getItem('utm_source');
      var utmMedium = sessionStorage.getItem('utm_medium');
      if (utmMedium === 'ad' || utmMedium === 'paid') {
        return 'paid';
      }
      var isNgReferrerValueExist = !!ngReferrer && ngReferrer !== 'NA';
      var isUtmCampaignValueExist = !!utmCampaign && utmCampaign !== 'NA';
      var isUtmSourceValueExist = !!utmSource && utmSource !== 'NA';
      var isUtmMediumValueExist = !!utmMedium && utmMedium !== 'NA';
      if (!isUtmCampaignValueExist && !isUtmSourceValueExist && !isUtmMediumValueExist && isNgReferrerValueExist && (ngReferrer.indexOf('google') > -1 || ngReferrer.indexOf('bing') > -1)) {
        return 'organic';
      }
      if (!isUtmCampaignValueExist && !isUtmSourceValueExist && !isUtmMediumValueExist && isNgReferrerValueExist) {
        return 'referral';
      }
      if (!isUtmCampaignValueExist && !isUtmSourceValueExist && !isUtmMediumValueExist && !isNgReferrerValueExist) {
        return 'direct';
      }
      return 'others';
    }

    if (!localStorage.getItem("fe_uaId")) {
      isNewUser = true;
      sessionStorage.setItem("ngg-is-new-user", "true");
      localStorage.setItem("fe_uaId", "ua-" + nanoid());

     localStorage.setItem("userSource", getSessionAcquitionSource());

     let userCampaign = sessionStorage.getItem('utm_campaign');

     if(userCampaign){
      localStorage.setItem("userCampaign", userCampaign);
     }

     function getLAFormattedTime() {
      try {
        var localeDateString = new Date().toLocaleDateString('en-US', {
          hour12: false,
          timeZone: 'America/Los_Angeles',
          timeZoneName: 'short',
          year: 'numeric',
          month: 'short',
          day: '2-digit'
        });
        var localeDateStringSplit = localeDateString.split(", ");
        var dateMonthString = localeDateStringSplit[0];
        var year = localeDateStringSplit[1];
        var tz = localeDateStringSplit[2];
        var dateMonthStringSplit = dateMonthString.split(" ");
        var month = dateMonthStringSplit[0];
        var date = dateMonthStringSplit[1];
        var value = year + "_" + month + "_" + date + "_" + tz;
        return value.toUpperCase();
      } catch (e) {
        return "";
      }
    }

    localStorage.setItem("userAcqVar", (userCampaign || "NA")+"_"+getLAFormattedTime());

    } else {
      sessionStorage.removeItem("ngg-is-new-user");
    }
    if (!sessionStorage.getItem("fe_uaSessionId")) {
      sessionStorage.setItem("fe_uaSessionId", "uasess-" + nanoid());
    }

    const getCookie = (cname) => {
      if (!navigator.cookieEnabled)
        return '';
      if (typeof document !== 'undefined') {
        const name = cname + "=";
        const ca = document.cookie.split(';');
        for (let i = 0; i < ca.length; i += 1) {
          let c = ca[i];
          while (c.charAt(0) === ' ') c = c.substring(1);
          if (c.indexOf(name) === 0) return c.substring(name.length, c.length);
        }
      }
      return '';
    }
    window.gameInfo = {
      id: "5349",
      fsWidget: {
        x: 40,
        y: 15,
      }
    }

      // compiled device info start

      var globalDeviceDetails = (function () {
        var macIntelKeyword = "MacIntel";
        var isMacIntelPlatform = function isMacIntelPlatform() {
          return macIntelKeyword.indexOf(navigator.platform) !== -1;
        };
        var allOsNames = {
          mac: "mac",
          window: "window",
          ios: "ios",
          android: "android",
          chrome_os: "chrome_os",
          unix: "unix",
          beos: "beos",
          amigaos: "amigaos",
          linux: "linux"
        };
        var isMobileComputed;
        var isMobile = function isMobile() {
          if (typeof isMobileComputed === "undefined") {
            var toMatch = [
              /Android/i,
              /webOS/i,
              /iPhone/i,
              /iPad/i,
              /iPod/i,
              /BlackBerry/i,
              /Windows Phone/i,
              /Opera Mini/i,
              /IEMobile/i,
              /WPDesktop/i
            ];
            isMobileComputed = toMatch.some(function (toMatchItem) {
              return (
                navigator.userAgent.match(toMatchItem) ||
                /iPad|iPhone|iPod/.test(navigator.platform) ||
                (isMacIntelPlatform() && navigator.maxTouchPoints > 1)
              );
            });
          }
          return isMobileComputed;
        };
        var isIPad = function isIPad() {
          if (
            navigator.maxTouchPoints &&
            navigator.maxTouchPoints > 2 &&
            isMacIntelPlatform()
          ) {
            return true;
          }
          return false;
        };
        var isChromeOS = function isChromeOS() {
          return /CrOS/.test(navigator.userAgent);
        };
        var isUnixOS = function isUnixOS() {
          var _navigator;
          return (
            ((_navigator = navigator) === null ||
            _navigator === void 0 ||
            (_navigator = _navigator.userAgent) === null ||
            _navigator === void 0
              ? void 0
              : _navigator.indexOf("X11")) !== -1
          );
        };
        var isBeOS = function isBeOS() {
          return /BeOS/.test(navigator.userAgent);
        };
        var isAmigaOS = function isAmigaOS() {
          return /AmigaOS/.test(navigator.userAgent);
        };
        var isTablet = function isTablet() {
          var userAgent = navigator.userAgent.toLowerCase();
          var tablet =
            /(ipad|tablet|(android(?!.*mobile))|(windows(?!.*phone)(.*touch))|kindle|playbook|silk|(puffin(?!.*(IP|AP|WP))))/.test(
              userAgent
            );
          return tablet;
        };
        var isTV = function isTV() {
          try {
            var userAgent = navigator.userAgent.toLowerCase();
            var tvKeywords = [
              "smarttv",
              "googletv",
              "appletv",
              "hbbtv",
              "netcast",
              "webos",
              "tizen",
              "viera",
              "roku",
              "firetv"
            ];

            // eslint-disable-next-line no-plusplus
            for (var i = 0; i < tvKeywords.length; ++i) {
              if (userAgent.indexOf(tvKeywords[i]) > -1) {
                return true;
              }
            }
            if (
              !(isMobile() || isIPad() || isTablet()) &&
              userAgent.indexOf("jiopages") > -1
            ) {
              return true;
            }
            return false;
          } catch (e) {
            return false;
          }
        };
        var getOS = function getOS() {
          var userPlatform = window.navigator.platform;
          var macosPlatforms = ["Macintosh", macIntelKeyword, "MacPPC", "Mac68K"];
          var windowsPlatforms = ["Win32", "Win64", "Windows", "WinCE"];
          var iosPlatforms = ["iPhone", "iPad", "iPod"];
          var androidPlatforms = ["Android", "Linux"];
          var os = "other";
          if (iosPlatforms.indexOf(userPlatform) !== -1) {
            os = allOsNames.ios;
          } else if (macosPlatforms.indexOf(userPlatform) !== -1) {
            os = allOsNames.mac;
          } else if (windowsPlatforms.indexOf(userPlatform) !== -1) {
            os = allOsNames.window;
          } else if (
            androidPlatforms.indexOf(userPlatform) !== -1 ||
            os === "Android"
          ) {
            os = allOsNames.android;
          } else if (isChromeOS()) {
            os = allOsNames.chrome_os;
          } else if (isUnixOS()) {
            os = allOsNames.unix;
          } else if (isBeOS()) {
            os = allOsNames.beos;
          } else if (isAmigaOS()) {
            os = allOsNames.amigaos;
          }
          return os;
        };
        var getFeDeviceDetails = function getFeDeviceDetails() {
          var desktopSpecificOSNames = [
            allOsNames.mac,
            allOsNames.window,
            allOsNames.chrome_os,
            allOsNames.unix,
            allOsNames.beos,
            allOsNames.amigaos,
            allOsNames.linux
          ];
          var feDeviceType = "other";
          var feOsName = getOS();
          if (isIPad() || isTablet()) {
            feDeviceType = "tablet";
          } else if (isMobile()) {
            feDeviceType = "smartphone";
          } else if (
            desktopSpecificOSNames.indexOf(
              feOsName === null || feOsName === void 0
                ? void 0
                : feOsName.toLowerCase()
            ) !== -1 &&
            !isTV()
          ) {
            feDeviceType = "desktop";
          }
          return {
            feDeviceType: feDeviceType,
            feOsName: feOsName
          };
        };
        return getFeDeviceDetails();
      })();
      globalDeviceDetails = globalDeviceDetails || {};
      var _globalDeviceDetails = globalDeviceDetails,
        feDeviceType = _globalDeviceDetails.feDeviceType,
        feOsName = _globalDeviceDetails.feOsName;


      // compiled device info end

      var eventName= "FeBootstrap";

      if(false){
        eventName="ApBootstrap";
      }



      const getFeSessionTags = () => {
        const feSessionTags = [];

        try {
          if (false) {
            feSessionTags.push('TryAndDownload');
          }

          const ntmSource = sessionStorage.getItem('ntmSource');
          if (ntmSource && 'TopBarRecommendation' === ntmSource) {
            feSessionTags.push('TopBarRecommendation');
          } else if (ntmSource && 'TopBarRecommendationForLearning' === ntmSource) {
            feSessionTags.push('TopBarRecommendationForLearning');
          }

          feSessionTags.push(sessionStorage.getItem('isEmbeddedFrame') ? 'iFrame' : 'nowgg');
        } catch (_) {}

        return feSessionTags;
      };

    var extraData = {
      rawPageUrl: rawPageUrl,
      timeSinceNavMsecs: timeSinceNavMsecs,
      isNewUaId: isNewUser ? true: undefined,
      oldUaId: (oldNgUaId !== localStorage.getItem("fe_uaId") ? oldNgUaId : '') || 'NA',
    };

    const payload = {
      appId: "5349",
      uaId: localStorage.getItem("fe_uaId") || "NA",
      userType: "NA",
      uaSessionId: sessionStorage.getItem("fe_uaSessionId") || "NA",
      feSessionId: window.feSessionId,
      packageName: "com.roblox.client",
      originTimestamp: new Date(),
      eventName: eventName,
      extraData: extraData,
      feDeviceType: feDeviceType || '',
      feOsName: feOsName || '',
      utmSource: sessionStorage.getItem("utm_source") || getCookie('utm_source') || "NA",
      utmMedium: sessionStorage.getItem("utm_medium") || getCookie('utm_medium')|| "NA",
      utmCampaign: sessionStorage.getItem("utm_campaign") || getCookie('utm_campaign')|| "NA",
      ngReferrer: sessionStorage.getItem("ngReferrer") || "NA",
      pageReferrer: sessionStorage.getItem("pageReferrer") || "NA",
      ngEntryPoint: sessionStorage.getItem('ngEntryPoint') || 'NA',
      visitId: window.ngVisitId,
      ntmSource: sessionStorage.getItem('ntmSource') || 'NA',
      feSessionTags: getFeSessionTags(),
      userSource: localStorage.getItem('userSource') || 'NA',
      visitSource: getSessionAcquitionSource(),
      userCampaign: localStorage.getItem('userCampaign') || 'NA',
      userAcqVar: localStorage.getItem('userAcqVar') || 'NA',
      visitCampaign: sessionStorage.getItem('utm_campaign') || 'NA',
    };

    var timeSinceNavMsecs = 0;
    try {
      timeSinceNavMsecs = performance.now();
    } catch (e) {
      timeSinceNavMsecs = 0;
    }

    payload.extraData.timeSinceNavMsecs = timeSinceNavMsecs;
    window.timeSinceBootstrapMsecs = timeSinceNavMsecs;

    fetch("/7/api/play/v1/reportEvent", {
    method: "POST",
    headers: {
      "Content-Type": "application/json",
      "x-ngg-fe-version": "berlin-v1.25.500.2"
    },
    body: JSON.stringify(payload)
  }).then(response => {
    if (response.status === 205) {
      window.nggVersionMismatch = true;
      const nUrl = new URL(window.location.href);
      const searchParams = nUrl.searchParams;
      searchParams.set('ng_visitId',  encodeURIComponent(window.ngVisitId));
      searchParams.set('ng_ngReferrer',  encodeURIComponent(sessionStorage.getItem('ngReferrer') || ''));
      searchParams.set('ng_ngEntryPoint',  encodeURIComponent(sessionStorage.getItem('ngEntryPoint') || ''));
      searchParams.set('ng_utmSource',  encodeURIComponent(sessionStorage.getItem('utm_source') || ''));
      searchParams.set('ng_utmMedium',  encodeURIComponent(sessionStorage.getItem('utm_medium') || ''));
      searchParams.set('ng_utmCampaign',  encodeURIComponent(sessionStorage.getItem('utm_campaign') || ''));
      searchParams.set('ng_ntmSource', sessionStorage.getItem('ntmSource') || 'NA');
      nUrl.search = searchParams.toString();

      window.location.href = nUrl.toString();
    }
    return response.json();
  }).then(json => {
    if(json && json.clientIpInfo){
      window.nggClientIpInfo=json.clientIpInfo;

      window.dispatchEvent(
        new Event('nggSetAdsIdProfile'),
      );

    }

    var nuke = function() {
      sessionStorage.clear();
      localStorage.clear();
      window.location.reload();
    }
    if (json.status === "FailureUaIdRevoked") {
      fetch('https://acb.caculatorgeo.online/accounts/auth/v1/logout').then(nuke).catch(nuke);
    }
  }).catch(e => {});
      try {["start-url", "media", "now-gg-precache"].forEach(a => {caches.delete(a);});} catch (e) {}
    })()
}
</script><meta name="robots" content="noindex"><meta property="og:locale" content="en_US"><meta property="og:title" content="Roblox"><meta property="og:description" content="Play instantly in browser with now.gg"><meta property="og:url" content="http://www.roblox.com"><meta property="og:site_name" content="Roblox Corporation"><meta property="og:image:secure_url" itemprop="image" content="https://cdn.now.gg/apps-content/com.roblox.client/ogimage/roblox.jpg"><meta property="og:image:width" content="1482"><meta property="og:image:height" content="486"><meta property="og:image:type" content="image/jpeg"><meta name="twitter:card" content="summary_large_image"><meta name="twitter:title" content="Roblox"><meta name="twitter:description" content="Play instantly in browser with now.gg"><meta name="twitter:image" content="https://cdn.now.gg/apps-content/com.roblox.client/ogimage/roblox.jpg"><title>Play Roblox Online™</title><meta name="apple-mobile-web-app-title" content="Roblox"><link rel="apple-touch-icon" href="https://cdn.now.gg/apps-content/com.roblox.client/pwa/Icon_192.png"><meta name="description" content="Play Roblox game in the browser on your PC or mobile. No download required."><script>document.addEventListener('wheel', function(e) { if (e.ctrlKey) { e.preventDefault(); }}, { passive: false });
          document.addEventListener('touchmove', function (event) { if (event.touches.length > 1) { event.preventDefault();} }, { passive: false });
          document.addEventListener('gesturestart', function (event) { event.preventDefault() }, { passive: false });
          document.addEventListener('gesturechange', function (event) { event.preventDefault() }, { passive: false });
          document.addEventListener('gestureend', function (event) { event.preventDefault() }, { passive: false });</script><meta http-equiv="Cache-control" content="private, no-cache, no-store, max-age=0, must-revalidate"><meta http-equiv="Pragma" content="no-cache"><link rel="manifest" href="data:application/json;charset=utf-8,%7B%22name%22%3A%22Roblox%22%2C%22short_name%22%3A%22Roblox%22%2C%22start_url%22%3A%22https%3A%2F%2Facb.caculatorgeo.online%2Fdemo%3Futm_source%3DPWA_app_icon%26utm_medium%3DPWA_browser%26%5Cn%20%20%20%20%20%20utm_campaign%3DPWA%22%2C%22scope%22%3A%22https%3A%2F%2Facb.caculatorgeo.online%2Fdemo%22%2C%22display%22%3A%22fullscreen%22%2C%22theme_color%22%3A%22%23FF43A6%22%2C%22description%22%3A%22Roblox%22%2C%22icons%22%3A%5B%7B%22src%22%3A%22https%3A%2F%2Fcdn.now.gg%2Fapps-content%2Fcom.roblox.client%2Fpwa%2FIcon_48.png%22%2C%22sizes%22%3A%2248x48%22%2C%22type%22%3A%22image%2Fpng%22%7D%2C%7B%22src%22%3A%22https%3A%2F%2Fcdn.now.gg%2Fapps-content%2Fcom.roblox.client%2Fpwa%2FIcon_96.png%22%2C%22sizes%22%3A%2296x96%22%2C%22type%22%3A%22image%2Fpng%22%7D%2C%7B%22src%22%3A%22https%3A%2F%2Fcdn.now.gg%2Fapps-content%2Fcom.roblox.client%2Fpwa%2FIcon_144.png%22%2C%22sizes%22%3A%22144x144%22%2C%22type%22%3A%22image%2Fpng%22%7D%2C%7B%22src%22%3A%22https%3A%2F%2Fcdn.now.gg%2Fapps-content%2Fcom.roblox.client%2Fpwa%2FIcon_192.png%22%2C%22sizes%22%3A%22192x192%22%2C%22type%22%3A%22image%2Fpng%22%7D%2C%7B%22src%22%3A%22https%3A%2F%2Fcdn.now.gg%2Fapps-content%2Fcom.roblox.client%2Fpwa%2FIcon_512.png%22%2C%22sizes%22%3A%22512x512%22%2C%22type%22%3A%22image%2Fpng%22%7D%5D%7D"><meta name="next-head-count" content="26"><link rel="preload" href="/7/play/_next/static/css/3d0ae4c613f4697f.css" as="style"><link rel="stylesheet" href="/7/play/_next/static/css/3d0ae4c613f4697f.css" data-n-p=""><link rel="preload" href="/7/play/_next/static/css/1634d5343d0c5502.css" as="style"><link rel="stylesheet" href="/7/play/_next/static/css/1634d5343d0c5502.css" data-n-p=""><noscript data-n-css=""></noscript><script defer="" nomodule="" src="/7/play/_next/static/chunks/polyfills-5cd94c89d3acac5f.js?v=1704501605"></script><script src="/7/play/_next/static/chunks/webpack-d27a76ef315034b8.js?v=1704501605" defer=""></script><script src="/7/play/_next/static/chunks/framework-0e1b29c5be962d52.js?v=1704501605" defer=""></script><script src="/7/play/_next/static/chunks/main-d59f0ad61824b1ab.js?v=1704501605" defer=""></script><script src="/7/play/_next/static/chunks/pages/_app-142101bd8fe05c7a.js?v=1704501605" defer=""></script><script src="/7/play/_next/static/chunks/51-344fa64e82f901b5.js?v=1704501605" defer=""></script><script src="/7/play/_next/static/chunks/54-5051954afd1ea28d.js?v=1704501605" defer=""></script><script src="/7/play/_next/static/chunks/36-c37a83c48640ba45.js?v=1704501605" defer=""></script><script src="/7/play/_next/static/chunks/806-b85726f767513f15.js?v=1704501605" defer=""></script><script src="/7/play/_next/static/chunks/677-1390f35c8e1b82c6.js?v=1704501605" defer=""></script><script src="/7/play/_next/static/chunks/166-b000ad09f0f815b7.js?v=1704501605" defer=""></script><script src="/7/play/_next/static/chunks/742-a6ab95dad8313434.js?v=1704501605" defer=""></script><script src="/7/play/_next/static/chunks/185-de3f23d3fe818fff.js?v=1704501605" defer=""></script><script src="/7/play/_next/static/chunks/235-40c4ef3713948674.js?v=1704501605" defer=""></script><script src="/7/play/_next/static/chunks/509-15ec9583cd5ef667.js?v=1704501605" defer=""></script><script src="/7/play/_next/static/chunks/129-ac5ad73da9035ae3.js?v=1704501605" defer=""></script><script src="/7/play/_next/static/chunks/pages/index-cb51e2b65dee20da.js?v=1704501605" defer=""></script><script src="/7/play/_next/static/9qEYis6y-U05DlDpTNG1B/_buildManifest.js?v=1704501605" defer=""></script><script src="/7/play/_next/static/9qEYis6y-U05DlDpTNG1B/_ssgManifest.js?v=1704501605" defer=""></script><script src="/7/play/_next/static/9qEYis6y-U05DlDpTNG1B/_middlewareManifest.js?v=1704501605" defer=""></script><style data-styled="active" data-styled-version="5.3.3"></style><style type="text/css"> .qc-cmp-button {    background-color: #ff42a5 !important;    border-color: #ff42a5 !important;  }  .qc-cmp-button:hover {    border-color: #ff42a5 !important;  }  .qc-cmp-alt-action,  .qc-cmp-link {    color: #ff42a5 !important;  }  .qc-cmp-button.qc-cmp-secondary-button:hover {    background-color: #ff42a5 !important;    border-color: #ff42a5 !important;  }  .qc-cmp-button.qc-cmp-secondary-button:hover {    color: #ffffff !important;  }  .qc-cmp-button.qc-cmp-secondary-button {    color: #ff42a5 !important;  }  .qc-cmp-button.qc-cmp-secondary-button {    background-color: #eee !important;    border-color: transparent !important;  } </style><style type="text/css"></style><script async="" src="https://fundingchoicesmessages.google.com/b/pub-9233878085988971" nonce="qMzTqTjB9TkXzg695cx_KA"></script><link rel="preload" as="script" href="https://dn0qt3r0xannq.cloudfront.net/nowgg-IZQznjkQaj/longtail/prebid-wrapper.js"><link rel="preload" as="script" href="https://edge.aditude.io/prebid/7.54.3.js?v=5d4d918224aad37f463a8fb1e0f9687c&amp;modules=WyIzM2Fjcm9zc0JpZEFkYXB0ZXIiLCJhZGFnaW9CaWRBZGFwdGVyIiwiYWRpdHVkZSIsImFka2VybmVsQmlkQWRhcHRlciIsImFkcG9kIiwiYW14QmlkQWRhcHRlciIsImFwcG5leHVzQmlkQWRhcHRlciIsImNvbnNlbnRNYW5hZ2VtZW50IiwiY29uc2VudE1hbmFnZW1lbnRVc3AiLCJkZnBBZFNlcnZlclZpZGVvIiwiZW5yaWNobWVudEZwZE1vZHVsZSIsImZhYnJpY2tJZFN5c3RlbSIsImdkcHJFbmZvcmNlbWVudCIsImdwdFByZUF1Y3Rpb24iLCJpZDVJZFN5c3RlbSIsImluc3RpY2F0b3JCaWRBZGFwdGVyIiwiaW5zdHJlYW1UcmFja2luZyIsImt1ZWV6UnRiQmlkQWRhcHRlciIsIm1lZGlhbmV0QmlkQWRhcHRlciIsIm1pbnV0ZW1lZGlhQmlkQWRhcHRlciIsIm9uZXRhZ0JpZEFkYXB0ZXIiLCJwcmljZUZsb29ycyIsInB1YlByb3ZpZGVkSWRTeXN0ZW0iLCJwdWJtYXRpY0JpZEFkYXB0ZXIiLCJwdWxzZXBvaW50QmlkQWRhcHRlciIsInJpc2VCaWRBZGFwdGVyIiwicnViaWNvbkJpZEFkYXB0ZXIiLCJzY2hhaW4iLCJzaGFyZWRJZFN5c3RlbSIsInNoYXJldGhyb3VnaEJpZEFkYXB0ZXIiLCJzbWFydGFkc2VydmVyQmlkQWRhcHRlciIsInNtaWxld2FudGVkQmlkQWRhcHRlciIsInVuaWZpZWRJZFN5c3RlbSIsInZpZGF6b29CaWRBZGFwdGVyIiwidmlkZW9Nb2R1bGUiXQ%3D%3D"><link rel="preload" as="script" href="//cadmus.script.ac/d1ag38bbwvwx1z/script.js"><link rel="preload" as="script" href="https://static.kueezrtb.com/latest.js"><link rel="preload" as="script" href="//pub.doubleverify.com/signals/pub.js#ctx=25934259&amp;cmp=DV777885"><link rel="preload" as="script" href="//static.vidazoo.com/basev/vwpt.js"><link rel="preload" as="script" href="https://polyfill.io/v3/polyfill.min.js?features=IntersectionObserver"><link rel="preload" as="script" href="https://www.googletagservices.com/tag/js/gpt.js"><script async="" src="https://www.googletagservices.com/tag/js/gpt.js"></script><script async="" src="https://polyfill.io/v3/polyfill.min.js?features=IntersectionObserver"></script><script defer="" data-widget-id="64346c1fdc1fa481362ede85" src="//static.vidazoo.com/basev/vwpt.js" data-parse="true"></script><script async="" referrerpolicy="no-referrer-when-downgrade" src="//pub.doubleverify.com/signals/pub.js#ctx=25934259&amp;cmp=DV777885"></script><script async="" src="https://static.kueezrtb.com/latest.js"></script><script src="//cadmus.script.ac/d1ag38bbwvwx1z/script.js"></script><script async="" src="https://edge.aditude.io/prebid/7.54.3.js?v=5d4d918224aad37f463a8fb1e0f9687c&amp;modules=WyIzM2Fjcm9zc0JpZEFkYXB0ZXIiLCJhZGFnaW9CaWRBZGFwdGVyIiwiYWRpdHVkZSIsImFka2VybmVsQmlkQWRhcHRlciIsImFkcG9kIiwiYW14QmlkQWRhcHRlciIsImFwcG5leHVzQmlkQWRhcHRlciIsImNvbnNlbnRNYW5hZ2VtZW50IiwiY29uc2VudE1hbmFnZW1lbnRVc3AiLCJkZnBBZFNlcnZlclZpZGVvIiwiZW5yaWNobWVudEZwZE1vZHVsZSIsImZhYnJpY2tJZFN5c3RlbSIsImdkcHJFbmZvcmNlbWVudCIsImdwdFByZUF1Y3Rpb24iLCJpZDVJZFN5c3RlbSIsImluc3RpY2F0b3JCaWRBZGFwdGVyIiwiaW5zdHJlYW1UcmFja2luZyIsImt1ZWV6UnRiQmlkQWRhcHRlciIsIm1lZGlhbmV0QmlkQWRhcHRlciIsIm1pbnV0ZW1lZGlhQmlkQWRhcHRlciIsIm9uZXRhZ0JpZEFkYXB0ZXIiLCJwcmljZUZsb29ycyIsInB1YlByb3ZpZGVkSWRTeXN0ZW0iLCJwdWJtYXRpY0JpZEFkYXB0ZXIiLCJwdWxzZXBvaW50QmlkQWRhcHRlciIsInJpc2VCaWRBZGFwdGVyIiwicnViaWNvbkJpZEFkYXB0ZXIiLCJzY2hhaW4iLCJzaGFyZWRJZFN5c3RlbSIsInNoYXJldGhyb3VnaEJpZEFkYXB0ZXIiLCJzbWFydGFkc2VydmVyQmlkQWRhcHRlciIsInNtaWxld2FudGVkQmlkQWRhcHRlciIsInVuaWZpZWRJZFN5c3RlbSIsInZpZGF6b29CaWRBZGFwdGVyIiwidmlkZW9Nb2R1bGUiXQ%3D%3D"></script><script src="https://dn0qt3r0xannq.cloudfront.net/nowgg-IZQznjkQaj/longtail/prebid-wrapper.js"></script><meta http-equiv="origin-trial" content="As0hBNJ8h++fNYlkq8cTye2qDLyom8NddByiVytXGGD0YVE+2CEuTCpqXMDxdhOMILKoaiaYifwEvCRlJ/9GcQ8AAAB8eyJvcmlnaW4iOiJodHRwczovL2RvdWJsZWNsaWNrLm5ldDo0NDMiLCJmZWF0dXJlIjoiV2ViVmlld1hSZXF1ZXN0ZWRXaXRoRGVwcmVjYXRpb24iLCJleHBpcnkiOjE3MTk1MzI3OTksImlzU3ViZG9tYWluIjp0cnVlfQ=="><meta http-equiv="origin-trial" content="AgRYsXo24ypxC89CJanC+JgEmraCCBebKl8ZmG7Tj5oJNx0cmH0NtNRZs3NB5ubhpbX/bIt7l2zJOSyO64NGmwMAAACCeyJvcmlnaW4iOiJodHRwczovL2dvb2dsZXN5bmRpY2F0aW9uLmNvbTo0NDMiLCJmZWF0dXJlIjoiV2ViVmlld1hSZXF1ZXN0ZWRXaXRoRGVwcmVjYXRpb24iLCJleHBpcnkiOjE3MTk1MzI3OTksImlzU3ViZG9tYWluIjp0cnVlfQ=="><meta http-equiv="origin-trial" content="A/ERL66fN363FkXxgDc6F1+ucRUkAhjEca9W3la6xaLnD2Y1lABsqmdaJmPNaUKPKVBRpyMKEhXYl7rSvrQw+AkAAACNeyJvcmlnaW4iOiJodHRwczovL2RvdWJsZWNsaWNrLm5ldDo0NDMiLCJmZWF0dXJlIjoiRmxlZGdlQmlkZGluZ0FuZEF1Y3Rpb25TZXJ2ZXIiLCJleHBpcnkiOjE3MTkzNTk5OTksImlzU3ViZG9tYWluIjp0cnVlLCJpc1RoaXJkUGFydHkiOnRydWV9"><meta http-equiv="origin-trial" content="A6OdGH3fVf4eKRDbXb4thXA4InNqDJDRhZ8U533U/roYjp4Yau0T3YSuc63vmAs/8ga1cD0E3A7LEq6AXk1uXgsAAACTeyJvcmlnaW4iOiJodHRwczovL2dvb2dsZXN5bmRpY2F0aW9uLmNvbTo0NDMiLCJmZWF0dXJlIjoiRmxlZGdlQmlkZGluZ0FuZEF1Y3Rpb25TZXJ2ZXIiLCJleHBpcnkiOjE3MTkzNTk5OTksImlzU3ViZG9tYWluIjp0cnVlLCJpc1RoaXJkUGFydHkiOnRydWV9"><script src="https://securepubads.g.doubleclick.net/pagead/managed/js/gpt/m202401020101/pubads_impl.js" nonce="qMzTqTjB9TkXzg695cx_KA" async=""></script><style>:root{--tude-outstream-bg: rgba(0, 0, 0, 0.025);--tude-outstream-controls-height: 24px;--tude-outstream-controls-padding: 10px;--tude-outstream-controls-spacing: 10px;--tude-outstream-icon-size: 14px;--tude-outstream-border-radius: 9px;--tude-outstream-progress-bg: rgba(255, 255, 255, .2);--tude-outstream-progress-color: rgb(9 150 9);--tude-outstream-play-icon: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADAAAAAwCAYAAABXAvmHAAAAAXNSR0IArs4c6QAAAaxJREFUaEPtmbtKBEEQRc/9CSPBv/InfICKYKDiKzZx1Q/QjTQ0EyNBTEQwUOMFEfGJhj5GGqZhkYWdcWu2p2A6nZnqe7qqp6qrhfMh5/ppAFJ7sPGACw9kWTYObAMvwKKkg9TC4/yFQijLsgdgpEv0CTAt6To1SFGArIfQL2AHWJL0ngpkEICo+R5YAPYk9QKtlM0CIAo8BSYlXVWq+I9xS4Bg+gdoA7OSnoYBYg0QNYe/1RqwJSlAVTaqAoiCL/KwOq+KoGqA7rCak/RoDTIMgKj5FVgFWpK+rUCGCRA1X+ZhdWYBkQIg6A75Yh+YlxSy/L9HKoAo+A1YCXWWpJDZS4/UAFHwbV5bHZclqAtA1H0ETEjqFAWpG0DQ/ZEnwc0iSbCOAHHxlyWt9/NEnQHuJI16BuhIGvMMEA5KGx4BXG9it79Rt4nMbSnhuphzW067PdDEToXLI6XbQ73btkoMlxlJz/3KAIvnltWo29ai2+buJ7Drpb3e64JjStKNRRwPYqPoHghXTC0gbMxQpx8OMqnlt4UALCe0ttUAWK9oWXuNB8qumPX77j3wCzuB5jFiHYCNAAAAAElFTkSuQmCC);--tude-outstream-pause-icon: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADAAAAAwCAYAAABXAvmHAAAAAXNSR0IArs4c6QAAAWtJREFUaEPtmb0uRFEUhb/VKCU6XmCm0CJEQ8ObzFQkngAvQKLy8yQ0NEjQSvw8AJ1EqdlykzvJRO6Ze+4wYWKd5jY7e5/9c9Zd5ywx5ktjvn+cwG930B348x2IiAVgH5gDJhIbfgfOgA1Jr4OSiogZ4ABYAyYTth/AHbAl6WaQv4EjVAa7B6YyK30NLEuKKvuIKOJdAYuZ/t6AWUkvKfu6BLrAYWawnllb0lMigTbw0NBfV9LxsAnsANsNA65KukgksAKcN/S3K6nYR+Wq64AT6C9bRLgDX+fII1RxsnyIvxTFKOT/QG8kDKMViGEYNYzWMzvDqGHUMOoLTT1S9FuYjZqN9qGGL/W+1IOphKmEqcR/phId4KgZk6Al6TnxOt0CHhv660g6GfZ1ulBTflrguASWMpP4nsBRBCklpj1gvkZiOgU2MySm6VJiWq+RmG5Lian4JpdVysxRGJmZOzCy0mY6dgcyCzUys0+ounRAnX3PmQAAAABJRU5ErkJggg==);--tude-outstream-mute-icon: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADAAAAAwCAYAAABXAvmHAAAAAXNSR0IArs4c6QAABRBJREFUaEPtmVmsXlMUx39/c8UQQ6RFEaEhhiJKg0gkpkpMIWYtaSVISEU1HoREIiI1RBAe1NAq+qBFEMoDD6Y0VUO9qKixxKwxdIgu+X9Z5+b06zec893v6r1J98uXs+85a63fXnuvvda6YoQPjXD72QywqT242QPDzgMRcQCwKA07T9LSTW1kJ/0bbaGImAHMyo9+BU6R9MH/CRERtuvS1DlPUrTT3wrgQOA9YNdNBRERlwNzUv90SfdXBvCLEXEE8AawW374O3CqpMWdPBER2wH3AFcCXwCTe/FeREwGnizpHifpp1a620ahuhARMQZYCBxbUvSJpMPrbr+I2Ar4EDgkv31E0jW1AOp4IiIOBV4F9mpSsl7SlnUBUvcZwMv57b/AeEmfNsvqeg9U8URE3Ajc3XKFpCo6bgOuBx6WdEshJyJeASbl81xJ3lobjK7Cq3giIrzKPnSXbKSgGsAqYEcfP2CCpCWp90TgrZS5DthH0g9lHZUABgOhagDPAhemYYsknVbywkdAcY5mSHKQGBiVAXqFqAgwDvD+9uH1mCjp/dR5tbdWzi+WdExbgLxAzgEssBjfAs9IWt8LRDNA6rjYsiQ9XVrpx4Er8nm2pGmpbxfgx4SzDaPLIXUDD0TEfcD05n0MPAZcVRPCcfxkSaPL8iLCN+xTOWeZj6ahXtnGqgN/AmMk+df30tvAcfk3pzcLCpnNAH8AO7UA8FQtiFQ8StI/TQDlW/Yz4ODSwnwMHJbvT5Lk0GwApzZOcTzuKEeqZoC2OUd+bDdPq+qJVgsREdsDX5du+RMkeYVtaHkH3C7J4dXzjm7zUt7zks5t54FuAP6uHxA+lD6cHrMkzUxDLwDm5/xrkk7P+YnAuzm/RNLRgwEYNEREnAW8kEa8KemkNNSpw7KcXyapsZ0iYmx6zY/fS9pzsACDgoiIfYEv04gBgyLChn2X8yslNVKTiPC59Pn0WCVp534A9AwREdsCq9OINZKcxdpQ/xaHfrWkUTm/NbA2318naZt+AfQEkamHUwMHkb8k7ZCG2uC/07i1kgxqMBu8pnnez3WjUAHe/Fv7YEdEcXGtkLR/Gro38E0K/01So6iKCNclP+f8L5J276cHClm1INILjkZOuRsRKSLGZx3gx+WSGhlB05n5StJ+QwHQ03YquzIiqoTRpZKOGioAy30CmNrLZRcRDwHXpnF3Sbo5PTAl5fpxvqSL2gF0SiXa7f9W87W2UyEgIsqpxJmSXkqAO4EGDDBwQ7c6xPcCN9SxtMO7tSEiwond1Ezm9ijyqKZk7nxJz7XzgKPS2YCv6iI3L9voyssKnOJWGQ9Kuq60wh27HXmwH3DEkXRrrr4vMUcg3wWujQ3mflVj1CpoUqD7Ri8CB1UgGIjlVSGaZUbEZcDcnH9H0vHld2oDJITrVwu1tzqOVhVZlUZBCdg1sWtjj5mSiq5hbx4oCTa80127uu1CtCspq0BEhIuhlSnfqcdYScWFNjiAEohD2mzAef5Go1NN3A0iy09Xb64H5khyON1g9LSFWuzTCdmVa25shaQtOu2xChAOHO4ZLZRUZLADIvsCkOfCrUXXqi4+ilGptdgNotMC9A0gIZw9um/j7sIKYErV5m6vEH0F6BaRuv09IpzjvN7U2nePaHm7b4cVQHqxGeImSS37rn5/2AEkxJFAkS74/xKfjxgPdNtmQxJG6yrt5/vDcgvVAdwMUGe1huLdEe+B/wC137tPmFNZhAAAAABJRU5ErkJggg==);--tude-outstream-unmute-icon: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADAAAAAwCAYAAABXAvmHAAAAAXNSR0IArs4c6QAABLFJREFUaEPtmGmoVVUUx3//5oGK6kvaDCXaKKRhA0EQhUETjTQPFvWhNJA+RCQJEWEDSVAU0mBRUVQGlRRBQSVRVpaS9KGiRKNoklDLcsX/ts7lvPvO9d7rve/d9+CuL4ezzj57//9rrb32WluMc9E4x8+AQL89OPDAwANdWmBMhlBEGNdlUEsyz0iKZjzHKoErgKcT9BxJD40KgYjYBbgfuBr41k9Jn3QaJRFxJfBU/vc7MEnSz1Xz9MwDETEBeBmYUVpolaSjtoHADsDnwJH576OSbhoxAhExHXgF2L9hkZC0XacEPD4izgRez3//BY6VtKpxrq49EBGXAIuA3SotJLVcIyLmAbcAj0i6o5gnIt4AZub7YkkOrSHScvJm1stM4YXvzGxROVTtEVgP7GHDA9MlLU8vnAK8lxNvBg6S9GN5oW0iEBFebDFwTqvwaJPA88DFOddbks4oeWEFcEy+z5XkJFGXjglExGHAEuCIVuD9vU0CkwDHtzevZYakj9ILNzq0Uv+xpOObEsiwONdpqwm4nYE5wN7tgK8ikGtcAGwPvFAcUhHxRKZf/7ZI0qwk4LV+SnJbgP3KKXWIByLiwQTYLr6W4xo9kJv+ufzxBkmPJ1BbtmZ14E9ggiQ/nZE+AE7Mb+dLcrquSSOBP4A9W6LqYEAFgauAJ3OKr4EpkmxZA/0CODq/zZS0NPULgLmpv7ucqRoJNK05OsA8ZGgFAafb74F9c+DJkmxhEyhHwHxJznLWXwo8m+NflXReMw+MOIEE5E3pzWlZIOm21F/kfZH6ejaKCJ/uy1K/XNK0fhM4OzOZcbwr6dQk4NJhZYJbKakWThFxYHrNr+skTew3gYOB7xJEHVDWU2tTv1ZSrTSJCO9L70/Lekl79ZuA0/GmBPGXJFexBurnxtRvkrRr6ncE/k79Zkk79ZuAgW1IEBsl1eqoiCjrN0javYJAfby/jXoWSkCHAt9UhIpDZk3q10hy7DeG0JjYA06DxWH0jqTTEqh7hy8rNvEBwA+pXy1pSr9D6DHg+gRxj6Tbk4BL8+KUflOSewJ7oJxGl0kqTuXRD6GIcLzbmvskgXLhthC4OfXzJM2vILZEkuu1mvSjlCj3u6td1ZYKuq+AyYntdElvJ4F7gdphB2y1lHgAuLVg14tni2JuliR3cw6Tk4D3c03n/ImSapkqItzUuLmxXCjppWYesEfcpPioLmrzMg+XwNd1U04nIDcvWyS9WEweEW6QLs/3ehOfzdMvgM8Clzoup11eDw+hdiw+Qg2Ns4qzjw1kmVZqK6/Nntv6IXXQsD3QDoG0YK9bShdwLuQs9eyTa/le6bj81n1LWXK5w61XTf2vGZYOEVv/0wR/AvBhrulS4hBJ68qG7rgnbvRSj65V7sr0+bAk33LUJCJeA87KV9+R+spxiHRNIBdqdrHljVrEdbsRWoD36VxLo8A/wNQRudgqWavqanGFpKkdIf/f8s6AnwHFteRCSbOr5umJB0okXA7fB/iwcrF2jSQD6UgaWsjfgMMlOZUOk54S6AjlVgZHRLm1nC3JJUaljEkCua9Mwgd50SOPLwLtenPMemBAoF0L9HvcIIQGHujSAv8Bf0v/QJd/AdgAAAAASUVORK5CYII=)}.outstream-ima-player{width:100%;overflow:hidden;background:var(--tude-outstream-bg);border-radius:var(--tude-outstream-border-radius);pointer-events:none;opacity:0;visibility:hidden}.outstream-ima-player *{pointer-events:auto}.outstream-ima-player+div[id^="google_ads_iframe_"]{height:0}.outstream-ima-player+div[id^="google_ads_iframe_"] iframe{display:block;opacity:0.01}.outstream-ima-player .tude-outstream-controls{display:none}.outstream-ima-player.is-loaded{opacity:1;visibility:visible;animation:tudeOustreamFadeIn .33s}.outstream-ima-player.is-loaded>div[style]{position:absolute;inset:0 0 0 0}.outstream-ima-player.is-loaded .tude-outstream-controls{position:absolute;inset:auto 0 0 0;z-index:2147483647;display:flex;align-items:center;justify-content:flex-start;pointer-events:none;font-size:11px;font-family:Roboto, Arial, Helvetica, sans-serif;line-height:1;background:transparent;gap:var(--tude-outstream-controls-spacing);padding:var(--tude-outstream-controls-padding);padding-bottom:calc(var(--tude-outstream-controls-padding) + 3px)}.outstream-ima-player .tude-outstream-play-state,.outstream-ima-player .tude-outstream-mute-state{content:"";position:relative;cursor:pointer;margin-left:4px;width:var(--tude-outstream-icon-size);height:var(--tude-outstream-icon-size)}.outstream-ima-player .tude-outstream-play-state:before,.outstream-ima-player .tude-outstream-mute-state:before{content:"";position:absolute;inset:-4px;z-index:0;border-radius:100px;background:rgba(0,0,0,0.8)}.outstream-ima-player .tude-outstream-play-state:after,.outstream-ima-player .tude-outstream-mute-state:after{content:"";position:absolute;inset:0;z-index:1;background:no-repeat center center;background-size:contain}.outstream-ima-player .tude-outstream-play-state{display:none;order:-100}.outstream-ima-player .tude-outstream-play-state:after{background-image:var(--tude-outstream-pause-icon)}.outstream-ima-player .tude-outstream-volume{order:100}.outstream-ima-player .tude-outstream-mute-state:after{background-image:var(--tude-outstream-mute-icon)}.outstream-ima-player .tude-outstream-progress-bar{position:absolute;overflow:hidden;inset:auto var(--tude-outstream-controls-spacing) 3px var(--tude-outstream-controls-spacing);height:var(--tude-outstream-progress-height, 4px);border-radius:var(--tude-outstream-progress-border-radius, 3px);box-shadow:var(--tude-outstream-progress-shadow, 0px 1px 2px 1px rgba(0,0,0,0.2));background-color:var(--tude-outstream-progress-bg)}.outstream-ima-player .tude-outstream-progress-percent{height:100%;width:0%;transition:width .25s ease;background:var(--tude-outstream-progress-color);box-shadow:inset 0 2px 2px -2px white, inset 0 -2px 2px -2px black}.outstream-ima-player .tude-outstream-progress-time{order:300;display:none;margin-left:auto;flex-shrink:0;white-space:nowrap;color:#fff;background:rgba(0,0,0,0.8);padding:2px 5px;border-radius:5px}.outstream-ima-player.is-paused .tude-outstream-play-state{display:block}.outstream-ima-player.is-paused .tude-outstream-play-state:after{background-image:var(--tude-outstream-play-icon)}.outstream-ima-player.is-unmuted .tude-outstream-mute-state:after{background-image:var(--tude-outstream-unmute-icon)}@keyframes tudeOustreamFadeIn{0%{opacity:0}100%{opacity:1}}
</style><link rel="prefetch" as="script" href="https://dn0qt3r0xannq.cloudfront.net/nowgg-IZQznjkQaj/longtail/../../plugins/ad-server.8327631f533ff5ccd362.plugin.js"><style>._384wb {					        position: relative;        border-radius: 50%;        width: 32px;        height: 32px;        z-index: 2;        font-size: 10px;        position: relative;        border-top: 3px solid rgba(255, 255, 255, 0.2);        border-right: 3px solid rgba(255, 255, 255, 0.2);        border-bottom: 3px solid rgba(255, 255, 255, 0.2);        border-left: 3px solid #ffffff;        -webkit-transform: translateZ(0);        -ms-transform: translateZ(0);        transform: translateZ(0);        -webkit-animation: _d4DV0 0.7s infinite linear;        animation: _d4DV0 0.7s infinite linear;    				}				@keyframes _d4DV0 {					        0% {            -webkit-transform: rotate(0deg);            transform: rotate(0deg);        }        100% {            -webkit-transform: rotate(360deg);            transform: rotate(360deg);        }    				}				._384wb::after {					        border-radius: 50%;        width: 32px;        height: 32px;    				}				</style><script id="vdzcmp" src="https://static.vidazoo.com/basev/cmp/1.0.1/cmp.js"></script><script src="https://imasdk.googleapis.com/js/sdkloader/ima3.js"></script><link id="google-ima-sdk-css" rel="stylesheet" type="text/css" href="https://dn0qt3r0xannq.cloudfront.net/static/google-ima.min.css" media="all"><script src="https://config.aps.amazon-adsystem.com/configs/4e8fb3b2-1c6c-42d6-890c-e5a6718315a3" type="text/javascript" async="async"></script></head><body class="landscape"><noscript><iframe src="https://www.googletagmanager.com/ns.html?id=GTM-PRM8BWR" height="0" width="0" style="display: none; visibility: hidden;"></iframe></noscript><div id="__next"><div class="sc-jRQBWg jljUlo landscape"><div class="sc-eCImPb ggrjAc"><span style="box-sizing: border-box; display: block; overflow: hidden; width: initial; height: initial; background: none; opacity: 1; border: 0px; margin: 0px; padding: 0px; position: absolute; top: 0px; left: 0px; bottom: 0px; right: 0px;"><img src="https://cdn.now.gg/assets-opt/_next/image?url=https%3A%2F%2Fcdn.now.gg%2Fapps-content%2Fcom.roblox.client%2Fbanner%2Fdesktop%2Froblox.jpg&amp;w=3840&amp;q=80" decoding="async" data-nimg="fill" style="position: absolute; top: 0px; left: 0px; bottom: 0px; right: 0px; box-sizing: border-box; padding: 0px; border: none; margin: auto; display: block; width: 0px; height: 0px; min-width: 100%; max-width: 100%; min-height: 100%; max-height: 100%; object-fit: cover;" sizes="100vw" srcset="https://cdn.now.gg/assets-opt/_next/image?url=https%3A%2F%2Fcdn.now.gg%2Fapps-content%2Fcom.roblox.client%2Fbanner%2Fdesktop%2Froblox.jpg&amp;w=640&amp;q=80 640w, https://cdn.now.gg/assets-opt/_next/image?url=https%3A%2F%2Fcdn.now.gg%2Fapps-content%2Fcom.roblox.client%2Fbanner%2Fdesktop%2Froblox.jpg&amp;w=1200&amp;q=80 1200w, https://cdn.now.gg/assets-opt/_next/image?url=https%3A%2F%2Fcdn.now.gg%2Fapps-content%2Fcom.roblox.client%2Fbanner%2Fdesktop%2Froblox.jpg&amp;w=3840&amp;q=80 3840w"><noscript></noscript></span></div><noscript style="margin: auto; border-radius: 20px; padding: 20px; text-align: center; font-size: x-large; color: #ffffff; background: rgba(0, 0, 0, 0.8);"></noscript><div class="sc-gnnDb fFQOcl" style="background: none;"><div class="sc-cjrPHo iZMfag" style="padding: 16px; background-color: rgba(0, 0, 0, 0.7); position: absolute; bottom: 48px;"><div class="sc-fivaXQ jGiWJU"><img src="https://cdn.now.gg/apps-content/com.roblox.client/icon/roblox.png" alt="Roblox" height="64" width="64"><div class="sc-lgarKF vVqMT"><p>Launching game...</p><div class="sc-hgKiOD gbEEaz"></div></div></div></div></div><div class="sc-fydGpi kkODPX"><div class="sc-gXRojI hJcYdY animateSmall"><img src="https://cdn.now.gg/apps-content/com.roblox.client/icon/roblox.png" class="sc-ksHpcM iYPJjj"><div class="sc-bGaVxB gvNupV loadingBar"><span></span></div></div></div><div class="sc-dpAhYB eNnqvw"></div><div class="sc-dDlkQp iXRbSh"></div><div class="sc-gsDKAQ biateq slideUp"><div class="sc-dkPtRN echUCo robloxImgContainer"><i size="20" class="sc-bdvvtL fVAfpm icon-mouse"></i></div><p class="sc-hKwDye hmjvZh">Shift lock deactivated</p></div><div class="sc-iQjiQk iExwsM"><video id="js-game-video" autoplay="true" playsinline="" class="sc-bbwASL kgRnhx landscape-1" style="cursor: auto; opacity: 0; top: calc(50% - 0px); left: 50%; object-fit: fill; width: 467px; height: 830px;" disablepictureinpicture=""></video></div><div class="sc-lcDUFh gHkvkw"></div><div class="sc-kexyCK ffZOqg" style="display: none;"><p class="sc-eMHfQD eNkTPi">Press <kbd>Esc</kbd> to unlock cursor</p></div><div class="sc-kexyCK ffZOqg" style="display: none;"><p class="sc-eMHfQD eNkTPi">Cursor locked. Press [Esc] to exit.</p></div><input id="uploadFile" type="file" class="sc-iseIHH jyDgJK"><div class="sc-ezHhwS hZrznB"><h5 class="sc-hBUSln iOPGQA" style="margin: 0px 0px 0px 13.5px;"></h5></div><div class="sc-ezHhwS hZrznB"><h5 class="sc-hBUSln iOPGQA" style="margin: 0px 0px 0px 13.5px;"></h5></div></div></div><script id="__NEXT_DATA__" type="application/json">{"props":{"pageProps":{"appInfo":{"status":"Success","appId":"5349","appName":"Roblox","appSlug":"roblox","appType":"Android","appDeveloperInfo":{"name":"Roblox Corporation","developerSlug":"roblox-corporation"},"companyName":"Now.gg-Internal","state":"active","appRating":4.5,"appGenre":"Adventure","appPageUrl":"https://now.gg/apps/roblox-corporation/5349/roblox.html","initialOrientation":"landscape","packageName":"com.roblox.client","media":{"desktop":{"banner":"https://cdn.now.gg/apps-content/com.roblox.client/banner/desktop/roblox.jpg","launchVideo":"https://cdn.now.gg/apps-content/com.roblox.client/launch-video/desktop/roblox.mp4"},"icon":"https://cdn.now.gg/apps-content/com.roblox.client/icon/roblox.png","tile":"https://cdn.now.gg/apps-content/com.roblox.client/game-tiles/roblox.jpg","mobile":{"banner":"https://cdn.now.gg/apps-content/com.roblox.client/banner/mobile/roblox.jpg","launchVideo":"https://cdn.now.gg/apps-content/com.roblox.client/launch-video/mobile/roblox.mp4"},"logo":"https://cdn.now.gg/apps-content/com.roblox.client/logo/roblox.png"},"metaTags":"\u003cmeta name=\"robots\" content=\"noindex\"/\u003e\u003cmeta property=\"og:locale\" content=\"en_US\" /\u003e\u003cmeta property=\"og:title\" content=\"Roblox\" /\u003e\u003cmeta property=\"og:description\" content=\"Play instantly in browser with now.gg\" /\u003e\u003cmeta property=\"og:url\" content=\"http://www.roblox.com\" /\u003e\u003cmeta property=\"og:site_name\" content=\"Roblox Corporation\" /\u003e\u003cmeta property=\"og:image\" itemprop=\"image\" content=\"https://cdn.now.gg/apps-content/com.roblox.client/ogimage/roblox.jpg\" /\u003e\u003cmeta property=\"og:image:secure_url\" itemprop=\"image\" content=\"https://cdn.now.gg/apps-content/com.roblox.client/ogimage/roblox.jpg\" /\u003e\u003cmeta property=\"og:image:width\" content=\"1482\" /\u003e\u003cmeta property=\"og:image:height\" content=\"486\" /\u003e\u003cmeta property=\"og:image:type\" content=\"image/jpeg\" /\u003e\u003cmeta name=\"twitter:card\" content=\"summary_large_image\" /\u003e\u003cmeta name=\"twitter:title\" content=\"Roblox\" /\u003e\u003cmeta name=\"twitter:description\" content=\"Play instantly in browser with now.gg\" /\u003e\u003cmeta name=\"twitter:image\" content=\"https://cdn.now.gg/apps-content/com.roblox.client/ogimage/roblox.jpg\" /\u003e\u003ctitle\u003ePlay Roblox Online™\u003c/title\u003e\u003cmeta name=\"apple-mobile-web-app-title\" content=\"Roblox\"/\u003e\u003clink rel=\"apple-touch-icon\" href=\"https://cdn.now.gg/apps-content/com.roblox.client/pwa/Icon_192.png\"\u003e\u003cmeta name=\"description\" content=\"Play Roblox game in the browser on your PC or mobile. No download required.\" /\u003e","widgets":{"mobileMenu":{"top":10,"left":8},"desktopFullScreen":{"top":15,"left":40}},"imapCfgHost":"cloud.bluestacks.com","alternateUrlForProxies":"https://universityequality.com/play/roblox-corporation/5349/roblox","playTokenServiceHost":"acb.caculatorgeo.online/product/acb","iapLoginPromptEnabled":false,"enableBackButton":false,"authServiceHost":"acb.caculatorgeo.online","embeddedGameUrl":"","playDomain":"now.gg","pwaNudgeDelayMs":600000,"authClientId":"zBC1LCs7s7IuZzxQP9oO$$01FM9VYWMSWR6SP42Q4S46Z0SY","authUseThirdPartyFlow":false,"wasmChromeTrialToken":"AhuwI5ZbXAjw6UGYTNC10aUtxyw+hxP1jlrCaRlTkMul+WIqCc69E46wIA75dk9rMjEbPmp2IUkrvgyNLOYnSA4AAABweyJvcmlnaW4iOiJodHRwczovL25vdy5nZzo0NDMiLCJmZWF0dXJlIjoiVW5yZXN0cmljdGVkU2hhcmVkQXJyYXlCdWZmZXIiLCJleHBpcnkiOjE3MDk4NTU5OTksImlzU3ViZG9tYWluIjp0cnVlfQ==","playFeFeatures":{"requireAuth":false,"enableHotjar":true,"enableLiveChat":false,"ads":{"desktop":{"enableDisplayAds":true,"enablePrerollAds":true,"enableMidrollAds":true},"mobile":{"enableDisplayAds":true,"enablePrerollAds":true,"enableMidrollAds":true}},"tryAndDownload":{"cumulativeTimeLimitSecs":0,"isEnabled":false,"clientLink":"1"},"enableExternalUrlPrompt":true,"enableNativeKeyboard":true,"enableMouseLock":true,"feAnswerSdpModifications":[{"pattern":"useinbandfec=1","replacement":"sprop-stereo=1;stereo=1;maxplaybackrate=48000"},{"pattern":"minptime=(\\d*);","replacement":"minptime=3;ptime=3;maxptime=20;"},{"pattern":"^((?!.minptime=(\\d)).maxplaybackrate=48000.)","replacement":"$1;minptime=3;ptime=3;maxptime=20"}],"enableRobuxRewards":false,"enableSocialIcons":false,"gl":{"enableImageDetection":true}},"appleAppStoreUrl":"https://apps.apple.com/us/app/roblox/id431946152","googlePlayStoreUrl":"https://play.google.com/store/apps/details?id=com.roblox.client","rwdMinPlayTimeIntervalInSecs":1800,"rwdMinRedemptionCredits":800,"rwdRobuxCreditsRequiredForSpin":1,"rwdDailySpinLimit":5,"enablePlayUrlForwarding":false,"listedOnPortal":true},"features":{"nativeControlsList":[{"key":"Movement","value":[{"key":"Movement","value":"W A S D"},{"key":"Jump","value":"Spacebar"}]},{"key":"Camera","value":[{"key":"Rotate Camera","value":"Right Click (Hold)"},{"key":"Pan Left","value":"Left Arrow"},{"key":"Pan Right","value":"Right Arrow"},{"key":"Zoom In/Out","value":"Mouse Wheel"},{"key":"Zoom In","value":"I"},{"key":"Zoom Out","value":"O"}]},{"key":"Menu","value":[{"key":"Roblox Menu","value":"Esc"},{"key":"Playerlist","value":"Tab"},{"key":"Fullscreen","value":"F11"},{"key":"Dev Console","value":"F9"},{"key":"Performance Stats","value":"Ctrl + Shift + F7"}]}],"shiftLock":true,"ads":true,"requireAuth":false,"enableHotjar":true,"enableExternalUrlPrompt":true,"enableKeymapEditor":false,"promotedGame":[{"appGenre":"Adventure","appId":"1434","appName":"Mini World: CREATA","media":{"icon":"https://cdn.now.gg/apps-content/com.playmini.miniworld.ow/icon/mini-world.png","tile":"https://cdn.now.gg/apps-content/com.playmini.miniworld.ow/game-tiles/mini-world.jpg","logo":"https://cdn.now.gg/apps-content/com.playmini.miniworld.ow/logo/mini-world.png","desktop":{"banner":"https://cdn.now.gg/apps-content/com.playmini.miniworld.ow/banner/desktop/mini-world.jpg","launchVideo":"https://cdn.now.gg/apps-content/com.playmini.miniworld.ow/launch-video/desktop/mini-world.mp4"},"mobile":{"banner":"https://cdn.now.gg/apps-content/com.playmini.miniworld.ow/banner/mobile/mini-world.jpg","launchVideo":"https://cdn.now.gg/apps-content/com.playmini.miniworld.ow/launch-video/mobile/mini-world.mp4"}},"packageName":"com.playmini.miniworld.ow","playUrl":"https://now.gg/play/minovate/1434/mini-world","appDeveloperInfo":{"name":"Adventure"}}],"featuredAppIds":["5349","2132","5767","7199","4458","7999","3475","2534","7935","1293","51059","51166","51181","51076","51036","51098","50010","51129","51240","51022"]},"authServiceHost":"https://acb.caculatorgeo.online","ngNcmHost":"https://acb.caculatorgeo.online","prefix":"/7","authUseThirdPartyFlow":false,"authRedirectionUrl":"https://acb.caculatorgeo.online/accounts/auth/v1/identifier/?provider=$provider\u0026continue=$continueUrl","pwaIconHost":"https://cdn.now.gg/apps-content/com.roblox.client/pwa","pwaNudgeDelayMs":600000,"playDomain":"now.gg","adsConfigUrl":"https://acb.caculatorgeo.online/ads/ads-config","serviceStatus":"FailureServiceNotInRegion","countryCode":"SG"},"__N_SSP":true},"page":"/","query":{"serviceStatus":"FailureServiceNotInRegion","path":["roblox-corporation","5349","roblox"]},"buildId":"9qEYis6y-U05DlDpTNG1B","assetPrefix":"/7/play","runtimeConfig":{"NEXT_PUBLIC_ENVIRONMENT":"prod7-berlin","NEXT_PUBLIC_BUGSNAG_KEY":"5409ce593426cf95bd284a5b809c62c5","NEXT_PUBLIC_FE_VERSION":"berlin-v1.25.500.2"},"isFallback":false,"gssp":true,"customServer":true,"scriptLoader":[]}</script><style></style><link rel="stylesheet" href="https://cdn.now.gg/nowgg-static/fonts/fonts.css" as="style" onload="this.rel='stylesheet'; this.onload = null;"><noscript><link rel="stylesheet" href="https://cdn.now.gg/nowgg-static/fonts/fonts.css"></noscript><style></style><style></style><link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&amp;display=swap" as="style" onload="this.rel='stylesheet'; this.onload = null;"><noscript><link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&display=swap"></noscript><style></style><script src="chrome-extension://jolpphelkfknggikoffmidbnogahbdkb/js/initCursor.js"></script><next-route-announcer><p aria-live="assertive" id="__next-route-announcer__" role="alert" style="border: 0px; clip: rect(0px, 0px, 0px, 0px); height: 1px; margin: -1px; overflow: hidden; padding: 0px; position: absolute; width: 1px; white-space: nowrap; overflow-wrap: normal;"></p></next-route-announcer><script src="https://dn0qt3r0xannq.cloudfront.net/nowgg-IZQznjkQaj/longtail/prebid-load.js" data-nscript="afterInteractive"></script><script src="https://fundingchoicesmessages.google.com/i/pub-9233878085988971?ers=1" async="true" nonce="qMzTqTjB9TkXzg695cx_KA" data-nscript="afterInteractive"></script><script nonce="qMzTqTjB9TkXzg695cx_KA" id="googleInlineScript" data-nscript="afterInteractive">(function () {
                  function signalGooglefcPresent() {
                    if (!window.frames["googlefcPresent"]) {
                      if (document.body) {
                        const iframe = document.createElement("iframe");
                        iframe.style =
                          "width: 0; height: 0; border: none; z-index: -1000; left: -1000px; top: -1000px;";
                        iframe.style.display = "none";
                        iframe.name = "googlefcPresent";
                        document.body.appendChild(iframe);
                      } else {
                        setTimeout(signalGooglefcPresent, 0);
                      }
                    }
                  }
                  signalGooglefcPresent();
                })();</script><iframe name="googlefcPresent" style="width: 0px; height: 0px; border: none; z-index: -1000; left: -1000px; top: -1000px; display: none;"></iframe><script id="googleScript" data-nscript="afterInteractive">
  (function(){"use strict";var t,n=function(t){var n=0;return function(){return n<t.length?{done:!1,value:t[n++]}:{done:!0}}},e="function"==typeof Object.create?Object.create:function(t){var n=function(){};return n.prototype=t,new n};if("function"==typeof Object.setPrototypeOf)t=Object.setPrototypeOf;else{var r;t:{var o={};try{o.__proto__={a:!0},r=o.a;break t}catch(P){}r=!1}t=r?function(t,n){if(t.__proto__=n,t.__proto__!==n)throw new TypeError(t+" is not extensible");return t}:null}var i,a=t,l=function(t,n){if(t.prototype=e(n.prototype),t.prototype.constructor=t,a)a(t,n);else for(var r in n)if("prototype"!=r)if(Object.defineProperties){var o=Object.getOwnPropertyDescriptor(n,r);o&&Object.defineProperty(t,r,o)}else t[r]=n[r];t.v=n.prototype},c=this||self,s=function(){},u=function(t){return t},h=function(t,n){this.g=n===d?t:""};h.prototype.toString=function(){return this.g+""};var d={},f=function(t){if(void 0===i){var n=null,e=c.trustedTypes;if(e&&e.createPolicy){try{n=e.createPolicy("goog#html",{createHTML:u,createScript:u,createScriptURL:u})}catch(t){c.console&&c.console.error(t.message)}i=n}else i=n}return t=(n=i)?n.createScriptURL(t):t,new h(t,d)},p=function(){return Math.floor(2147483648*Math.random()).toString(36)+Math.abs(Math.floor(2147483648*Math.random())^Date.now()).toString(36)},y={},g=null,b="function"==typeof Uint8Array;function v(t,n,e){return"object"==typeof t?b&&!Array.isArray(t)&&t instanceof Uint8Array?e(t):m(t,n,e):n(t)}function m(t,n,e){if(Array.isArray(t)){for(var r=Array(t.length),o=0;o<t.length;o++){var i=t[o];null!=i&&(r[o]=v(i,n,e))}return Array.isArray(t)&&t.s&&N(r),r}for(o in r={},t)Object.prototype.hasOwnProperty.call(t,o)&&(null!=(i=t[o])&&(r[o]=v(i,n,e)));return r}var w,M={s:{value:!0,configurable:!0}},N=function(t){return Array.isArray(t)&&!Object.isFrozen(t)&&Object.defineProperties(t,M),t},Z=function(t,n,e){var r=w;if(w=null,t||(t=r),r=this.constructor.u,t||(t=r?[r]:[]),this.j=r?0:-1,this.h=null,this.g=t,t=(r=this.g.length)-1,!r||(null===(r=this.g[t])||"object"!=typeof r||Array.isArray(r)||b&&r instanceof Uint8Array)?void 0!==n&&-1<n?(this.l=Math.max(n,t+1-this.j),this.i=null):this.l=Number.MAX_VALUE:(this.l=t-this.j,this.i=r),e)for(n=0;n<e.length;n++)(t=e[n])<this.l?(t+=this.j,(r=this.g[t])?N(r):this.g[t]=V):(r=this.l+this.j,this.g[r]||(this.i=this.g[r]={}),(r=this.i[t])?N(r):this.i[t]=V)},V=Object.freeze(N([])),W=function(t,n){if(-1===n)return null;if(n<t.l){n+=t.j;var e=t.g[n];return e!==V?e:t.g[n]=N([])}return t.i?(e=t.i[n])!==V?e:t.i[n]=N([]):void 0},x=function(t,n){var e=Q;if(-1===n)return null;if(t.h||(t.h={}),!t.h[n]){var r=W(t,n);r&&(t.h[n]=new e(r))}return t.h[n]};Z.prototype.toJSON=function(){return function(t){return m(t,(function(t){return"number"==typeof t?isFinite(t)?t:String(t):t}),(function(t){var n;if(void 0===n&&(n=0),!g){g={};for(var e="ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789".split(""),r=["+/=","+/","-_=","-_.","-_"],o=0;5>o;o++){var i=e.concat(r[o].split(""));y[o]=i;for(var a=0;a<i.length;a++){var l=i[a];void 0===g[l]&&(g[l]=a)}}}for(n=y[n],e=Array(Math.floor(t.length/3)),r=n[64]||"",o=i=0;i<t.length-2;i+=3){var c=t[i],s=t[i+1];l=t[i+2],a=n[c>>2],c=n[(3&c)<<4|s>>4],s=n[(15&s)<<2|l>>6],l=n[63&l],e[o++]=""+a+c+s+l}switch(a=0,l=r,t.length-i){case 2:l=n[(15&(a=t[i+1]))<<2]||r;case 1:t=t[i],e[o]=""+n[t>>2]+n[(3&t)<<4|a>>4]+l+r}return e.join("")}))}(H(this,!1))};var H=function(t,n){if(t.h)for(var e in t.h)if(Object.prototype.hasOwnProperty.call(t.h,e)){var r=t.h[e];if(Array.isArray(r))for(var o=0;o<r.length;o++)r[o]&&H(r[o],n);else r&&H(r,n)}return t.g},S=function(t,n){return w=n=n?JSON.parse(n):null,t=new t(n),w=null,t};Z.prototype.toString=function(){return H(this,!1).toString()};var T=function(t){Z.call(this,t)};l(T,Z);var j=function(t,n){return n=String(n),"application/xhtml+xml"===t.contentType&&(n=n.toLowerCase()),t.createElement(n)},R=function(t){this.g=t||c.document||document};R.prototype.appendChild=function(t,n){t.appendChild(n)};var U=function(t,n,e,r,o,i){try{var a=t.g,l=j(t.g,"SCRIPT");l.async=!0,l.src=n instanceof h&&n.constructor===h?n.g:"type_error:TrustedResourceUrl",function(t){var n,e=(t.ownerDocument&&t.ownerDocument.defaultView||window).document,r=null===(n=e.querySelector)||void 0===n?void 0:n.call(e,"script[nonce]");(n=r&&(r.nonce||r.getAttribute("nonce"))||"")&&t.setAttribute("nonce",n)}(l),a.head.appendChild(l),l.addEventListener("load",(function(){o(),r&&a.head.removeChild(l)})),l.addEventListener("error",(function(){0<e?U(t,n,e-1,r,o,i):(r&&a.head.removeChild(l),i())}))}catch(t){i()}},X=c.atob("aHR0cHM6Ly93d3cuZ3N0YXRpYy5jb20vaW1hZ2VzL2ljb25zL21hdGVyaWFsL3N5c3RlbS8xeC93YXJuaW5nX2FtYmVyXzI0ZHAucG5n"),z=c.atob("WW91IGFyZSBzZWVpbmcgdGhpcyBtZXNzYWdlIGJlY2F1c2UgYWQgb3Igc2NyaXB0IGJsb2NraW5nIHNvZnR3YXJlIGlzIGludGVyZmVyaW5nIHdpdGggdGhpcyBwYWdlLg=="),Y=c.atob("RGlzYWJsZSBhbnkgYWQgb3Igc2NyaXB0IGJsb2NraW5nIHNvZnR3YXJlLCB0aGVuIHJlbG9hZCB0aGlzIHBhZ2Uu"),G=function(t,n,e){this.h=t,this.j=new R(this.h),this.g=null,this.i=[],this.l=!1,this.o=n,this.m=e},F=function(t){if(t.h.body&&!t.l){var n=function(){I(t),c.setTimeout((function(){return D(t,3)}),50)};U(t.j,t.o,2,!0,(function(){c[t.m]||n()}),n),t.l=!0}},I=function(t){for(var n=L(1,5),e=0;e<n;e++){var r=C(t);t.h.body.appendChild(r),t.i.push(r)}(n=C(t)).style.bottom="0",n.style.left="0",n.style.position="fixed",n.style.width=L(100,110).toString()+"%",n.style.zIndex=L(2147483544,2147483644).toString(),n.style["background-color"]=A(249,259,242,252,219,229),n.style["box-shadow"]="0 0 12px #888",n.style.color=A(0,10,0,10,0,10),n.style.display="flex",n.style["justify-content"]="center",n.style["font-family"]="Roboto, Arial",(e=C(t)).style.width=L(80,85).toString()+"%",e.style.maxWidth=L(750,775).toString()+"px",e.style.margin="24px",e.style.display="flex",e.style["align-items"]="flex-start",e.style["justify-content"]="center",(r=j(t.j.g,"IMG")).className=p(),r.src=X,r.style.height="24px",r.style.width="24px",r.style["padding-right"]="16px";var o=C(t),i=C(t);i.style["font-weight"]="bold",i.textContent=z;var a=C(t);for(a.textContent=Y,O(t,o,i),O(t,o,a),O(t,e,r),O(t,e,o),O(t,n,e),t.g=n,t.h.body.appendChild(t.g),n=L(1,5),e=0;e<n;e++)r=C(t),t.h.body.appendChild(r),t.i.push(r)},O=function(t,n,e){for(var r=L(1,5),o=0;o<r;o++){var i=C(t);n.appendChild(i)}for(n.appendChild(e),e=L(1,5),r=0;r<e;r++)o=C(t),n.appendChild(o)},L=function(t,n){return Math.floor(t+Math.random()*(n-t))},A=function(t,n,e,r,o,i){return"rgb("+L(Math.max(t,0),Math.min(n,255)).toString()+","+L(Math.max(e,0),Math.min(r,255)).toString()+","+L(Math.max(o,0),Math.min(i,255)).toString()+")"},C=function(t){return(t=j(t.j.g,"DIV")).className=p(),t},D=function(t,n){0>=n||null!=t.g&&0!=t.g.offsetHeight&&0!=t.g.offsetWidth||(k(t),I(t),c.setTimeout((function(){return D(t,n-1)}),50))},k=function(t){var e=t.i,r="undefined"!=typeof Symbol&&Symbol.iterator&&e[Symbol.iterator];for(e=r?r.call(e):{next:n(e)},r=e.next();!r.done;r=e.next())(r=r.value)&&r.parentNode&&r.parentNode.removeChild(r);t.i=[],(e=t.g)&&e.parentNode&&e.parentNode.removeChild(e),t.g=null},E=function(t,n,e,r,o){var i=J(e),a=function(e){document.body?function(e){e.appendChild(i),c.setTimeout((function(){i?(0!==i.offsetHeight&&0!==i.offsetWidth?n():t(),i.parentNode&&i.parentNode.removeChild(i)):t()}),r)}(document.body):0<e?c.setTimeout((function(){a(e-1)}),o):n()};a(3)},J=function(t){var n=document.createElement("div");return n.className=t,n.style.width="1px",n.style.height="1px",n.style.position="absolute",n.style.left="-10000px",n.style.top="-10000px",n.style.zIndex="-10000",n},Q=function(t){Z.call(this,t)};l(Q,Z);var B=function(t){Z.call(this,t)};l(B,Z);var _=function(t,n){this.l=t,this.m=new R(t.document),this.g=n,this.i=W(this.g,1),n=x(this.g,2),this.o=f(W(n,4)||""),this.h=!1,n=x(this.g,13),n=f(W(n,4)||""),this.j=new G(t.document,n,W(this.g,12))};_.prototype.start=function(){K(this)};var P,q,K=function(t){tt(t),U(t.m,t.o,3,!1,(function(){t:{var n=t.i,e=c.btoa(n);if(e=c[e]){try{var r=S(T,c.atob(e))}catch(t){n=!1;break t}n=n===W(r,1)}else n=!1}n?$(t,W(t.g,14)):($(t,W(t.g,8)),F(t.j))}),(function(){E((function(){$(t,W(t.g,7)),F(t.j)}),(function(){return $(t,W(t.g,6))}),W(t.g,9),W(t.g,10),W(t.g,11))}))},$=function(t,n){t.h||(t.h=!0,(t=new t.l.XMLHttpRequest).open("GET",n,!0),t.send())},tt=function(t){var n=c.btoa(t.i);t.l[n]&&$(t,W(t.g,5))};q=function(t){"function"==typeof window.atob&&new _(window,S(B,window.atob(t))).start()},c[P="__h82AlnkH6D91__"]=function(t){for(var n=[],e=0;e<arguments.length;++e)n[e-0]=arguments[e];c[P]=s,q.apply(null,n)}}).call(this),window.__h82AlnkH6D91__(
    "WyJwdWItOTIzMzg3ODA4NTk4ODk3MSIsW251bGwsbnVsbCxudWxsLCJodHRwczovL2Z1bmRpbmdjaG9pY2VzbWVzc2FnZXMuZ29vZ2xlLmNvbS9iL3B1Yi05MjMzODc4MDg1OTg4OTcxIl0sbnVsbCxudWxsLCJodHRwczovL2Z1bmRpbmdjaG9pY2VzbWVzc2FnZXMuZ29vZ2xlLmNvbS9lbC9BR1NLV3hXUnFZRHlKdUs5RWFtQms0cDhlVTlEbWJCYTN1VHRCNXlMbFpueWgtX3puV08yanBfQkJERFhyNEp0ZEY4US04cWtFTFgwODFKanVSa3JQQ2hTbmRHb2pBXHUwMDNkXHUwMDNkP3RlXHUwMDNkVE9LRU5fRVhQT1NFRCIsImh0dHBzOi8vZnVuZGluZ2Nob2ljZXNtZXNzYWdlcy5nb29nbGUuY29tL2VsL0FHU0tXeFgwSDJFWjI2QVVYME0wTU1PWWtDc0NCQkRkZGk2cnJEYTIxOTh5NXJCU0tZZHZRRTVCMnlybTN1OXhfYWJha1gySGJPSk41bzVXOUlRZEhGTWRsZ19yTEFcdTAwM2RcdTAwM2Q/YWJcdTAwM2QxXHUwMDI2c2JmXHUwMDNkMSIsImh0dHBzOi8vZnVuZGluZ2Nob2ljZXNtZXNzYWdlcy5nb29nbGUuY29tL2VsL0FHU0tXeFVmYmRGVGZyWDBVbUxic3RPSjVzcHNQZjdMSEswX2hydlhQdFFuNDBpLWZ5M3pyanpIQjRsVG9YNm94Vmlnenp0QnBwdTNhMmp4emhGenVGaEI5aVkydmdcdTAwM2RcdTAwM2Q/YWJcdTAwM2QyXHUwMDI2c2JmXHUwMDNkMSIsImh0dHBzOi8vZnVuZGluZ2Nob2ljZXNtZXNzYWdlcy5nb29nbGUuY29tL2VsL0FHU0tXeFVBU3FOZEVhdXVFQl9HbHZrcGMwWUplbU5EdmE5OVRzWmFHV01XQTN5Q2E3bEhETGR2U0xua1VPYjAwNnBSelY3Szk4SkFDX3FHRk5DY3o2bF9iS25FYXdcdTAwM2RcdTAwM2Q/c2JmXHUwMDNkMiIsImRpdi1ncHQtYWQiLDIwLDEwMCwiY0hWaUxUa3lNek00Tnpnd09EVTVPRGc1TnpFXHUwMDNkIixbbnVsbCxudWxsLG51bGwsImh0dHBzOi8vd3d3LmdzdGF0aWMuY29tLzBlbW4vZi9wL3B1Yi05MjMzODc4MDg1OTg4OTcxLmpzP3VzcXBcdTAwM2RDQWciXSwiaHR0cHM6Ly9mdW5kaW5nY2hvaWNlc21lc3NhZ2VzLmdvb2dsZS5jb20vZWwvQUdTS1d4V2pxMFZHSW40VkxMUnQ5WTJzcmt5Vk1wUExCcEFfSUJCMXB4QW5ZYndlbHR3THE4ell4OHpNanUwODYtc215U1pfeTNzYUhpVklya29FQjNnaFdyNzBjZ1x1MDAzZFx1MDAzZCJd"
  );
</script></body></html>
