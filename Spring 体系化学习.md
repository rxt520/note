# Spring 体系化学习

## SpringBean 的生命流程

1. beanDefinition bean 的解释器 存储着Bean的信息
2. beanFactoryPostProcessor
3. 实例化 通过反射生成带有默认值的bean
4. 初始化
   1. 属性注入
   2. Aware 接口
   3. BeanPostProcessor 前置处理
   4. init-method
   5. BeanPostProcessor 后置处理
   6. 完整Bean
5. 销毁



