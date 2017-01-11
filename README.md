# X5WebView
解决Android WebView不同机型的兼容问题，用法同原生WebView一致。
注意包名引用：import com.tencent.smtt.sdk.WebView;
主要使用TBS（腾讯浏览服务）X5内核。
获取：
① http://x5.tencent.com/

② [![](https://jitpack.io/v/MiQt/X5WebView.svg)](https://jitpack.io/#MiQt/X5WebView)

	allprojects {
		repositories {
			...
			maven { url "https://jitpack.io" }
		}
	}


        dependencies {
	        compile 'com.github.MiQt:X5WebView:v2.6'
	}
