---
layout: single
title: "Contact Me"
permalink: /contact/
author_profile: true
---

If you have any questions, collaboration proposals, or just want to say hi, feel free to drop a message using the form below.

<div markdown="0">
<form action="https://api.web3forms.com/submit" method="POST" style="margin-top: 20px;">

  <!-- แทนที่ YOUR_ACCESS_KEY_HERE ด้วย Access Key ที่ได้จาก Web3Forms -->
  <input type="hidden" name="access_key" value="987b0626-a757-47c4-8e32-eff7944aa598">

  <!-- (Option) กำหนดหัวข้ออีเมลที่จะส่งเข้ามาหาคุณ -->
  <input type="hidden" name="subject" value="New Submission from Personal Website">

  <!-- (Option) ป้องกัน Bot ด้วย Honeypot Spam Protection -->
  <input type="checkbox" name="botcheck" class="hidden" style="display: none;">

  <div style="margin-bottom: 15px;">
    <label for="name" style="display: block; margin-bottom: 5px; font-weight: bold;">Your Name</label>
    <input type="text" id="name" name="name" required style="width: 100%; padding: 8px; border: 1px solid #ccc; border-radius: 4px;">
  </div>

  <div style="margin-bottom: 15px;">
    <label for="email" style="display: block; margin-bottom: 5px; font-weight: bold;">Your Email</label>
    <input type="email" id="email" name="email" required style="width: 100%; padding: 8px; border: 1px solid #ccc; border-radius: 4px;">
  </div>

  <div style="margin-bottom: 15px;">
    <label for="message" style="display: block; margin-bottom: 5px; font-weight: bold;">Message</label>
    <textarea id="message" name="message" rows="5" required style="width: 100%; padding: 8px; border: 1px solid #ccc; border-radius: 4px;"></textarea>
  </div>

  <!-- (Option) ตั้งค่าหน้าเว็บหลังกดส่งสำเร็จ (ถ้าไม่ใส่ จะแสดงหน้า Thank you ของ Web3Forms แทน) -->
  <!-- <input type="hidden" name="redirect" value="https://yourusername.github.io/thanks/"> -->

  <button type="submit" style="background-color: #007acc; color: white; padding: 10px 20px; border: none; border-radius: 4px; cursor: pointer;">Send Message</button>
</form>
</div>
