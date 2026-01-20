# Planning

- [x] Protocol spec
- [ ] Python client & server
- [ ] C client & server

## C client and server project structure
```
client
- client.c (entrypoint)
- networking.c (networking stuff)
- crypto.c (kex, negotiations, challenges, etc)

server
- server.c (entrypoint)
- registries.c (works with SQL db)
- networking.c (networking stuff)
- routing.c (handles message routing)
- crypto.c (kex, negotiations, challenges, etc)
```
