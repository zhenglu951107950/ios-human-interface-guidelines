# 社交媒体 (Social Media)

人们希望可以在任何情况下都能使用他们的社交媒体。ios 会使用人们喜欢的方式将社交软件融合到你的 app 里。

![](images/social_media_sharing_2x.png)

> **提示**
> 
> 当用户点击动作按钮，他们会得到一个类似上图中的视图控制器。想了解更多关于视图控制器，请点击[Activity View Controller](https://developer.apple.com/library/ios/documentation/UserExperience/Conceptual/MobileHIG/ContentViews.html#//apple_ref/doc/uid/TP40006556-CH13-SW121)
> 活动视图控制器中间的那行列出了可以让用户分享的 app ，这是有系统提供的分享服务。想了解更多关于分享应用，请点击[Share and Action Extensions](https://developer.apple.com/library/ios/documentation/UserExperience/Conceptual/MobileHIG/AppExtensions.html#//apple_ref/doc/uid/TP40006556-CH67-SW3)

**考虑给你的用户提供一种方便的方式来撰写分享。**用户可能会使用分享扩展功能以便能随意分享内容，但是你也可以使用系统提供的视图控制器，让用户在其中进行编辑操作。你可以在显示给用户编辑之前，预先加载具有自定义内容的撰写试图（在你呈现给用户之后，只有用户可以编辑这些自定义内容）。想了解更多关于社交框架，包括[SLComposeViewController](https://developer.apple.com/library/ios/documentation/NetworkingInternet/Reference/SLComposeViewController_Class/index.html#//apple_ref/occ/cl/SLComposeViewController)类，请点击[Social Framework Reference](https://developer.apple.com/library/ios/documentation/Social/Reference/Social_Framework/index.html#//apple_ref/doc/uid/TP40012233)

**尽量不要让用户登录社交账户。**社交框架会和账号框架一起来支持单点登录，所以你可以获得授权来访问用户的账号，而无需要求他们重新登录。如果用户还没有登录，你可以显示登录界面让他们进行登录。