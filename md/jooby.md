# &infin; do more, more easily

Introducing [Jooby](http://jooby.org) a minimalist web framework for Java 8 or higher.

* **Solid**. build on top of mature technologies.

* **Scalable**. Stateless application development.

* **Fast, modular and extensible**. It is so extensible that even the web server is plugable.

* **Simple, effective and easy to learn**. Ideal for small but also large scale applications.

* **Ready for modern web**. That require a lot of JavaScript/HTML/CSS

## hello world!

```java
import org.jooby.Jooby;

public class App extends Jooby {

  {
    get("/", () -> "Hey Jooby!");
  }

  public static void main(final String[] args) throws Exception {
    new App().start(args);
  }
}

```