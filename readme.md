# Setting up Xdebug for cli. PhpStorm & Intellij IDEA

* Check XDebug remote port [File -> Settings - >Language & Frameworks -> PHP -> Debug]

[![settings](./img/settings.jpg)](./img/settings.jpg)

If you change port number, change it in settings

* Configure remote XDebug server. Open configurations [ Run -> Edit Configurations...]

[![settings xebug](./img/set-up-tool.png)](./img/set-up-tool.png)

* Press '+' for add new configuration

* Enable "Filter debug connection by IDE Key"

[![settings xebug](./img/add-xdebug.png)](./img/add-xdebug.png)

* Use PHP Remote Debug for new configuration

[![settings xebug](./img/server-config.png)](./img/server-config.png)

* Add server configuration. Press "..." for 'Server'
* Enter name
* Host: localhost
* Port: 80
* Use path mapping for directory in container: Your local directory add to mapping with container directory structure

[![settings xebug](./img/final-config.png)](./img/final-config.png)

* Apply changes
* Add IDE key: PHPSTORM or your IDE key

[![settings xebug](./img/final-config-ide-key.png)](./img/final-config-ide-key.png)

# Setting up Xdebug for web. PhpStorm & Intellij IDEA

See Setting up for cli.

Result:

[![web xdebug work](./img/web-xdebug.jpg)](./img/web-xdebug.jpg)

## Links

[See off documentation for more details](https://www.jetbrains.com/help/phpstorm/configuring-xdebug.html)
[See off documentation for more details for docker](https://confluence.jetbrains.com/display/PhpStorm/Docker+Support+in+PhpStorm#DockerSupportinPhpStorm-DebuggingthePHPwebapplicationrunningintheDockercontainer)
