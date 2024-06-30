---
description: >-
  Learn how to setup Stripe+ payments.  This is our recommend solution for
  online payments due to their streamlined setup, user experience and self
  service options in our dashboard.
---

# Setup Integrated Stripe Payments

### Steps to Set Up Stripe+ Payments:

1. **Login:** Access your admin dashboard at [https://admin.pumpd.co.nz ](https://admin.pumpd.co.nz)[.](https://admin.pumpd.co.nz)
2. **Navigate to Settings:** Go to **Settings > Payments > Add Payment Method > Stripe > Add Method**.

<figure><img src="../.gitbook/assets/Settings-payments-Stripe.png" alt=""><figcaption><p>Settings > Payments > Add Payment Method > Stripe > Add Method</p></figcaption></figure>

#### Recommended Minimum Settings for Stripe:

| Setting                        | Recommendation              | Notes                                                                                               |
| ------------------------------ | --------------------------- | --------------------------------------------------------------------------------------------------- |
| **Enabled**                    | On                          | Activates the feature                                                                               |
| **Stripe Secret Key**          | sk\_live                    |                                                                                                     |
| **Stripe Publishable Key**     | pk\_live                    |                                                                                                     |
| **Stripe Version**             | Version 2                   | Only use Version 1 if requested by Pump'd support                                                   |
| **Currency**                   | NZD - Australian Dollar - $ | Use your local currency                                                                             |
| **Disable E-Mail Receipt**     |                             |                                                                                                     |
| **Enable Custom Payment Form** |                             |                                                                                                     |
| **Layout**                     | Themes                      |                                                                                                     |
| **Services**                   | Label                       | Pay - Online                                                                                        |
| **Delivery Label**             | Print Label                 | _PAID - ONLINE_                                                                                     |
| **Maximum Order Value ($)**    | 999                         | Set a realistic maximum online order total                                                          |
| **Minimum Order Value ($)**    | 2                           | Minimum transaction should not be lower than $2                                                     |
| **SC Account ID**              | GET THIS FROM SUPPORT       | Example format - acct\_1A3abABCABCac1aA. Contact chat/email support to activate your SC Account ID. |

3. **Save Settings:** Press **Save** to apply the settings.
4. **Test Your Setup:** Launch your store and place a live test order using your card, Google Pay, or Apple Pay.
5. **Get Assistance:** For any issues or to activate your SC Account ID, please email Gianni@pumpd.co.nz or use the chat support feature.

{% hint style="danger" %}
Please email [Gianni@pumpd.co.nz](https://app.gitbook.com/u/MjyhhhNdIeS3Tw8pUFix0pXVbaB2) or use the chat support feature to get assistance activating this feature.
{% endhint %}

### Don't Have a Pump'd Account?

Visit [https://admin.pumpd.co.nz/register](https://admin.pumpd.co.nz/register) and create your account.

{% content-ref url="using-stripe-integrated.md" %}
[using-stripe-integrated.md](using-stripe-integrated.md)
{% endcontent-ref %}
