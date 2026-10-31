# Shaarli LazyCat community package

Source https://github.com/shaarli/Shaarli,v0.16.10. Official candidate com.liaobinbin.shaarli. Package community.lazycat.app.shaarli,minOS1.5.0,amd64 mirror mode, community store only. Core license Zlib; asset/vendor notices retain their own terms as listed in bundled COPYING.txt. Intended category Productivity/Bookmarks121.

Single PHP/nginx container, no external database. First native setup is MANUAL; use deployment credentials and finish before sharing access. Params do not create/reset native accounts. Root path matching accommodates query routing, but selectors are restricted to form[name=loginform], not arbitrary inputs or settings forms. Autofill does not submit. Platform auth stays enabled; anonymous sharing/RSS/API still require entry authentication. Only grant shared fill to trusted members.

Persist data and cache separately. Setup only mkdir/chowns those directories to the original nginx account so host binds are writable; native S6/PHP-FPM identity and entrypoint retained. Back up data before uninstalling. No smoke, extra healthcheck, startup test gate or file interception.

Original core/asset notices are served at /package-licenses/COPYING.txt. Icon is only resized for packaging, app image code unchanged. Build and independent package/config/license/SHA256 checks run on GitHub, no local source/image/LPK download. Startup, setup, login fill, bookmark CRUD, import/export, sharing and persistence remain unverified on a device.
