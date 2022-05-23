# Spring Boot Basics Practice

Using Spring Boot CLI, do the following:

* Scaffold a new app
* Add a file called `HelloController.java` next to the entry point and put the following code in it:

```java
package com.example.springboot; // This needs to be the actual package name

import org.springframework.web.bind.annotation.GetMapping;
import org.springframework.web.bind.annotation.RestController;

@RestController
public class HelloController {

	@GetMapping("/")
	public String index() {
		return "Hello, world!";
	}

}
```

* Run the app and verify that it prints the string "Hello, world!" when accessed in the browser.
