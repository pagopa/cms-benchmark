# CMS Benchmark

This repository provide a simple way to start and try some CMS.

## Strapi

To start strapi execute the following command, and wait until the process is complete (it could takes several minutes).

``` sh
docker-compose -f strapi/docker-compose.yml up
```

The final output should something like the following:

```
strapi_1  | yarn install v1.22.19
strapi_1  | [1/5] Validating package.json...
strapi_1  | [2/5] Resolving packages...
strapi_1  | success Already up-to-date.
strapi_1  | Done in 1.18s.
strapi_1  | yarn run v1.22.19
strapi_1  | $ strapi develop
strapi_1  | Starting the compilation for TypeScript files in /home/node/app
strapi_1  | Building your admin UI with development configuration...
strapi_1  | Admin UI built successfully
strapi_1  | 
strapi_1  |  Project information
strapi_1  | 
strapi_1  | ┌────────────────────┬──────────────────────────────────────────────────┐
strapi_1  | │ Time               │ Mon Feb 06 2023 16:37:56 GMT+0000 (Coordinated … │
strapi_1  | │ Launched in        │ 3142 ms                                          │
strapi_1  | │ Environment        │ development                                      │
strapi_1  | │ Process PID        │ 64                                               │
strapi_1  | │ Version            │ 4.6.0 (node v18.14.0)                            │
strapi_1  | │ Edition            │ Community                                        │
strapi_1  | │ Database           │ postgres                                         │
strapi_1  | └────────────────────┴──────────────────────────────────────────────────┘
strapi_1  | 
strapi_1  |  Actions available
strapi_1  | 
strapi_1  | One more thing...
strapi_1  | Create your first administrator 💻 by going to the administration panel at:
strapi_1  | 
strapi_1  | ┌─────────────────────────────┐
strapi_1  | │ http://localhost:1337/admin │
strapi_1  | └─────────────────────────────┘
```

Access to the admin area visiting `http://localhost:1337/admin`.

## PayloadCMS

To start payloadCMS execute the following command, and wait until the process is complete (it could takes several minutes).

``` sh
docker-compose -f payloadcms/docker-compose.yml up
```

The final output should something like the following:

```
payload_1  | [nodemon] watching path(s): *.*
payload_1  | [nodemon] watching extensions: ts
payload_1  | [nodemon] starting `ts-node src/server.ts`
payload_1  | [13:47:44] INFO (payload): Connected to Mongo server successfully!
payload_1  | [13:47:44] INFO (payload): Starting Payload...
payload_1  | [13:47:45] INFO (payload): Payload Admin URL: http://localhost:3000/admin
payload_1  | webpack built 231f049e2ef57913d34b in 2894ms
payload_1  | webpack compiled successfully
```

Access to the admin area visiting `http://localhost:3000/admin`.
