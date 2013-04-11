swt-maven
=========
This respostiroty intend to host eclipse package into a maven repository since Eclipse it self doesn't host a maven repository with the latest version of the pacakge. Reference.: https://code.google.com/p/swt-maven/

<repositories>
    ...
    <repository>
        <id>swt repo</id>
        <url>https://raw.github.com/ikus060/swt-maven/master/</url>
    </repository>
</repositories>
<dependencies>
    ...
    <dependency>
        <groupId>org.eclipse.swt</groupId>
        <artifactId>org.eclipse.swt.win32.win32.x86_64</artifactId>
        <version>4.2.1</version>
    </dependency>
</dependencies>
