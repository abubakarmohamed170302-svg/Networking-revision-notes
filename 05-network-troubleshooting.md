# Network Troubleshooting

## Why Troubleshooting Matters

In DevOps, things break.

Common issues:

* website down
* DNS failure
* server unreachable
* slow connections

Troubleshooting finds the cause.

---

## Ping

Tests connectivity.

Example:

```bash id="d6gh3n"
ping google.com
```

Checks:

* can we reach it?
* is it alive?

---

## Traceroute

Shows path packets take.

Linux:

```bash id="l5zm8d"
traceroute google.com
```

Windows:

```bash id="ay6f1u"
tracert google.com
```

Useful for finding where connection fails.

---

## nslookup

Checks DNS.

Example:

```bash id="iy1t8w"
nslookup google.com
```

Tests:

* DNS resolution
* returned IP

---

## dig

More detailed DNS.

Example:

```bash id="l0ypt4"
dig google.com
```

Used a lot in Linux.

---

## netstat

Shows connections and listening ports.

Example:

```bash id="m8yvsq"
netstat -tuln
```

Useful for checking open ports.

---

## ss

Modern replacement for netstat.

Example:

```bash id="it9dr8"
ss -tuln
```

Very useful.

---

## curl

Tests HTTP.

Example:

```bash id="xt92v3"
curl google.com
```

Checks website response.

---

## Troubleshooting Flow

Example:

Website down.

Step 1:

```bash id="cv8m3n"
ping
```

Can we reach it?

Step 2:

```bash id="yy1r8v"
nslookup
```

Is DNS working?

Step 3:

```bash id="kl0p8q"
traceroute
```

Where does it fail?

Step 4:

```bash id="z9dh1s"
curl
```

Is app responding?

---

## Real World DevOps Mindset

Think:

```text id="wd4fne"
What broke?
Where broke?
Why broke?
How fix?
```

That mindset matters more than memorising commands.
