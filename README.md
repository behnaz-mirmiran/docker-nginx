# 🌐 Docker NGINX Static Website

پروژه‌ای برای اجرای یک وب‌سایت ساده استاتیک با استفاده از NGINX در Docker.

---

## 🚀 نحوه اجرا

### 1. ساخت ایمیج:

```bash
docker build -t nginx-static .


docker run -p 8080:80 nginx-static
