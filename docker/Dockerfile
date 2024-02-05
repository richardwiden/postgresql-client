ARG BASE_IMAGE=alpine:3.12
FROM ${BASE_IMAGE}
ARG POSTGRES_VERSION="" #3.12 calls client postgresclient not postgreclient12
RUN apk --no-cache add postgresql${POSTGRES_VERSION}-client
ENTRYPOINT [ "psql" ]