# jmargutti.io
my website

## Run locally

On Windows PowerShell, point Ruby at its bundled CA certificates before starting Jekyll:

```powershell
$env:SSL_CERT_FILE = "C:\Ruby40-x64\ssl\cert.pem"
```

```sh
bundle exec jekyll serve
```

Open <http://127.0.0.1:4000/> in your browser. Jekyll rebuilds the site when files change.
