# This file is generated by Nx.
#
# Build the docker image with `npx nx docker-build auth_service`.
# Tip: Modify "docker-build" options in project.json to change docker build args.
#
# Run the container with `docker run -p 3000:3000 -t auth_service`.
FROM docker.io/node:lts-alpine

ENV HOST=0.0.0.0
ENV PORT=3000

WORKDIR /app

RUN addgroup --system auth_service && \
          adduser --system -G auth_service auth_service

COPY dist/apps/auth_service auth_service/
RUN chown -R auth_service:auth_service .

# You can remove this install step if you build with `--bundle` option.
# The bundled output will include external dependencies.
RUN npm --prefix auth_service --omit=dev -f install

CMD [ "node", "auth_service" ]
