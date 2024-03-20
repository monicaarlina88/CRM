# Ajak Teman

This page is used to track which customer already brought another customer from their referral code and track if they have already paid with commission and the detail of payment method.

Each of the referral will have 2 status based on the eligibility status from Ajak Teman terms and condition and payment status of the referred customer.

To get `ELIGIBLE` status, the referral will have to achieve 1 lot in a month. If the month already passed and they haven't achieve it, they will be set as `NOT ELIGIBLE`

<figure><img src="../../.gitbook/assets/App &#x26; CRM (20).jpg" alt=""><figcaption></figcaption></figure>

## Ajak Teman Flow :&#x20;

* Customer will refer their friend to join Valbury using their referral code
* Once the referral joins the system check if this customer already have 20 or more referral,
  * If YES, then the new referral will have `Not Eligible` status and the customer will not get commission from this referral
  * If NOT, then system will check if this referral already `Eligible` or not
    * If Yes, then we will update the customer payment status by inputting when we paid, the payment method, set the payment status and how much they will get.
    * If Not, then the system will set to `Not Eligible` and the customer will not get commission from this referral
* If there's less than 20 referral, CSO will pay the commission based on how many referral this customer have.

<figure><img src="../../.gitbook/assets/CRM (Referral) Ajak Teman (1).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/CRM (Referral) Ajak Teman_update (1).png" alt=""><figcaption></figcaption></figure>

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

Benefit of Ajak Teman referral :&#x20;

* For each referral joined from user's Ajak Teman, they will receive Rp 500.000,- with maximum 20 referral.
* Client can only join via user's referral link in Valbury App
* CSO can update the payment status for each eligible client that join via user's referral link.

### Menghitung jumlah nasabah yang direferralkan

Admin dapat mengecek berapa banyak akun yang terdaftar menggunakan kode Ajak Teman dari nasabah dan memberikan tanda jika nasabah tersebut sudah mendaftarkan 20 teman yang eligible.

Untuk mengecek detail teman yang sudah diajak dan jumlah yang sudah `PAID` atau `UNPAID` maka admin dapat klik tombol **Update** dan akan muncul detailnya.

<figure><img src="https://valbury.gitbook.io/~gitbook/image?url=https:%2F%2F1419112617-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252F9bd901PWyHrcrr6MgxiG%252Fuploads%252FkDAOSJEqopBfJohtbtEm%252FAjak%2520Teman.png%3Falt=media%26token=4c64d1db-eb9a-42e0-8492-fa15ac12f049&#x26;width=300&#x26;dpr=4&#x26;quality=100&#x26;sign=b33290577361d8354b4e53a430d3833eb099315f63c87cf4237a62607f7b84d8" alt=""><figcaption></figcaption></figure>
