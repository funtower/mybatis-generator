## org.mybatis.generator.internal.DefaultCommentGenerator.java  
这个类是为了覆盖jar包里的注释生成类，在xml里指定了不生成注释，但是未生效，于是重写该类的注释生成方法，这样逆向工程生成的代码式不含注释的。