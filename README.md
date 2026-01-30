# deface
Master project of deface-backend and deface-frontend.

## Install
Checkout this repository:
```bash
git clone git@github.com:DerIngo/deface.git
```
Checkout backend and frontend:
```bash
cd deface
git clone git@github.com:DerIngo/deface-backend.git
git clone git@github.com:DerIngo/deface-frontend.git
```
Set domain name (for Traefik):
```bash
cp .env.example .env
vim .env
```
Create Docker Volume:
```bash
docker volume create deface-volume
```

## Run
Start deface:
```bash
docker compose up -d
```
Watch logging:
```bash
docker compose logs -f
```
