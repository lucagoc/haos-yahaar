ARG BUILD_FROM=ghcr.io/home-assistant/amd64-base:latest
FROM ghcr.io/thephaseless/byparr:1.2.1

# Add entrypoint script
COPY run.sh /run.sh
RUN chmod +x /run.sh

CMD [ "/run.sh" ]
