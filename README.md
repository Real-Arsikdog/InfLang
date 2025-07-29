# InfLang

A modern programming language combining the best of Python and Java.

InfLang is a new programming language designed to offer the simplicity and readability of Python, combined with the robust performance and structured nature of Java. It aims to provide a familiar yet unique experience for developers, making it easy to learn for beginners while being powerful enough for complex applications.



## Features

- **Simple, Python-like Syntax**: Enjoy clean and readable code that's easy to pick up.
- **Java-like Performance**: Built on Java, InfLang leverages its performance and ecosystem.
- **Unique `pin` Statement**: Say goodbye to `print` and embrace `pin` for all your output needs.
- **Strong Typing**: Benefit from the type safety and reliability inherited from Java.
- **Easy to Learn**: Designed with a gentle learning curve for new programmers.
- **Open-Source & Community-Driven**: Join a growing community and contribute to the language's evolution.



## Getting Started

To get started with InfLang, you'll need to have the Java Development Kit (JDK) installed on your system (version 17 or higher).

### Prerequisites
- [Java Development Kit (JDK) 17+](https://www.oracle.com/java/technologies/downloads/)

### Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/InfLang.git
   cd InfLang
   ```

2. **Compile the source code:**
   ```bash
   javac src/main/java/inftlang/*.java -d out
   ```

### Running InfLang Scripts
To run an InfLang script, use the following command:

```bash
java -cp out inftlang.InfLang <your_script_name>.inft
```

**Example:**
```bash
java -cp out inftlang.InfLang hello.inft
```



## Usage Examples

### Hello World

Create a file named `hello.inft`:

```inftlang
pin "Hello, InfLang!";
```

Run it:

```bash
java -cp out inftlang.InfLang hello.inft
```

Output:

```
Hello, InfLang!
```

### Variables, Control Flow, and Functions

Create a file named `test.inft`:

```inftlang
var x = 10;
var y = 20;
pin "x + y = " + (x + y);

if (x < y) {
    pin "x is less than y";
} else {
    pin "x is not less than y";
}

var count = 0;
while (count < 3) {
    pin "Count: " + count;
    count = count + 1;
}

func greet(name) {
    pin "Hello, " + name + "!";
}

greet("World");

func add(a, b) {
    return a + b;
}

var result = add(5, 7);
pin "5 + 7 = " + result;
```

Run it:

```bash
java -cp out inftlang.InfLang test.inft
```

Output:

```
x + y = 30
x is less than y
Count: 0
Count: 1
Count: 2
Hello, World!
5 + 7 = 12
```



## Language Specification

For a detailed understanding of InfLang syntax, grammar, and core features, please refer to the [InfLang Language Specification](inftlang_spec.md).

## Contributing

We welcome contributions to InfLang! If you're interested in improving the language, fixing bugs, or adding new features, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature-name`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add new feature'`).
5. Push to the branch (`git push origin feature/your-feature-name`).
6. Open a Pull Request.

Please ensure your code adheres to our coding standards and includes appropriate tests.

## Community

Join our growing community of InfLang developers!

- **Discord:** [https://discord.gg/bQN5wJQfTs](https://discord.gg/bQN5wJQfTs)
- **Official Website:** [https://txzolrtd.manus.space](https://txzolrtd.manus.space)

## License

InfLang is released under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For general inquiries or support, please open an issue on our GitHub repository.
