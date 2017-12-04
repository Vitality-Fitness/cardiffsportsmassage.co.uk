---
title: "Buy a Gift Voucher"
date: 2017-12-04T19:11:11Z
draft: false
---

Please fill in the following form to buy a gift voucher.

Payment will be made by PayPal, and the gift voucher will be sent to the email address used by your PayPal account within 3 working days.

---

<form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top">
  <input type="hidden" name="cmd" value="_s-xclick">
  <input type="hidden" name="hosted_button_id" value="46HCZEDRR2UKS">
  <input type="hidden" name="on1" value="Name on Voucher">
  <input type="hidden" name="on0" value="Voucher">
  <input type="hidden" name="currency_code" value="GBP">
  <div class="form-group">
    <label for="os1">Name on Voucher</label>
    <input type="text" class="form-control" name="os1" maxlength="200" required aria-describedby="nameHelp" placeholder="Joe Bloggs">
    <small id="nameHelp" class="form-text text-muted">Please enter the name you'd like to be written on the voucher.</small>
  </div>
  <div class="form-group">
    <label for="os0">Voucher Type</label>
    <select name="os0" class="form-control" aria-describedby="voucherHelp">
       <option value="30 Minutes">30 Minutes £25.00 GBP</option>
       <option value="60 Minutes">60 Minutes £40.00 GBP</option>
    </select>
    <small id="voucherHelp" class="form-text text-muted">Please select the length of treatment you'd like to buy.</small>
  </div>
  <div class="form-group">
    <input class="btn btn-primary" type="submit" name="submit" value="Pay with PayPal">
    <img alt="" border="0" src="https://www.paypalobjects.com/en_GB/i/scr/pixel.gif" width="1" height="1">
  </div>
</form>
