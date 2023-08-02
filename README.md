# 📱 Android Studio WebView Template
<p>
  <img alt="Version" src="https://img.shields.io/badge/version-1.1.0-blue.svg?cacheSeconds=2592000" />
 
</p>

### WebView Template for android studio based applications
![alt text](https://i.imgur.com/4kn0s5h.png)


## Updating displayed web page

- Update your Web Page link :

```webView.loadUrl("https://github.com/4r1ss"); ```  

> Line 18 , MainActivity.java

## Changing the action bar color

- Action Bar color can be change from : 

``` <color name="purple_700">#000000</color> ```

> Located in app > res > values > colors.xml

## Additional Properties

- Action Bar can be enabled by replacing : 

```android:theme="@style/Theme.AppCompat.NoActionBar">``` With ```android:theme="@style/Theme.AppCompat">```
> Line 16 , AndroidManifest.xml

- JavaScript can be enabled from :

```webSettings.setJavaScriptEnabled(true);```
> Line 21 , MainActivity.java

## License 

- [MIT](https://github.com/4r1ss/WebView_Template/blob/main/LICENSE)
