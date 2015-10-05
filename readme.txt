+ Potentially less reliance on custom Javascript libraries, using browser's native tech instead
+ Growing library of custom elements exist, that can be imported and simply dropped onto the page, minimal styling needed
	e.g. a Google map widget on the page could be achieved with <google-map lat="37.790" long="-122.390"></google-map>, passing in a couple of parameters
+ Allows for greater encapsulation of form, functionality - makes designing sites more modular. Shadow DOM functionality of Polymer

- At the moment, the Polyfills can be weighty and lead to performance issues, reportedly esp. on not fully compatible browsers, mobile devices
- Something similar to Polymer's custom elements could be achieved using Angular's element directives - although Angular does not use shadow DOM for style encapsulation
- Current documentation seems sparse, unclear - e.g. tough to find specific tutorials on passing objects between elements
- Big changes between Polymer .5 and 1.0, requiring tools to export/import elements between versions, and it seems rework is often needed - is this likely to be the case for future versions?
- Safari and IE seem slow on the uptake

Sites currently using Polymer:

Several Google, inc. Google Music
Github
News Corp
