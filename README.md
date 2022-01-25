# 1. 组合模式、命令模式

定义：将一组行为抽象为对像并提供执行、撤销等方法，解决它与调用者的之间的耦合关系。
[示例]('./组合模式、命令模式/index.html')

# 2.策略模式

定义：定义一系列算法，把他们一个个封装起来，并且可以相互替换。</br>
简介：现实生活中当我们要达成一个目的的时候通常会有多种方案可以选择。比如马上年底要发年终奖了，公司针对不同类型的员工有不同的奖金策略，对于表现突出的员工发3个月的工资，一般的员工发2个月的，打酱油的发1个月的，专写Bug的扣一个月。在这里 发年终奖 是目的，针对表现不同的员工我们有多种发奖金的策略，可以使用策略模式来实现。
[示例]('./策略模式.html')

# 3. 代理模式

定义：当直接访问一个对象不方便或者不满足需要时，为其提供一个替身对象来控制对这个对象的访问。<br/>
简介：代理模式是一种非常有意义的模式，在我们日常开发中有许多常用功能都可以通过代理模式实现的，例如 防抖动函数（debounce 常用于控制用户输入后回调函数触发的时机），节流函数（throttle 常用于控制resize、scroll等事件的触发频率）
[示例]('./代理模式.html')

# 4.观察者模式

定义：分离事件创建者和执行者，执行方只需订阅感兴趣的事件发生点。减少对象间的耦合关系，新的订阅者出现时不必修改原有代码逻辑。<br/>
简介：发布订阅模式又叫观察者模式，它定义了对象间一种一对多的关系，当一个对象的状态发生改变时，所有依赖于它的对象都将得到通知。 发布订阅模式在我们日常开发中应用十分广泛，如浏览器的dom事件通知机制(document.addEventListener)，以及vue框架中数据改变时自动刷新dom的双向绑定机制都是基于该模式
[示例]('./发布订阅模式(观察者模式).html')
