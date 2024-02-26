FROM cgr.dev/chainguard/wolfi-base

WORKDIR /app

RUN chown -R nonroot.nonroot /app/

USER nonroot

COPY hello.sh /app/
ENTRYPOINT [ "./hello.sh" ]