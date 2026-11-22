work1是为了实现功能一，LED灯的开关，
用haldelay来实现功能；
work2是为了实现功能二，
用if循环来防止CPU过载；
work3是功能3，开关的控制，
static uint32_t last2 = 0记录上次，
if ((now - last2) >= 20U)消抖.
