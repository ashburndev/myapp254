# myapp254
a simple Grails web application created using Grails 2.5.4

## creating the grails 2.5.4 web application

    ashburndave@dphnuc:~/g2projects$ grails --version
    Grails version: 2.5.4
    ashburndave@dphnuc:~/g2projects$ javac -version
    javac 1.8.0_66
    ashburndave@dphnuc:~/g2projects$ java -version
    java version "1.8.0_66"
    Java(TM) SE Runtime Environment (build 1.8.0_66-b17)
    Java HotSpot(TM) 64-Bit Server VM (build 25.66-b17, mixed mode)
    ashburndave@dphnuc:~/g2projects$ 
    ashburndave@dphnuc:~/g2projects$ grails --non-interactive --plain-output --stacktrace -verbose create-app myapp254
    Base Directory: /home/ashburndave/g2projects
    |Loading Grails 2.5.4
    |Configuring classpath
    .
    |Environment set to development
    ......    [mkdir] Created dir: /home/ashburndave/g2projects/myapp254/src
    .    [mkdir] Created dir: /home/ashburndave/g2projects/myapp254/src/java
    .    [mkdir] Created dir: /home/ashburndave/g2projects/myapp254/src/groovy
    .    [mkdir] Created dir: /home/ashburndave/g2projects/myapp254/grails-app
    .    [mkdir] Created dir: /home/ashburndave/g2projects/myapp254/grails-app/controllers
    .    [mkdir] Created dir: /home/ashburndave/g2projects/myapp254/grails-app/services
    .    [mkdir] Created dir: /home/ashburndave/g2projects/myapp254/grails-app/domain
    .    [mkdir] Created dir: /home/ashburndave/g2projects/myapp254/grails-app/taglib
    .    [mkdir] Created dir: /home/ashburndave/g2projects/myapp254/grails-app/utils
    .    [mkdir] Created dir: /home/ashburndave/g2projects/myapp254/grails-app/views
    .    [mkdir] Created dir: /home/ashburndave/g2projects/myapp254/grails-app/views/layouts
    .    [mkdir] Created dir: /home/ashburndave/g2projects/myapp254/grails-app/i18n
    .    [mkdir] Created dir: /home/ashburndave/g2projects/myapp254/grails-app/conf
    .    [mkdir] Created dir: /home/ashburndave/g2projects/myapp254/test
    .    [mkdir] Created dir: /home/ashburndave/g2projects/myapp254/test/unit
    .    [mkdir] Created dir: /home/ashburndave/g2projects/myapp254/test/integration
    .    [mkdir] Created dir: /home/ashburndave/g2projects/myapp254/scripts
    .    [mkdir] Created dir: /home/ashburndave/g2projects/myapp254/web-app
    .    [mkdir] Created dir: /home/ashburndave/g2projects/myapp254/web-app/js
    .    [mkdir] Created dir: /home/ashburndave/g2projects/myapp254/web-app/css
    .    [mkdir] Created dir: /home/ashburndave/g2projects/myapp254/web-app/images
    .    [mkdir] Created dir: /home/ashburndave/g2projects/myapp254/web-app/META-INF
    .    [mkdir] Created dir: /home/ashburndave/g2projects/myapp254/lib
    .    [mkdir] Created dir: /home/ashburndave/g2projects/myapp254/grails-app/conf/spring
    .    [mkdir] Created dir: /home/ashburndave/g2projects/myapp254/grails-app/conf/hibernate
    ..     [copy] Copying 1 resource to /home/ashburndave/g2projects/myapp254
    .    [unjar] Expanding: /home/ashburndave/g2projects/myapp254/grails-shared-files.jar into /home/ashburndave/g2projects/myapp254
    .   [delete] Deleting: /home/ashburndave/g2projects/myapp254/grails-shared-files.jar
    .     [copy] Copying 1 resource to /home/ashburndave/g2projects/myapp254
    .    [unjar] Expanding: /home/ashburndave/g2projects/myapp254/grails-app-files.jar into /home/ashburndave/g2projects/myapp254
    .   [delete] Deleting: /home/ashburndave/g2projects/myapp254/grails-app-files.jar
    .     [copy] Copying 2 files to /home/ashburndave/g2projects/myapp254
    ..
    |Created Eclipse project files.
    .
    |Generating Wrapper
         [copy] Copying 1 resource to /home/ashburndave/g2projects/myapp254/wrapper
    .    [unjar] Expanding: /home/ashburndave/g2projects/myapp254/wrapper/grails-wrapper-support.jar into /home/ashburndave/g2projects/myapp254/wrapper
    .   [delete] Deleting: /home/ashburndave/g2projects/myapp254/wrapper/grails-wrapper-support.jar
    .     [move] Moving 2 files to /home/ashburndave/g2projects/myapp254
    ....
    |Wrapper installed successfully
    |Created Grails Application at /home/ashburndave/g2projects/myapp254
    ashburndave@dphnuc:~/g2projects$ 
    ashburndave@dphnuc:~/g2projects$ tree myapp254/
    myapp254/
    ├── application.properties
    ├── grails-app
    │   ├── assets
    │   │   ├── images
    │   │   │   ├── apple-touch-icon.png
    │   │   │   ├── apple-touch-icon-retina.png
    │   │   │   ├── favicon.ico
    │   │   │   ├── grails_logo.png
    │   │   │   ├── skin
    │   │   │   │   ├── database_add.png
    │   │   │   │   ├── database_delete.png
    │   │   │   │   ├── database_edit.png
    │   │   │   │   ├── database_save.png
    │   │   │   │   ├── database_table.png
    │   │   │   │   ├── exclamation.png
    │   │   │   │   ├── house.png
    │   │   │   │   ├── information.png
    │   │   │   │   ├── shadow.jpg
    │   │   │   │   ├── sorted_asc.gif
    │   │   │   │   └── sorted_desc.gif
    │   │   │   ├── spinner.gif
    │   │   │   └── springsource.png
    │   │   ├── javascripts
    │   │   │   └── application.js
    │   │   └── stylesheets
    │   │       ├── application.css
    │   │       ├── errors.css
    │   │       ├── main.css
    │   │       └── mobile.css
    │   ├── conf
    │   │   ├── BootStrap.groovy
    │   │   ├── BuildConfig.groovy
    │   │   ├── Config.groovy
    │   │   ├── DataSource.groovy
    │   │   ├── hibernate
    │   │   ├── spring
    │   │   │   └── resources.groovy
    │   │   └── UrlMappings.groovy
    │   ├── controllers
    │   ├── domain
    │   ├── i18n
    │   │   ├── messages_cs_CZ.properties
    │   │   ├── messages_da.properties
    │   │   ├── messages_de.properties
    │   │   ├── messages_es.properties
    │   │   ├── messages_fr.properties
    │   │   ├── messages_it.properties
    │   │   ├── messages_ja.properties
    │   │   ├── messages_nb.properties
    │   │   ├── messages_nl.properties
    │   │   ├── messages_pl.properties
    │   │   ├── messages.properties
    │   │   ├── messages_pt_BR.properties
    │   │   ├── messages_pt_PT.properties
    │   │   ├── messages_ru.properties
    │   │   ├── messages_sv.properties
    │   │   ├── messages_th.properties
    │   │   └── messages_zh_CN.properties
    │   ├── services
    │   ├── taglib
    │   ├── utils
    │   └── views
    │       ├── error.gsp
    │       ├── index.gsp
    │       └── layouts
    │           └── main.gsp
    ├── grailsw
    ├── grailsw.bat
    ├── lib
    ├── scripts
    ├── src
    │   ├── groovy
    │   └── java
    ├── test
    │   ├── integration
    │   └── unit
    ├── web-app
    │   ├── css
    │   ├── images
    │   ├── js
    │   ├── META-INF
    │   └── WEB-INF
    │       ├── applicationContext.xml
    │       ├── sitemesh.xml
    │       └── tld
    │           ├── grails.tld
    │           ├── spring-form.tld
    │           └── spring.tld
    └── wrapper
        ├── grails-wrapper.properties
        ├── grails-wrapper-runtime-2.5.4.jar
        └── springloaded-1.2.4.RELEASE.jar
    
    33 directories, 59 files
    ashburndave@dphnuc:~/g2projects$ 

