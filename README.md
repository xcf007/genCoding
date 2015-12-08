# genCoding
前端有emmet(aka zenCoding),后端咱可以有genCoding;emmet基于selector,那么genCoding基于all qualifier class name!!!

# 修饰符
1.) + public
2.) - private
3.) # protected



1.新建类cn.xcf007.test.HelloWorld [默认即public 类]
命令：cn.xcf007.test.HelloWorld
等同 +cn.xcf007.test.HelloWorld
新增(add)一个public类
直接回车确认，即new一个新的class
2.新建一个HelloWorld的私有方法
命令：-cn.xcf007.test.HelloWorld..printHello():void
生成：
package cn.xcf007.test;
public class HelloWorld{
  private void printHello(){
   //TODO...
  }
}

再来一个：
+cn.xcf007.test.HelloWorld..query(sql:String):List<Map<String, Object>>

package cn.xcf007.test;
public class HelloWorld{
  public List<Map<String, Object>> query(String sql){
   //TODO...
  }
}


3.光标跳转到指定的方法
