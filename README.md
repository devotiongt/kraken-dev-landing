# krakengt.com

Landing de Kevin Morán / Kraken GT. Sitio estático (HTML + CSS + JS), sin build.

## Desarrollo local

```bash
python3 -m http.server 8080
```

## Despliegue en GitHub Pages

1. Crear el repo (por ejemplo `krakengt/krakengt.github.io` o cualquier repo con Pages activado en la rama `main`, carpeta `/`).
2. `git push`. El archivo `CNAME` ya apunta a `krakengt.com`.
3. En el DNS de `krakengt.com` agregar:
   - `A` @ → `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - `CNAME` www → `<usuario>.github.io`
4. En Settings → Pages, marcar **Enforce HTTPS** cuando el certificado esté listo.

`biblenames.krakengt.com` es un subdominio aparte y no se ve afectado.
