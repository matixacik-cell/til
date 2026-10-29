# Only NEXT_PUBLIC_ env vars reach the browser

Anything without the `NEXT_PUBLIC_` prefix stays on the server, which is where secret keys belong.
