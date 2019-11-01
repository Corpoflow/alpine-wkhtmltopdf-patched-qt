# wkhtmltopdf alpine binary

Version 0.12.5 with patched qt


Needs these dependencies:

```
RUN apk add \
    libgcc \
    libstdc++ \
    libx11 \
    glib \
    libxrender \
    libxext \
    libintl \
    ttf-dejavu \
    ttf-droid \
    ttf-freefont \
    ttf-liberation \
    ttf-ubuntu-font-family
```
