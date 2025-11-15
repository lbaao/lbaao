## Hi there 👋


- 🌱 I’m currently learning UI design

- ⚡ Fun fact: shahr kord.kord nadare
<h1 align="center">🚀 پروژه‌ی خفن من</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Status-در%20حال%20توسعه-yellow" alt="Project Status">
  <img src="https://img.shields.io/badge/ساخته%20شده%20با-Rust-blue" alt="Built with Rust">
</p>

<div align="center">
  <img src="https://your-image-url.com/banner.png" alt="Banner" width="80%">
</div>

---

<h2>📦 درباره پروژه</h2>

<p>
  این پروژه یک API سریع، امن و مقیاس‌پذیر با استفاده از <strong>Rust</strong> و <strong>Docker</strong> است. تمرکز اصلی روی <em>امنیت، وضوح معماری</em> و <code>best practices</code> در توسعه‌ی بک‌اند است.
</p>

---

<h2>🧱 ساختار پروژه</h2>

<table>
  <tr>
    <th>مسیر</th>
    <th>توضیح</th>
  </tr>
  <tr>
    <td><code>src/config.rs</code></td>
    <td>تنظیمات پروژه و بارگذاری از env</td>
  </tr>
  <tr>
    <td><code>src/redis.rs</code></td>
    <td>اتصال امن به Redis با TLS</td>
  </tr>
  <tr>
    <td><code>src/db/pool.rs</code></td>
    <td>مدیریت اتصال به Postgres با connection pooling</td>
  </tr>
</table>

---

<h2>⚙️ اجرا با Docker</h2>

```bash
docker compose up --build
