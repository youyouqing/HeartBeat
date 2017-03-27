# HeartBeat
手机检测心率血压
 //创建了一个心电图的View
 self.live = [[HeartLive alloc]initWithFrame:CGRectMake(10, 100, self.view.frame.size.width-20, 150)];
 [self.view addSubview:self.live];
 
 - (void)startHeartDelegateRatePoint:(NSDictionary *)point {
    NSNumber *n = [[point allValues] firstObject];
    //拿到的数据传给心电图View
    [self.live drawRateWithPoint:n];
 }
 */
