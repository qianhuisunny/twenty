FROM twentycrm/twenty:v2.51.0

ENTRYPOINT ["/bin/sh", "-c", "export SERVER_URL=${RENDER_EXTERNAL_URL:?}; exec /app/entrypoint.sh node dist/main"]
