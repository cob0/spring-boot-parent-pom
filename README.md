# Spring Boot Parent POM

Spring Boot and JDK 21 based parent POM for Java projects.

## License

![ GNU General Public License v3](https://www.gnu.org/graphics/gplv3-127x51.png)

### What does that mean?

- Anyone can run the software licensed under GPLv3 for any purpose without restrictions.
- GPLv3 ensures that users have access to the software's source code, allowing them to study, modify, and improve it.
- Users can distribute copies of the software, but they must do so under the terms of GPLv3. This ensures that the
  original freedoms are maintained in new versions.
- If someone modifies the software and distributes it, they must do so under the same GPLv3 terms and provide the source
  code for their modifications as well.
- If you are interested in knowing more details about the license, please visit the following links:
    - Spanish: https://www.gnu.org/licenses/gpl-3.0.es.html
    - English: https://www.gnu.org/licenses/gpl-3.0.en.html

## How to run the project

### Dependencies

- **JDK** >= 21 (you can use [JBang](https://www.jbang.dev/documentation/guide/latest/installation.html))
- **Apache Maven** >= 3.9.6 (you can use [Homebrew](https://brew.sh/) or your package manager)

### Install dependencies

```shell
mvn dependency:resolve -U
```

### Install parent POM locally for testing purposes

Run the following command:

```shell
mvn clean -B package --file pom.xml install
```