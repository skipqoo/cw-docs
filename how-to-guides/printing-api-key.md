---
description: >-
  How to setup your API key.  This is used to connect your online printing
  configuration to your PushPrinter application and receipt printer.
---

# Printing - API Key

1. Login to your Skipqoo account at [admin.SkipQoo.app](https://admin.skipqoo.app) and go to Settings&gt;System&gt;Receipt Printing&gt;Create Printer.

![](../.gitbook/assets/1-create-printer.png)

2. Name the printer, ideally use the same name as the settings in PushPrinter to avoid confusion. We also recommend turning on 'Auto Print Orders' and 'Auto Print Bookings'.

![](../.gitbook/assets/untitled%20%282%29.png)

3. Now select 'Printer Settings' and make sure that;

4. 'Printing Method' - is set to ESCPOS

5. 'ESCPOS Printing Type' - is set to 'ESCPOS Image'.

{% hint style="warning" %}
**NOTE** - In the case that your printer doesn't support image printer \(not printing correctly or printing very slowly\) Please change this to 'ESCPOS Text Only'.
{% endhint %}

![](../.gitbook/assets/untitled-1%20%282%29.png)

6. Scroll to the bottom on the screen and press the 'Save' button.

7. Then highlight the API key &gt; right click &gt; copy to clipboard.

![](../.gitbook/assets/untitled-2%20%283%29.png)

8. Paste the API key into the relevant API field in PushPrinter.

