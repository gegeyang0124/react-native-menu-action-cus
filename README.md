# react-native-menu-action-cus
自定义弹出菜单（或页面）组件；
本组件是基于[react-native-custom-action-sheet](https://github.com/eyaleizenberg/react-native-custom-action-sheet)
进行修改和升级的

###  安装组件：
npm i --save react-native-lib-cus-com

<p align="center">
    <img src ="http://i.imgur.com/Iq6YZGj.gif" />
</p>


### 示例
```javascript
import CustomActionSheet from "react-native-menu-action-cus";

var SomeComponent = React.createClass({
  render: function() {
    return (
      <View>
        <CustomActionSheet modalVisible={this.state.modalVisible} onCancel={this.toggleModal}>
          <View style={styles.datePickerContainer}>
            <DatePickerIOS mode={"date"} date={@state.dateForPicker} onDateChange={@dateChanged} />
          </View>
        </CustomActionSheet>
      </View>
    );
  }
});
```

### 公共属性
- `modalVisible` (Boolean) - 控制组件是否可见
- `onCancel` (Function) - 取消回调函数
- `buttonText` (String) - 按钮显示文本
- `backgroundColor` (String) - 背景色.

### 欢迎交流
欢迎提问交流；若有bug，请添加bug截图或代码片段，以便更快更好的解决问题。<br>
欢迎大家一起交流

### [我的博客](http://blog.sina.com.cn/s/articlelist_6078695441_0_1.html)
