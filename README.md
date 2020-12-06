# Oathtool with Docker

1. Build an image with docker-compose.

```sh
docker-compose build
```

2. Pipe an otp secret to it.

```sh
echo "$OTP_SECRET" | docker run --rm -i oathtool:2.6.2-alpine
```
