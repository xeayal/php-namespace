<a href="https://www.khcoding.com/en/php/what-is-php-namespace-how-to-use-what-is-the-intended-use">➤ # What is PHP Namespace? How to use? What is the intended use?</a>

PHP Namespace is a feature that is used to organize your code and prevent collisions. This feature has been available by default since PHP version 5.3. Namespace allows a class or function to be separated from another class or function in a package.

For more information: <a href="https://www.khcoding.com/en/php/what-is-php-namespace-how-to-use-what-is-the-intended-use">➤ khcoding.com</a>

Creating a namespace is done by using the namespace keyword. The namespace name consists of one or more name parts separated by a backslash (\). For example:
```php
namespace MyProject;

class MyClass {
  // ...
}
```
The example above creates a namespace called MyProject and defines a class called MyClass within this namespace. When you want to use a class within a namespace, you need to specify the namespace name. For example:

```php
$myObj = new MyProject\MyClass();
```
In the example above, an object is created from the MyClass class within the MyProject namespace. The purpose of using a namespace is to better organize your project and prevent naming collisions between classes, functions, and other elements. For example, if different classes in different packages have the same name, namespaces can prevent naming collisions. Below is an example use case:

```php
<?php
namespace MyProject;

class MyClass {
  // ...
}

namespace AnotherProject;

class MyClass {
  // ...
}
```
In the example above, a class named MyClass is defined within the MyProject namespace, and another class with the same name is defined within the AnotherProject namespace. This way, both classes can be used independently of each other. Namespaces help you organize and manage your PHP code better. They prevent naming collisions and make your project more sustainable.
