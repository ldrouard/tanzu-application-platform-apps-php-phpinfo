# Nginx Customization
According to [Nginx Tanzu Buildpack documentation](https://docs.pivotal.io/tanzu-buildpacks/nginx/nginx-buildpack.html), the main nginx configuration will set up during build image.

However, you can put here your extra nginx configuration into :
  * ```.nginx.conf.d/*-server.conf``` : Add parameters for ```server {}``` directive
  * ```.nginx.conf.d/*-http.conf``` : Add parameters for ```http {}``` directive
