# jdev

Mirror repository of a collection of maven modules for assistance in java SDLC.

## Modules :

| module name    | module purpose                                                                                 |
|----------------|------------------------------------------------------------------------------------------------|
| jdev-test      | maven module with several testing dependencies for SDLC.                                       |
| jdev-jackson   | java helper & util classes combined with jackson for for SDLC.                                 |
| jdev-primitive | java helper & util classes around java primitives (IntUtils, ByteArrayBuilder...etc) for SDLC. |

## How to use it ?

This is not pushed to Maven central... yet. But still you can use it
via [jitpack.io](https://jitpack.io/docs/).

Add the jitpack repository to your maven repositories:

 ```
<repositories>
    ...
    <repository>
        <id>JitPack</id>
        <url>https://jitpack.io</url>
    </repository>
    ...
</repositories>
 ```

Then, add the following to your pom.xml (use any version
from [gitHub releases page](https://github.com/gentjankolicaj/jdev/releases)):

 ```
<dependency>
    <groupId>com.github.gentjankolicaj</groupId>
    <artifactId>jdev-${MODULE_NAME}</artifactId>
    <version>main-SNAPSHOT</version>
</dependency>
 ```