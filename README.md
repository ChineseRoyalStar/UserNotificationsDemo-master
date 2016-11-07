#UserNotificationsDemo
//申请通知权限 <br />
`- (BOOL)application:(UIApplication *)application didFinishLaunchingWithOptions:(NSDictionary *)launchOptions` <br /> <br />
//获取deviceToken  <br />
`- (void)application:(UIApplication *)application didRegisterForRemoteNotificationsWithDeviceToken:(NSData *)deviceToken` <br /> <br />
//获取deviceToken失败 <br />
`- (void)application:(UIApplication *)application didFailToRegisterForRemoteNotificationsWithError:(NSError *)error` <br /> <br />
