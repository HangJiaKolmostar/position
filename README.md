# Get Geolocation from Web Browser

Since the [`navigator.geolocation.getCurrentPosition()`](https://developer.mozilla.org/en-US/docs/Web/API/Geolocation/getCurrentPosition) api of web browser is available only in [secure contexts](https://developer.mozilla.org/en-US/docs/Web/Security/Secure_Contexts) (HTTPS), this repo provides the geolocation accessing service which can be used on non-HTTPS web app.

## Usage

In your non-HTTPS web app, when you need to get the geolocation of user:
```js
window.open("https://weiminwangkolmostar.github.io/position/")
```
In the new window, the page will write the geolocation of user to users' clipboard and close the window after success.
