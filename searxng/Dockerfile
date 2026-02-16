FROM docker.io/searxng/searxng:latest

# Bake in custom configuration to disable bot detection limiter
COPY settings.yml /etc/searxng/settings.yml
COPY limiter.toml /etc/searxng/limiter.toml
