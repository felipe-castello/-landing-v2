# Nexus IoT Energy Landing Page

Arquivos prontos para subir no GitHub e publicar na VPS.

## Estrutura

- `index.html` — página pública
- `styles.css` — layout responsivo
- `script.js` — menu mobile
- `logo-nexus-iot-energy.jpg` — logo oficial
- `deploy.sh` — script simples para copiar arquivos na VPS
- `nginx-nexusiotenergy.conf` — exemplo de configuração Nginx

## Publicação sugerida

Domínio público:

`www.nexusiotenergy.com.br`

Sistema FCX 5.2:

`https://app.nexusiotenergy.com.br/login`

## VPS

```bash
cd /var/www/nexus-iot-energy-landing
sudo git pull
sudo systemctl reload nginx
```

Se usar o script:

```bash
chmod +x deploy.sh
sudo ./deploy.sh
```

## Atenção

Esta landing page não altera backend, autenticação ou app FCX 5.2.
