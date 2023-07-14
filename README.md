# AXUM WASIX STARTER

This repo contains a starter project for building a **Wasix** based axum web server.

## Deploy to Wasmer Edge

1. Login to `wasmer-cli`

```bash
$ wasmer login
```

2. Replace `wasix-org` username in `wasmer.toml` and `deploy.toml` with your username
   > Note: `wasmer.toml` is for publishing the image to **wasmer registry** and `deploy.toml` is for deploying the image to **wasmer-edge**
3. Deploy to `wasmer-edge`

```bash
$ wasmer deploy
```

Checkout the full tutorial [here](http://wasix.org/docs/language-guide/rust/tutorials/wasix-axum)
