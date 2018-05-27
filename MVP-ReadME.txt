MVP: model view Presenter(controller)

1. presenter将modle,view注入里面
2. 提供了实现方法供activity调用
3.在方法里面将数据给了model。构建一个方法调用view的方法，从此将model的数据传到view接口中。
4. 让activity实现View接口，并调用其方法。
5.>在activity里用成员变量presenter实现整个方法调用。


好处: 解耦。activity里的代码量大大减少。
作用: 将数据从 presenter -> model -> view -> activity
环境: ??