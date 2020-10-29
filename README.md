【springboot-selenium】
## springboot2.x集成selenium3.141.59

【注意】

	本人也是初次接触selenium，总结几点避免入坑的注意点，
	不要太在意浏览器版本过低有什么影响的，只要能满足你的需求就可以了。
	---->重要的话说三遍<-----
	1. 不管是chrome还是firefox最重要的就是他们驱动与浏览器之间的版本对应关系。
	2. 不管是chrome还是firefox最重要的就是他们驱动与浏览器之间的版本对应关系。
	3. 不管是chrome还是firefox最重要的就是他们驱动与浏览器之间的版本对应关系。

【如下地址可供参考】

	Selenium国内镜像地址：https://npm.taobao.org/mirrors/selenium
	chromedriver国内镜像地址： https://npm.taobao.org/mirrors/chromedriver/
	chrome国内下载地址：https://www.chromedownloads.net/chrome64win/
	geckodriver的github地址：https://github.com/mozilla/geckodriver/releases
	firefox浏览器各版本下载地址：http://ftp.mozilla.org/pub/firefox/releases/

【windows-项目使用版本对应关系供参考】
	
	jdk: 1.8.0_171

	chrome：
		chromedriver.exe --> 80.0.3987.16 
		google chrome --> 80.0.3987.132 (64位) 
		下载地址: https://www.chromedownloads.net/chrome64win-stable/978.html
		selenium-java --> 3.141.59

	firefox:
		geckodriver.exe --> v0.21.0
		firefox --> 57.0b8 (64 位) 
		下载地址：http://ftp.mozilla.org/pub/firefox/releases/57.0/win64/zh-CN/
		selenium-java --> 3.141.59

【设置无界面启动】
	
	// chrome 无界面启动（不启动浏览器）
	ChromeOptions options = new ChromeOptions();
	options.setHeadless(true);
	driver = new ChromeDriver(options);

	// firefox无界面启动（不启动浏览器）
	FirefoxOptions options = new FirefoxOptions();
	options.setHeadless(true);
	driver = new FirefoxDriver(options);
		
	
	
	
	






	
	
	
	
	
	
	
	
	
