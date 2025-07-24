# Basic Linux Commands

# 🐧 Basic Linux Commands for System Administrators

এই ডকুমেন্টটি নতুন Linux System Administrator দের জন্য প্রাথমিক এবং দরকারি কিছু কমান্ড নিয়ে তৈরি করা হয়েছে।

---

## 🔍 1. System Info Commands
| Command | Description |
|--------|-------------|
| `uname -a` | সম্পূর্ণ সিস্টেম ইনফো দেখায় |
| `hostname` | হোস্টনেম চেক করে |
| `uptime` | সিস্টেম কতক্ষণ চালু আছে |
| `top` | লাইভ প্রসেস মোনিটর করে |
| `htop` | উন্নত প্রসেস ভিউয়ার (ইনস্টল করতে হয়) |
| `whoami` | আপনি কে (ইউজারনেম) |

---

## 📁 2. File & Directory Commands
| Command | Description |
|--------|-------------|
| `ls` | ফোল্ডারের কনটেন্ট দেখতে |
| `ls -la` | হিডেন ফাইলসহ ডিটেইল লিস্ট |
| `cd /path/` | ফোল্ডার চেঞ্জ করতে |
| `pwd` | কারেন্ট লোকেশন চেক করতে |
| `mkdir newfolder` | নতুন ফোল্ডার বানাতে |
| `rm file.txt` | ফাইল ডিলিট করতে |
| `rm -rf foldername/` | ফোল্ডারসহ সব ডিলিট করতে |

---

## 📝 3. File Handling
| Command | Description |
|--------|-------------|
| `cat file.txt` | ফাইল কনটেন্ট দেখতে |
| `nano file.txt` | ফাইল এডিট করতে (Text editor) |
| `cp file.txt /backup/` | ফাইল কপি করতে |
| `mv old.txt new.txt` | ফাইল রিনেম করতে বা মুভ করতে |

---

## 🔐 4. User & Permissions
| Command | Description |
|--------|-------------|
| `adduser atik` | নতুন ইউজার তৈরি করতে |
| `passwd atik` | ইউজারের পাসওয়ার্ড সেট করতে |
| `usermod -aG sudo atik` | ইউজারকে sudo অ্যাক্সেস দিতে |
| `chown atik:atik file.txt` | ফাইলের মালিকানা বদলাতে |
| `chmod 755 script.sh` | ফাইল পারমিশন সেট করতে |

---

## 🌐 5. Network Commands
| Command | Description |
|--------|-------------|
| `ip a` / `ifconfig` | IP info চেক করতে |
| `ping google.com` | কানেক্টিভিটি টেস্ট |
| `netstat -tulnp` | ওপেন পোর্ট এবং সার্ভিস দেখতে |
| `curl ifconfig.me` | পাবলিক IP দেখতে |

---

## 📦 6. Package Management (Debian-based)
| Command | Description |
|--------|-------------|
| `sudo apt update` | প্যাকেজ লিস্ট আপডেট করতে |
| `sudo apt upgrade` | সিস্টেম আপগ্রেড করতে |
| `sudo apt install nginx` | নতুন প্যাকেজ ইনস্টল |
| `sudo apt remove nginx` | প্যাকেজ রিমুভ করতে |

---

## 🛠️ 7. Services & Process
| Command | Description |
|--------|-------------|
| `systemctl status ssh` | SSH সার্ভিস স্ট্যাটাস দেখতে |
| `systemctl restart apache2` | সার্ভিস রিস্টার্ট করতে |
| `ps aux` | সকল প্রসেস দেখতে |
| `kill -9 PID` | প্রসেস kill করতে |

---

## 📄 8. File Search & Disk
| Command | Description |
|--------|-------------|
| `find / -name file.txt` | সিস্টেমে ফাইল খুঁজতে |
| `df -h` | ডিস্ক usage দেখতে |
| `du -sh folder/` | ফোল্ডার সাইজ দেখতে |

---

## ✅ 9. Others
| Command | Description |
|--------|-------------|
| `history` | আপনার কমান্ড হিস্টোরি |
| `clear` | টার্মিনাল ক্লিয়ার করতে |
| `alias ll='ls -la'` | শর্টকাট কমান্ড বানাতে |

---

📌 **নোট:** Ubuntu, Debian, Kali ইত্যাদির জন্য উপযুক্ত। অন্য ডিস্ট্রোতে কিছু পার্থক্য হতে পারে।

---

✍️ Created by [Atikul Islam (iamatikahad)](https://github.com/iamatikahad)
