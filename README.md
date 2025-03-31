# koala-web-demo

This is a basic demo to show how to use Koala for web browsers, using the IIFE version of the library (i.e. an HTML script tag). It instantiates a Koala worker engine and uses it with the [@picovoice/web-voice-processor](https://www.npmjs.com/package/@picovoice/web-voice-processor) to access (and automatically downsample) microphone audio.
<br>
## AccessKey

Koala requires a valid Picovoice `AccessKey` at initialization. `AccessKey` acts as your credentials when using Picovoice SDKs.
You can get your `AccessKey` for free. Make sure to keep your `AccessKey` secret.
Signup or Login to [Picovoice Console](https://console.picovoice.ai/) to get your `AccessKey`.
<br>
## Install & run

Use `npm` to install the dependencies, and the `start` script to start a local web server hosting the demo.
<br>
```console
npm install 
```
<br>

```console
http-server -p (your port number)
```
