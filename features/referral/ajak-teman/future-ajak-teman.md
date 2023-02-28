# Future Ajak Teman

This page is used to track which customer already brought another customer from their referral code and track if they have already paid with commission and the detail of payment method.

Each of the referral will have 2 status based on the eligibility status from Ajak Teman terms and condition and payment status of the referred customer.

To get `ELIGIBLE` status, the referral will have to achieve 1 lot in a month. If the month already passed and they haven't achieve it, they will be set as `NOT ELIGIBLE`

<figure><img src="../../../.gitbook/assets/App &#x26; CRM (20).jpg" alt=""><figcaption></figcaption></figure>

## Ajak Teman Flow :&#x20;

* Customer will refer their friend to join Valbury using their referral code
* Once the referral joins the system check if this customer already have 10 or more referral,
  * If YES, then the new referral will have `Not Eligible` status and the customer will not get commission from this referral
  * If NOT, then system will check if this referral already `Eligible` or not
    * If Yes, then we will update the customer payment status by inputting when we paid, the payment method, set the payment status and how much they will get.
    * If Not, then the system will set to `Not Eligible` and the customer will not get commission from this referral

<figure><img src="../../../.gitbook/assets/CRM (Referral) Ajak Teman (1).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../../.gitbook/assets/CRM (Referral) Ajak Teman_update (1).png" alt=""><figcaption></figcaption></figure>

| Field           | Type   | Description                      |
| --------------- | ------ | -------------------------------- |
| No              | Number | Number of list                   |
| Name            | Text   | Referral Name                    |
| Email           | Text   | Referral Email                   |
| Referred Name   | Text   | Customer referred name           |
| Referral Email  | Text   | Customer referred email          |
| Referral in Use | Text   | Customer referral code           |
| Tgl Aktivasi    | Date   | Activation date                  |
| Status          | Text   | Referral status                  |
| Tgl Pencapaian  | Date   | Achieve referral date            |
| Payment status  | Text   | Customer referred payment status |
| Method          | Text   | Payment method                   |
| Payment Date    | Date   | Payment Date                     |
