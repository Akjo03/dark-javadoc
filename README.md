![GitHub release (latest by date including pre-releases)](https://img.shields.io/github/downloads-pre/Akjo03/dark-javadoc/latest/total?label=Downloads&style=flat-square)
![GitHub](https://img.shields.io/github/license/Akjo03/dark-javadoc?label=License&style=flat-square)
![CodeFactor Grade](https://img.shields.io/codefactor/grade/github/Akjo03/dark-javadoc?label=Code%20Quality&style=flat-square)
![Lines of code](https://img.shields.io/tokei/lines/github/Akjo03/dark-javadoc?label=Lines%20Of%20Code&style=flat-square)

# AkjoNav

An open-source, fully functional and intelligent navigation system made in Java.

## How to install into your java project

*Prerequisites: Maven Project & IntelliJ IDEA*

### 1. Add plugin to pom.xml

Head into your pom.xml and add the contents of [plugin.xml](plugin.xml) to the \<plugins\> tag.

### 2. Reload Maven Project

Reload the Maven project by opening the Maven tab on the right side and clicking on "Reload All Maven Projects" at the top.

### 3. Copying the stylesheet

Copy the [javadoc-stylesheet.css](javadoc-stylesheet.css) into `src/main/javadoc/javadoc-stylesheet.css` inside of your project.

### 4. Generate the JavaDoc with Maven

Under the Maven tab on the right side, go under "Plugins", "javadoc" and double-click on "javadoc:javadoc"

This will generate the new JavaDoc under `doc/`. You can view the javadoc by right-clicking `doc/index.html` inside of IntelliJ, then under "Open In" go under Browser and choose your preferred browser.

### 5. *Optional*: Exclude doc folder

Right-click on the `doc/` folder inside IntelliJ and under "Mark directory as", choose "Excluded".


------

## Built With

* [Java 17 (Eclipse Temurin)](https://adoptium.net/?variant=openjdk17&jvmVariant=hotspot)
* [Maven 3.6.3 (Bundled - IntelliJ)](https://maven.apache.org/)
* [Git 2.33.1.windows.1](https://git-scm.com/)
* [Windows 10 21H1 (19043.1288)](https://docs.microsoft.com/en-us/windows/release-health/status-windows-10-21h1)
* [IntelliJ IDEA 2021.2.3](https://www.jetbrains.com/de-de/idea/)

## License

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE](LICENSE) file for details

## Authors

* **Lukas Freckmann** - *Initial work* - [Akjo03](https://github.com/Akjo03)

See also the list of [contributors](https://github.com/Akjo03/PROJECT_NAME/contributors) who participated in this project.