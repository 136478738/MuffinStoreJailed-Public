# MuffinStore Jailed

Hacked together on-device App Store client, view it more-so as a PoC than as a final tool.
在设备App Store客户端上一起被黑客攻击，将其视为PoC而非最终工具。

Publicizing because it could be useful for some people, however please use TrollStore MuffinStore over this if you can. This is not meant to be a final product, but it can be helpful for some people.
宣传，因为它可能对某些人有用，但如果可以的话，请使用TrollStore MuffinStore。这不是最终产品，但对某些人来说可能会有所帮助。

The UI is a bit scuffed, there's no progress bar during downgrading so just wait on the screen until you get a popup that requests installation ( the time this takes depends on how big the app is, so please wait. ), and then after you press install wait like ~5 more seconds and then you can return to SpringBoard to see the app downgrade being finalized.
用户界面有点磨损，降级过程中没有进度条，所以只需在屏幕上等待，直到你收到一个请求安装的弹出窗口（所需的时间取决于应用程序的大小，所以请等待。），然后在你按下安装键后，再等约5秒，然后你可以返回SpringBoard查看应用程序降级的最终结果。

I am not responsible for any issues caused by the usage of this tool, it's experimental and I will not be held accountable if anything happens. Use at your own risk. Although nothing should happen, just putting this here just in case.
我不对使用此工具造成的任何问题负责，它是实验性的，如果发生任何事情，我将不承担任何责任。使用风险自负。虽然什么都不应该发生，但把它放在这里以防万一。

The app you want to downgrade will need to be uninstalled, however, you can preserve app data by offloading the app first, and then downgrading it.
您要降级的应用程序需要卸载，但是，您可以通过先卸载应用程序，然后再降级来保留应用程序数据。

You should request a 2fa code BEFORE logging in, via the Settings app, however, if the settings app doesn't show the option ( iOS 18+ ), you can leave the code field empty, and then you should get a popup, accept it, and copy the code from there. If it doesn't log you in fully close and re-open the app and try again.
您应该在登录之前通过设置应用程序请求2fa代码，但是，如果设置应用程序没有显示选项（iOS 18+），您可以将代码字段留空，然后您应该得到一个弹出窗口，接受它，并从那里复制代码。如果它没有让你完全登录，请关闭并重新打开应用程序，然后重试。
