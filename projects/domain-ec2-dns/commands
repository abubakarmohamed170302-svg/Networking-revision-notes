# Commands Used

## 1. SSH into the EC2 instance

```bash
ssh -i abu-nginx-key.pem ubuntu@54.196.147.85
```

**What it does:**
Connects to the Ubuntu EC2 server using the private SSH key.

**Simple meaning:**
This is how I remotely logged into my cloud server.

---

## 2. Update package list

```bash
sudo apt update
```

**What it does:**
Refreshes Ubuntu’s package list.

**Simple meaning:**
Checks for the latest available software updates.

---

## 3. Install NGINX

```bash
sudo apt install -y nginx
```

**What it does:**
Installs NGINX web server.

**Simple meaning:**
Sets up the software needed to host a website.

---

## 4. Enable NGINX on boot

```bash
sudo systemctl enable nginx
```

**What it does:**
Makes NGINX start automatically after reboot.

**Simple meaning:**
Keeps the web server running even after restarting.

---

## 5. Start NGINX

```bash
sudo systemctl start nginx
```

**What it does:**
Starts the NGINX service.

**Simple meaning:**
Turns the web server on.

---

## 6. Check NGINX status

```bash
sudo systemctl status nginx
```

**What it does:**
Shows if NGINX is running.

**Simple meaning:**
Checks if the web server is healthy.

---

## 7. Check internal IP address

```bash
hostname -I
```

**What it does:**
Shows the server’s internal/private IP.

**Simple meaning:**
Displays the EC2 machine’s private AWS network address.

---

## 8. Check if NGINX is listening on port 80

```bash
sudo ss -tulnp | grep :80
```

**What it does:**
Shows if NGINX is listening for web traffic.

**Simple meaning:**
Confirms the server is accepting HTTP requests.

---

## 9. Test NGINX locally

```bash
curl localhost
```

**What it does:**
Tests the website from inside the server.

**Simple meaning:**
Checks if NGINX works on the machine itself.

---

## 10. Check DNS record

```bash
nslookup nginx.abubakarmohamed.dev
```

**What it does:**
Checks where the domain points.

**Simple meaning:**
Confirms the domain is linked to the EC2 public IP.

---

## 11. Test domain from server

```bash
curl http://nginx.abubakarmohamed.dev
```

**What it does:**
Tests if the domain loads the NGINX page.

**Simple meaning:**
Checks if DNS and NGINX work together.

---

## 12. Test public IP in browser

```text
http://54.196.147.85
```

**What it does:**
Loads the website directly using the EC2 public IP.

**Simple meaning:**
Tests if the server works without DNS.

---

## 13. Test domain in browser

```text
https://nginx.abubakarmohamed.dev
```

**What it does:**
Loads the website using the custom domain.

**Simple meaning:**
Tests the full working setup.

