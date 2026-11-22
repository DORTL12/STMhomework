第一次作业代码提交
work1main.c是第一个任务，使用HAL_GPIO_TogglePin(GPIOA, GPIO_PIN_0);来让外接LED闪烁；
work2main.c是为了实现第二项功能，
使用if判断函数来避免阻塞CPU；
work3main.c是按键控制，
用if ((now - last2) >= 20U)来消抖，
static uint32_t last2 = 0来记录上次触发的时刻.
