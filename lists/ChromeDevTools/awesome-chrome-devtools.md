<h1 align="center">
Ranked awesome lists, all in one place
</h1>
<p align="center">
	This list is a copy of <a href="https://github.com/ChromeDevTools/awesome-chrome-devtools">https://github.com/ChromeDevTools/awesome-chrome-devtools</a> with ranks
</p>
---
# Awesome chrome-devtools [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★57421](https://github.com/sindresorhus/awesome)

> Awesome tooling and resources in the Chrome DevTools ecosystem

## Learning
- [Dev Tips](https://umaar.com/dev-tips/) - Large collection of tips as animated gifs.

### DevTools as an IDE
- [Chrome DevTools App ★1389 ⏳1Y](https://github.com/auchenberg/chrome-devtools-app) - Standalone app which can inspect various targets.
- [DevTools Remote ★515](https://github.com/auchenberg/devtools-remote) - Remotely debug someone else's browser.
- [DevTools Snippets ★1182](https://github.com/bahmutov/code-snippets) - Collection of snippets.

### Node.js + DevTools
- [chrome-remote-interface](https://github.com/cyrus-and/chrome-remote-interface) - The recommended Node.js API for the protocol. There are also [TypeScript-friendly alternatives ★53 ⏳1Y](https://github.com/DickvdBrink/chrome-debug-protocol).
- [chrome-devtools-frontend](https://www.npmjs.com/package/chrome-devtools-frontend) - Mirror of the frontend shipping in Chrome.
- [chrome-timeline-model](https://www.npmjs.com/package/devtools-timeline-model) - Uses frontend as lib to process profiling data.
- [crmux ★79](https://github.com/sidorares/crmux) - Multiplexes protocol connections.
- [crconsole ★165](https://github.com/sidorares/crconsole) - Terminal based chrome console and debugger.

### Chrome Debugging Protocol
- [Debugging Protocol Viewer](https://chromedevtools.github.io/debugger-protocol-viewer/) - Easy browsable UI for exploring the protocol's domains, methods and events
- [Remote Debug Gateway ★54 ⏳1Y](https://github.com/RemoteDebug/remotedebug-gateway) - Allows you to connect a client to multiple browsers at once.
- [Remote Debug Firefox adapter ★103](https://github.com/RemoteDebug/remotedebug-firefox-adapter) - Translates Firefox's devtools protocol to the CDP
- [ios-webkit-debug-proxy ★2737](https://github.com/google/ios-webkit-debug-proxy) - Exposes Mobile Safari & UIWebView instances via the CDP.
- [Remote Debug iOS WebKit adapter ★120](https://github.com/RemoteDebug/remotedebug-ios-webkit-adapter) - Builts upon ios-webkit-debug-proxy and translates WebKit's Remote Debugging Protocol API to the CDP
- [IE Diagnostics Adapter ★527](https://github.com/Microsoft/IEDiagnosticsAdapter) - Protocol adaptor for Microsoft IE 10/11 to CDP.
- [Edge Diagnostics Adaptor](https://github.com/Microsoft/edge-diagnostics-adaptor) - Protocol adaptor that enables tools to debug Edge using the CDP.
- [devtools-compat-proxy ★13](https://github.com/artygus/devtools-compat-proxy) - Young effort to translate modern Safari debugging protocol to modern CDP.
- [crmux ★79](https://github.com/sidorares/crmux) - Multiplexer to handle multiple clients.
- [RemoteDebug](https://github.com/RemoteDebug) - Initiative to normalize debugging protocols across today's browsers.

### Debugging Android & iOS w/ DevTools
- [PonyDebugger ★5351](https://github.com/square/PonyDebugger) - Remote network and data debugging iOS apps with Chrome DevTools
- [Facebook Stetho ★7492](https://github.com/facebook/stetho) - Native Android debugging with Chrome DevTools

### Debugging Node.js w/ DevTools
- [Debugging Node.js with Chrome DevTools](https://medium.com/@paul_irish/debugging-node-js-nightlies-with-chrome-devtools-7c4a1b95ae27) - New, native support for full debugging and profiling in Node v6.3+
- [devtool](https://github.com/Jam3/devtool) - Debug & profile Node.js apps with Chrome DevTools (using Electron).
- [buggerJS ★150](https://github.com/buggerjs/bugger) - Provides Chrome DevTools bindings for node.

### Object formatting
- [immutable-devtools ★485 ⏳1Y](https://github.com/andrewdavey/immutable-devtools) - Custom formatter for Immutable-js values.

### Network Inspection
- [betwixt ★3437](https://github.com/kdzwinel/betwixt) - System level network proxy, providing inspection via Network panel

### CPU profile
- [JSCLegacyProfiler/json2trace](https://github.com/facebook/react-native/blob/master/JSCLegacyProfiler/json2trace) - Converts Safari's JavaScriptCore profiler output into `.cpuprofile`
- [call-trace](https://github.com/brendankenny/call-trace) - Can instrument your JS with hooks, and then generate a `.cpuprofile`  of the of the complete (non-sampled) execution. View either time or call counts.
- [cpuprofilify ★101](https://github.com/thlorenz/cpuprofilify) - Converts output of various profiling/sampling tools to the `.cpuprofile` format.
- [Wishbone python framework](http://wishbone.readthedocs.org/en/develop/miscellaneous.html#profiling) - Profiling data can export as `.cpuprofile`.

### Multimedia
- [snapline ★271 ⏳1Y](https://github.com/pmdartus/snapline) - Converts timeline screenshots to gif.

### Timeline, Tracing & Profiling
- [DevTools Timeline Viewer](https://chromedevtools.github.io/timeline-viewer/) - Share URLs of your timeline recordings.

### Chrome Debugger integration with Editors
- [Showcase Protocol Clients](https://developer.chrome.com/devtools/docs/debugging-clients) - Lists many editor integration extensions.
- [VS Code - Debugger for Chrome ★629](https://github.com/Microsoft/vscode-chrome-debug) - Chrome Debugger for Visual Studio Code

## Extensions

### Accessibility (A11y)
- [Chromelens](http://chromelens.xyz) - See how your web app will look to people with different types of vision and the path users will travel when tabbing through your page.

### Workflow
- [Clockwork](https://chrome.google.com/webstore/detail/clockwork/dmggabnehkmmfmdffgajcflpdjlnoemp?hl=en) - View PHP application profiling data.
- [Emulated Device Lab](https://chrome.google.com/webstore/detail/emulated-device-lab/oaonfodocibcdobdeelbbfggjombamff) - Experiment with multiple devices being emulated at the same time.
- [RailsPanel](https://chrome.google.com/webstore/detail/railspanel/gjpfobpafnhjhbajcjgccbbdofdckggg?hl=en-US) - View Ruby on Rails application profiling data.
- [React Developer Tools](https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi) - Inspect the React component hierarchies.
- [EmberJS Inspector](https://chrome.google.com/webstore/detail/ember-inspector/bmdblncegkenkacieihfhpjfppoconhi) - Allows you to inspect EmberJS objects in your application.
- [VueJS Developer Tools ★3451](https://github.com/vuejs/vue-devtools) - Inspect VueJS components and manipulate their data.
- [Angular Batarang](https://chrome.google.com/webstore/detail/angularjs-batarang/ighdmehidhipcmcojjgiloacoafjmpfk) - Inspect an Angular application's scope and profile its data.
- [Augury](https://augury.angular.io)  - Debugging and Profiling for Angular 2 applications.
- [Marionette Inspector](https://chrome.google.com/webstore/detail/marionette-inspector/fbgfjlockdhidoaempmjcddibjklhpka) - Inspect a Marionette application's views, events, and live data.
- [Backbone Debugger](https://chrome.google.com/webstore/detail/backbone-debugger/bhljhndlimiafopmmhjlgfpnnchjjbhd) - Inspect a Backbone application's views, models, events, and routes.
- [App Inspector for Sencha](https://chrome.google.com/webstore/detail/app-inspector-for-sencha/pbeapidedgdpniokbedbfbaacglkceae) - Inspect a Sencha ExtJS/Touch application's component tree, data stores, events, and layouts.
- [Redux Devtools](https://chrome.google.com/webstore/detail/redux-devtools/lmhkpmbekcpmknklioeibfkpmmfibljd) - Inspect Redux with actions history, undo and replay.
- [Three.js](https://chrome.google.com/webstore/detail/threejs-editor-extension/fbgbekpggeldiacgjkacbkkcbjhmakea/) - Edit any three.js project.
- [Insight ★676](https://github.com/3Dparallax/insight) - A WebGL debugging toolkit which enables more productive WebGL development and more efficient WebGL applications.
- [BEM devtools ★34 ⏳1Y](https://github.com/escaton/bem-chrome-devtools) - Inspect BEM entities expressed in `i-bem` framework.

### UX
- [DevTools Author](https://chrome.google.com/webstore/detail/devtools-author/egfhcfdfnajldliefpdoaojgahefjhhi) - A selection of themes to modify parts of DevTools related to authoring web applications.
- [Zero Dark Matrix](https://chrome.google.com/webstore/detail/devtools-theme-zero-dark/bomhdjeadceaggdgfoefmpeafkjhegbo) - Dark theme for Chrome Developer Tools.

### Performance
- [Chrome React Perf](https://chrome.google.com/webstore/detail/react-perf/hacmcodfllhbnekmghgdlplbdnahmhmm) - An Operation Interface for react-addons-perf Package.

### Testing
- [UI-automation-chrome-extension](https://chrome.google.com/webstore/detail/ui-automation/aacdhbhfmngpoiinjmphdcpalpdcmbpf/) - Provides simple DOM selectors with Java code snippets so you can write automated Selenium tests faster.

---
<p align="center">
	This list is a copy of <a href="https://github.com/ChromeDevTools/awesome-chrome-devtools">https://github.com/ChromeDevTools/awesome-chrome-devtools</a> with ranks
</p>