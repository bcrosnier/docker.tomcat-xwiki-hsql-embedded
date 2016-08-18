# XWiki with embedded HSQL database

Default XWiki configuration, using an embedded file-based HSQL database.

Used for fast and painless setups of XWiki.

## [View Dockerfile](https://github.com/bcrosnier/docker.tomcat-xwiki-hsql-embedded/blob/master/Dockerfile)

**This image uses an embedded file-based database.**
**Don't use this on an environment where your database should be separate.**

# Usage

1. Run this image
   - Single-use run example: `docker run -p 8080:8080 bcrosnier/tomcat-xwiki-hsql-embedded`
2. Head on to your configured port, eg. `http://localhost:8080/`
3. Use XWiki's configuration assistant to create an Administrator account

## Exposed ports

- `8080`: Tomcat port (from `tomcat`)