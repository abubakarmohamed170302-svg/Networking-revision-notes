# Commands Used

## SSH into EC2

```bash
ssh -i abu-nginx-key.pem ubuntu@54.196.147.85
```

## Update packages

```bash
sudo apt update
```

## Install NGINX

```bash
sudo apt install -y nginx
```

## Enable NGINX

```bash
sudo systemctl enable nginx
```

## Start NGINX

```bash
sudo systemctl start nginx
```

## Check NGINX status

```bash
sudo systemctl status nginx
```

## Check listening ports

```bash
sudo ss -tulnp | grep :80
```

## Test domain

```bash
curl http://nginx.abubakarmohamed.dev
```

