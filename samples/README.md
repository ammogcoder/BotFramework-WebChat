# Web Chat hosted samples

Here you can find all hosted samples of [Web Chat](https://github.com/Microsoft/BotFramework-WebChat). The source code repository can be found on [GitHub](https://github.com/Microsoft/BotFramework-WebChat/tree/master/samples).

> These samples are connected to MockBot, a bot for testing various features of Web Chat. The source code of MockBot can be found on [GitHub](https://github.com/compulim/BotFramework-MockBot).

## Basics

This section covers samples helping you to jumpstart embedding Web Chat in your existing web site.

### Thru CDN

For simplicity, you can use a `<script>` tag to embed Web Chat from a CDN.

- [Full bundle](https://microsoft.github.io/BotFramework-WebChat/1.a.getting-started-full-bundle) [(source)](https://github.com/Microsoft/BotFramework-WebChat/tree/master/samples/1.a.getting-started-full-bundle)
- [Full bundle with polyfills for ES5 browsers](https://microsoft.github.io/BotFramework-WebChat/1.b.getting-started-es5-bundle) [(source)](https://github.com/Microsoft/BotFramework-WebChat/tree/master/samples/1.b.getting-started-es5-bundle)
- [Minimal bundle](https://microsoft.github.io/BotFramework-WebChat/2.a.getting-started-minimal-bundle) [(source)](https://github.com/Microsoft/BotFramework-WebChat/tree/master/samples/2.a.getting-started-minimal-bundle)
- [Minimal bundle with Markdown](https://microsoft.github.io/BotFramework-WebChat/2.b.getting-started-minimal-markdown) [(source)](https://github.com/Microsoft/BotFramework-WebChat/tree/master/samples/2.b.getting-started-minimal-markdown)

> You can look at this [sunburst chart](http://cdn.botframework.com/botframework-webchat/master/stats.html) for better understanding on the content of various bundles.

Web Chat offer different bundle varieties as outlined in the table below.

| | Minimal | Full | Full with ES5 polyfills |
| - | - | - | - |
| [Adaptive Cards](https://adaptivecards.io/) | | Yes | Yes |
| [Cognitive Services Bing Speech](https://azure.microsoft.com/en-us/services/cognitive-services/speech/) | | Yes | Yes |
| [DirectLineJS](https://npmjs.com/package/botframework-directlinejs) | Yes | Yes | Yes |
| [Markdown-It](https://npmjs.com/package/markdown-it/) | | Yes | Yes |
| [`sanitize-html`](https://npmjs.com/package/sanitize-html) | | Yes | Yes |
| ES5 Polyfills (for IE11) | | | Yes |

> Rich card (e.g. hero card, receipt card) requires Adaptive Cards.

### Thru NPM (as a React component)

You can also embed Web Chat as a React component from NPM. This is a more advanced approach and requires knowledge of React and bundling.

This approach will give you lots of flexibility to style and customize the component, including breaking down Web Chat into pieces and recompose back into a component.

- [Integrate with React](https://microsoft.github.io/BotFramework-WebChat/3.a.host-with-react) [(source)](https://github.com/Microsoft/BotFramework-WebChat/tree/master/samples/3.a.host-with-react)

## Styling

Web Chat can be styled in many ways without too much coding.

- [Avatar initials](https://microsoft.github.io/BotFramework-WebChat/4.display-user-bot-initials-styling) [(source)](https://github.com/Microsoft/BotFramework-WebChat/tree/master/samples/4.display-user-bot-initials-styling)
- [Custom style options](https://microsoft.github.io/BotFramework-WebChat/5.a.branding-webchat-styling) [(source)](https://github.com/Microsoft/BotFramework-WebChat/tree/master/samples/5.a.branding-webchat-styling)
- [Custom style set](https://microsoft.github.io/BotFramework-WebChat/5.b.idiosyncratic-manual-styling) [(source)](https://github.com/Microsoft/BotFramework-WebChat/tree/master/samples/5.b.idiosyncratic-manual-styling)
- [Presentation mode](https://microsoft.github.io/BotFramework-WebChat/5.c.presentation-mode-styling) [(source)](https://github.com/Microsoft/BotFramework-WebChat/tree/master/samples/5.c.presentation-mode-styling)

## Speech support

To use Cognitive Services or your own speech engine withWeb Chat, these samples will give you a headstart.

- Cognitive Services Bing Speech API
   - [Using JavaScript](https://microsoft.github.io/BotFramework-WebChat/6.a.cognitive-services-bing-speech-js) [(source)](https://github.com/Microsoft/BotFramework-WebChat/tree/master/samples/6.a.cognitive-services-bing-speech-js)
   - [Using React](https://microsoft.github.io/BotFramework-WebChat/6.b.cognitive-services-bing-speech-react) [(source)](https://github.com/Microsoft/BotFramework-WebChat/tree/master/samples/6.b.cognitive-services-bing-speech-react)
- [Speech thru a supported browsers](https://microsoft.github.io/BotFramework-WebChat/6.d.speech-web-browser) [(source)](https://github.com/Microsoft/BotFramework-WebChat/tree/master/samples/6.d.speech-web-browser)
   - [List of supported browsers](https://caniuse.com/#search=speech)

## Customization

If styling cannot met your need, you can customize Web Chat by extend the render pipeline or break it down and recompose it.

### Activity and attachment

To add, decorate, replace, or remove activity or attachment, these samples will give you a headstart.

- [Activity decorator: Button](https://microsoft.github.io/BotFramework-WebChat/9.customization-reaction-buttons) [(source)](https://github.com/Microsoft/BotFramework-WebChat/tree/master/samples/9.customization-reaction-buttons)
- [Activity decorator: Highlight](https://microsoft.github.io/BotFramework-WebChat/8.customization-user-highlighting) [(source)](https://github.com/Microsoft/BotFramework-WebChat/tree/master/samples/8.customization-user-highlighting)
- [Custom attachment: GitHub repository](https://microsoft.github.io/BotFramework-WebChat/10.customization-card-components) [(source)](https://github.com/Microsoft/BotFramework-WebChat/tree/master/samples/10.customization-card-components)
- [Web Chat API via Redux](https://microsoft.github.io/BotFramework-WebChat/11.customization-redux-actions) [(source)](https://github.com/Microsoft/BotFramework-WebChat/tree/master/samples/11.customization-redux-actions)

## Backchannel

On your web site, instead of connecting to your backend thru REST/Web Socket API, you can also connect thru Direct Line activities. This gives you flexibility of delivering content to your users.

- [Pipe activities to Redux as actions](https://microsoft.github.io/BotFramework-WebChat/14.customization-piping-to-redux) [(source)](https://github.com/Microsoft/BotFramework-WebChat/tree/master/samples/14.customization-piping-to-redux)

## Breakaway components

If you want to deep-customize Web Chat, you can break Web Chat into multiple breakaway components and join them back together.

- [Minimize mode](https://microsoft.github.io/BotFramework-WebChat/12.customization-minimizable-web-chat) [(source)](https://github.com/Microsoft/BotFramework-WebChat/tree/master/samples/12.customization-minimizable-web-chat)
- [Speech button](https://microsoft.github.io/BotFramework-WebChat/13.customization-speech-ui) [(source)](https://github.com/Microsoft/BotFramework-WebChat/tree/master/samples/13.customization-speech-ui)

## Timestamps

Timestamps can be grouped using various settings.

- [Group timestamps](https://microsoft.github.io/BotFramework-WebChat/7.customization-timestamp-grouping) [(source)](https://github.com/Microsoft/BotFramework-WebChat/tree/master/samples/7.customization-timestamp-grouping)
