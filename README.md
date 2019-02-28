# shinyproxy
Default Docker image for containerised ShinyProxy image

##Example application.yml

    proxy:
      landing-page: /
      port: 8080
      specs:
      - id: placeholder
        display-name: Placeholder App
        description: The Docker hello-world app
        container-cmd: ["/usr/bin/shiny-server.sh"]
        container-image: hello-world
