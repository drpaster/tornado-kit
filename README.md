# tornado-kit
The structure of the Tornado based application with the necessary set of scripts for work in production.

Makes it easy to build flexible scaling and high loads production apps.

Additional features:
- A convenient directory structure;
- Management through configuration files;
- Session support;
- Multithreading support;
- PostgreSQL support based on Momoko (multithread pool);
- Redis support based on RedIce, redis-py and tornadis;
- Basic DDoS protection;
- Support for loading Lua scripts for Redis;
- Support for smooth shutdown with waiting for current requests;
- Based on Fabric production ready deployment scripts;
- Based on Bash production/development/test run scripts;
- Migrate-like Recording DB structure changes for Postgres/Redis;
- Multiservers support for static files.
