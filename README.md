#UserNotificationsDemo
//申请通知权限 <br />
`- (BOOL)application:(UIApplication *)application didFinishLaunchingWithOptions:(NSDictionary *)launchOptions` <br /> <br />
//获取deviceToken  <br />
`- (void)application:(UIApplication *)application didRegisterForRemoteNotificationsWithDeviceToken:(NSData *)deviceToken` <br /> <br />
//获取deviceToken失败 <br />
`- (void)application:(UIApplication *)application didFailToRegisterForRemoteNotificationsWithError:(NSError *)error` <br /> <br />
//iOS10 收到通知（本地和远端） UNUserNotificationCenterDelegate<br />
//App处于前台接收通知时<br />
`- (void)userNotificationCenter:(UNUserNotificationCenter *)center willPresentNotification:(UNNotification *)notification withCompletionHandler:(void (^)(UNNotificationPresentationOptions))completionHandler`<br /> <br />
//App通知的点击事件<br />
` (void)userNotificationCenter:(UNUserNotificationCenter *)center didReceiveNotificationResponse:(UNNotificationResponse *)response withCompletionHandler:(void (^)())completionHandler`<br /><br />
//iOS 10之前收到通知<br />
`- (void)application:(UIApplication *)application didReceiveRemoteNotification:(NSDictionary *)userInfo` <br /> <br />
`-(void)application:(UIApplication *)application didReceiveRemoteNotification:(NSDictionary *)userInfo fetchCompletionHandler:(void (^)(UIBackgroundFetchResult))completionHandler`
