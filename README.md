##  全新的依赖包方式

第一: 添加下面代码到工程根目录 build.gradle  
Add it in your root build.gradle at the end of repositories:

`
allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
`
第二: 添加下面代码到工程APP目录下的 build.gradle  
Add it in your App build.gradle   Add the dependency:

`
dependencies {
	        compile 'com.github.hongyang51:SlidingMenuText:1.0.0'
	}
`

简单的使用强大的SlidingMenu 库 并且在Android Studio中依赖! 依赖方法请参考 
* http://blog.csdn.net/wooder111/article/details/49740431 
* 大牛勿喷!
