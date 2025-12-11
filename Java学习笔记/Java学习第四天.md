##### Java学习第四天

###### 



###### String对象和其他包装类之间的转换，以及包装类和基本类型的转换

基本类型和他们的包装类可以自动转换例如 Float ff = 123.33f;

String对象与其他包装类之间做转换：

//String -> Float 

Float ff = Float.parseValue( new String("123.4f") );

//Float -> String 

String str = String.valueOf(new Float(12.3f));



