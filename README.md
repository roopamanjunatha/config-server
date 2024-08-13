# config-server
Config Server to externalize configurations for spring boot microservices.

Please note the below points when creating a configuration file in the GitHub repo.

{application} which maps to spring.application.name in your config client
{profile} which maps to spring.profiles.active on the client
{label} which is a server side feature labeling a “versioned” set of config files

Below are the ways to access the configurations from the config server.

/{application}/{profile}[/{label}]
/{application}-{profile}.yml
/{label}/{application}-{profile}.yml
/{application}-{profile}.properties
/{label}/{application}-{profile}.properties
