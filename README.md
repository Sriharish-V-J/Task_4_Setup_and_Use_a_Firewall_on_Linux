# Task_4_Setup_and_Use_a_Firewall_on_Linux

## 🎯 Objective
To configure and test basic firewall rules that allow or block traffic, understanding how firewalls filter and secure network connections.

---

## 🛠️ Tools Used

| OS        | Tool                        |
|-----------|-----------------------------|
| Linux     | UFW (Uncomplicated Firewall)|

---

## 🐧 Linux (UFW)

### 1️⃣ Check and Enable UFW

```bash
sudo ufw status verbose
sudo ufw enable
```

### 2️⃣  Block Inbound Telnet (Port 23)

```bash
sudo ufw deny 23
```

### 3️⃣ Allow SSH (Port 22)

```bash
sudo ufw allow 22
```

### 4️⃣ View Rules

```bash
sudo ufw status numbered
```

### 5️⃣ Remove Rule

```bash
sudo ufw delete deny 23
```

