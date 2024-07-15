The Web Servers Initializ Buildpack provides a set of collaborating buildpacks that
enable the use of web servers. These buildpacks include:
- [NGINX CNB](https://github.com/initializ-buildpacks/nginx)
- [Apache HTTPD CNB](https://github.com/initializ-buildpacks/httpd)
- [Node Engine CNB](https://github.com/initializ-buildpacks/node-engine)
- [Yarn CNB](https://github.com/initializ-buildpacks/yarn)
- [Yarn Install CNB](https://github.com/initializ-buildpacks/yarn-install)
- [NPM Install CNB](https://github.com/initializ-buildpacks/npm-install)

The buildpack supports building applications that leverage NGINX or HTTPD web
servers as well as JavaScript Frontend apps. Usage examples can be found in the
[`samples`
repository](https://github.com/initializ-buildpacks/samples) under
the [`web-servers`
directory](https://github.com/initializ-buildpacks/samples/tree/main/web-servers).

This buildpack also includes the following utility buildpacks:
- [Procfile CNB](https://github.com/initializ-buildpacks/procfile)
- [Environment Variables CNB](https://github.com/initializ-buildpacks/environment-variables)
- [Image Labels CNB](https://github.com/initializ-buildpacks/image-labels)
- [CA Certificates CNB](https://github.com/initializ-buildpacks/ca-certificates)
- [Node Run Script CNB](https://github.com/initializ-buildpacks/node-run-script)
- [Source Removal CNB](https://github.com/initializ-buildpacks/source-removal)

Check out the [Web Servers initializ Buildpack docs](https://initializ.io/docs/howto/web-servers/) for more information.
