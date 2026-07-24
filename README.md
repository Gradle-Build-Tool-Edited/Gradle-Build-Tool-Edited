<!-- تب‌ها -->
<div style="display: flex; gap: 10px; margin-bottom: 20px;">
  <button onclick="document.getElementById('en').style.display='block'; document.getElementById('fa').style.display='none';" style="padding: 8px 16px; background: #0366d6; color: white; border: none; border-radius: 4px; cursor: pointer;">🇬🇧 English</button>
  <button onclick="document.getElementById('fa').style.display='block'; document.getElementById('en').style.display='none';" style="padding: 8px 16px; background: #0366d6; color: white; border: none; border-radius: 4px; cursor: pointer;">🇮🇷 فارسی</button>
</div>

<!-- محتوای انگلیسی -->
<div id="en" style="display: block;">
  <h2>🚀 What's New in v1.0</h2>
  <h3>🔧 Core Upgrades</h3>
  <ul>
    <li><strong>Java:</strong> Upgraded from 21 to <strong>25</strong></li>
    <li><strong>Gradle:</strong> Bumped from <code>9.3.2</code> to <code>9.7.0-rc-1</code></li>
  </ul>
  <h3>✨ New Features</h3>
  <ul>
    <li>Background execution when app opens</li>
    <li>Added <code>keytool</code> command for Java 25</li>
    <li>Updated syntax textures to official new ones</li>
  </ul>
</div>

<!-- محتوای فارسی -->
<div id="fa" style="display: none;">
  <h2>🚀 تغییرات نسخه ۱.۰</h2>
  <h3>🔧 ارتقاء هسته</h3>
  <ul>
    <li><strong>جاوا:</strong> از نسخه ۲۱ به <strong>۲۵</strong></li>
    <li><strong>گریدل:</strong> از <code>9.3.2</code> به <code>9.7.0-rc-1</code></li>
  </ul>
  <h3>✨ ویژگی‌های جدید</h3>
  <ul>
    <li>اجرای برنامه در پس‌زمینه</li>
    <li>اضافه شدن دستور <code>keytool</code> برای جاوا ۲۵</li>
    <li>تکسچر جدید زبان‌های برنامه‌نویسی</li>
  </ul>
</div>
