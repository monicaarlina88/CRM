# Leads

This page is use to view, track and update the list of prospective customer. These leads can come from any of our leads generator page (e.g. Website, Sales Campaign page, Apps, MyTrade, etc).

These leads have several status :&#x20;

| Status     | Definition                                                                    |
| ---------- | ----------------------------------------------------------------------------- |
| New        | New lead added manually or import leads on CRM                                |
| In Process | New leads after add task to approach them                                     |
| Qualified  | Leads who has been have demo account activated                                |
| Failed     | Lead has been approach but unfortunately decided not to join / have no result |
| Converted  | Lead decided to create live account                                           |
| Funded     | Lead successfully create first time deposit                                   |

<figure><img src="../../.gitbook/assets/Screenshot 2023-02-07 at 14.49.24.png" alt=""><figcaption></figcaption></figure>

## Leads status flow :&#x20;

* When `New` leads appear on the list, sales will approach them and it will change the status to `In Process`.
  * If the leads decided to register and create a demo account then the status will change to `Qualified`
  * If not then the status change to `Failed`.
* Once the leads already try their demo account and decided to create a live account, they will have to fill out a due diligence document and submit it to our system. The status will updated to `Converted` in Leads menu and a new account will appear in Accounts menu.
* When the leads deposit money to their live account, system will update the status of leads to `Funded` in the list.

<figure><img src="../../.gitbook/assets/Screenshot 2023-02-08 at 16.01.34.png" alt=""><figcaption></figcaption></figure>

UTM Description :&#x20;

| UTM Name     | Description                                                                                          |
| ------------ | ---------------------------------------------------------------------------------------------------- |
| Google       | Nasabah yang mendapatkan link dari Google                                                            |
| Data Pribadi | Daftar dengan kode sales                                                                             |
| Organic      | Nasabah yang mendaftar langsung ke app tanpa FC, RC, Unity Code                                      |
| TikTok Ads   | Nasabah yang mendapatkan link dari TikTok                                                            |
| Data         | Data Pribadi yang terpotong                                                                          |
| Satu Persen  | Nasabah yang mendapatkan link dari satu persen (channel marketing seperti google, detik, dan tiktok) |
| Facebook Ads | Nasabah mendapatkan link dari Facebook                                                               |
| Unattributed | Kondisi dimana nasabah mendaftar antara organic atau channel marketing                               |
| Data IB      | Pendaftaran dari IB                                                                                  |

| Code                   | Description                                                                                                                 |
| ---------------------- | --------------------------------------------------------------------------------------------------------------------------- |
| FC (Marketing Code)    | Kode yang terbuat secara otomatis untuk tiap Marketing berdasarkan cabangnya masing-masing                                  |
| RC                     | Kode yang terbuat secara otomatis untuk nasabah mengajak teman (kode Ajak Teman) atau IB mengajak referral (kode IB)        |
| Special Code           | Kode spesial yang ditambahkan untuk membuka komisi baru atau rate baru                                                      |
| Origin Code/Unity Code | Origin code atau Unity code adalah kode gabungan yang digenerate oleh admin, kode yang sudah dimasukkan tidak dapat berubah |

