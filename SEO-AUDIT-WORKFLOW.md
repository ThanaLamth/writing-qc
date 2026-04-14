# SEO Audit Workflow

Tai lieu nay thay the cho workflow audit cu theo huong thuc chien hon, uu tien tinh chinh xac khi ra quyet dinh URL, content, crawl, index, va backlink.

## 1. Muc tieu cua SEO audit

SEO audit khong phai la viec check loi cho du. Muc tieu dung la:

- xac dinh van de ky thuat dang can index, crawl, xep hang, va trai nghiem nguoi dung
- xac dinh URL nao nen giu, viet lai, redirect, noindex, hoac xoa
- xac dinh content hub, taxonomy, va trust pages co du manh hay chua
- lap action plan theo muc do anh huong, cong suc, va thu tu uu tien

SEO audit can duoc lam:

- khi tiep nhan du an moi
- khi traffic hoac ranking giam manh
- truoc khi remap, gom bai evergreen, hoac don content hang loat
- dinh ky de kiem soat crawl, index, metadata, va trust stack

## 2. Bo nguon du lieu can co

Khong nen audit bang cam giac. Bo du lieu uu tien:

### Bat buoc

- `Google Search Console`
  - clicks
  - impressions
  - CTR
  - average position
  - queries
  - pages
- `Screaming Frog`
  - status codes
  - indexability
  - canonicals
  - directives
  - sitemap coverage
  - inlinks
  - orphan URLs
- `Semrush` hoac `Ahrefs`
  - backlinks
  - referring domains
  - target URL
  - anchor text
  - follow / nofollow
  - first seen / last seen

### Nguon bo tro

- `Google Analytics`
  - engagement metrics
  - conversion support
  - time on page
- manual review
  - homepage
  - category / tag / archive pages
  - article pages
  - author pages
  - trust pages
  - robots.txt
  - sitemap index

## 3. Thu tu uu tien cua cac nguon

Khi co xung dot giua cac so lieu, uu tien theo thu tu sau:

1. `Google Search Console` cho SEO performance thuc te
2. `Screaming Frog` cho tinh trang crawl / index / status / sitemap
3. `Semrush` hoac `Ahrefs` cho backlink va authority signals
4. `Google Analytics` cho hanh vi va business context

Luu y:

- `GSC` la nguon chinh de quyet dinh URL co gia tri tim kiem hay khong
- `GA` khong thay the `GSC`
- backlink data chi la mot lop quyet dinh, khong du de tu mot minh ra lenh keep / delete / redirect

## 4. Cac nhom audit chinh

### Technical SEO

Can check:

- robots.txt
- sitemap index va sitemap con
- non-indexable URLs in sitemap
- canonical conflicts
- missing canonical
- redirect chains
- internal 4xx / 5xx
- archive va utility pages bi index
- duplicate URL patterns
- orphan URLs
- media / image URLs bi loi

### Content Audit

Can check:

- content co dung search intent khong
- bai co gia tri rieng hay chi la phien ban yeu hon cua bai khac
- content co trung lap / gan trung lap khong
- co thin content khong
- co source, chung cu, entity signals, authorship khong
- co dang spam commercial hoac parasite style khong

### On-page Audit

Can check:

- title missing / duplicate / qua dai
- meta description missing / duplicate
- H1 / heading hierarchy
- internal links
- anchor text
- canonical tags
- indexability rules

### Trust / E-E-A-T Audit

Can check:

- about page
- contact page
- editorial policy
- corrections policy
- author pages
- ownership / ads / sponsored disclosure
- trust pages co duoc link noi bo khong

### Backlink Audit

Can check:

- URL nao co referring domains that su
- URL nao co backlink nhung dang 404
- backlink co lien quan den chu de khong
- target URL co nen giu, redirect, hay phuc hoi
- co pattern link spam ro rang khong

## 5. Framework quyet dinh URL

Day la phan quan trong nhat. Khong quyet dinh bang mot metric don le.

Moi URL can duoc danh gia theo 4 lop:

1. `Indexability`
2. `Search performance`
3. `Intent / uniqueness`
4. `Backlink / business value`

### Lop 1: Indexability

Can tra loi:

- URL tra ve gi? `200`, `301`, `404`, `410`, `5xx`
- dang `Indexable` hay `Non-Indexable`
- co trong sitemap khong
- canonical co dung khong
- co bi noindex khong

Neu URL da sai o lop nay, uu tien sua ky thuat truoc khi ban den content.

### Lop 2: Search performance

Lay tu `GSC`, uu tien 3 thang gan nhat hoac 6 thang neu site it traffic:

- clicks
- impressions
- CTR
- average position
- top queries

Interpretation:

- co impressions / clicks that su: URL dang co gia tri search
- impressions = 0 trong thoi gian dai: co the URL yeu, khong duoc index, hoac khong phu hop intent

### Lop 3: Intent / uniqueness

Can hoi:

- URL nay co phuc vu mot nhu cau tim kiem rieng khong?
- Neu user search tu khoa nay, co nen de URL nay rank khong?
- No co trung vai tro voi mot URL manh hon khong?
- No co chi la archive, utility page, hoac trang phu khong?

### Lop 4: Backlink / business value

Can hoi:

- URL co referring domains that su khong?
- backlink co lien quan khong?
- URL co role kinh doanh / legal / trust / conversion khong?

## 6. Rule hanh dong cho moi URL

### Giu va toi uu

Ap dung khi:

- URL co gia tri rieng
- dang co clicks / impressions co y nghia
- intent khac voi URL khac
- co backlink tot

Hanh dong:

- giu URL
- cap nhat noi dung
- toi uu internal links
- cap nhat title / meta / schema neu can

### Viet lai / nang cap

Ap dung khi:

- URL dung intent nhung content yeu
- co impressions nhung CTR thap hoac rank yeu
- co backlink / gia tri lich su dang giu lai

Hanh dong:

- viet lai bai
- bo sung source, facts, visuals, structure
- tang internal links tu hub lien quan

### Redirect 301

Chi ap dung khi:

- co URL thay the ro rang
- hai URL cung intent hoac URL cu la phien ban yeu hon cua URL moi
- muon gom tin hieu ve mot trang manh hon

Khong duoc redirect bua ve homepage.

Rule:

- `same intent + valid replacement` -> `301`
- `many weak URLs` -> redirect ve `1 strong evergreen URL`

### Noindex

Ap dung khi:

- URL can ton tai cho user nhung khong can len search
- login, account, bookmarks, filters, utility pages
- archive phu, pagination, hoac cac trang gia tri thap can ton tai cho dieu huong

### Delete / 404 / 410

Ap dung khi:

- URL khong con gia tri
- khong co replacement phu hop
- khong co traffic, khong co backlink, khong co vai tro kinh doanh
- la trang rac, loi, hoac spam

Rule:

- `khong co replacement` -> `404` hoac `410`
- khong duoc `301` ve homepage chi de "don site"

## 7. Workflow thuc thi de xu ly hang loat

### Buoc 1: Crawl va lay inventory

Tu `Screaming Frog`, export:

- internal HTML
- response codes 3xx / 4xx / 5xx
- canonicals missing / canonicalised
- directives noindex
- sitemaps URLs in sitemap
- sitemaps non-indexable URLs in sitemap
- orphan URLs
- page titles duplicate / over length
- meta descriptions missing / duplicate

### Buoc 2: Lay data performance

Tu `GSC`, export:

- pages
- queries
- clicks
- impressions
- CTR
- position

Dung khung 3 thang, 6 thang, hoac 12 thang tuy nhu cau.

### Buoc 3: Lay backlink data

Tu `Semrush` hoac `Ahrefs`, export:

- target URL
- referring domains
- backlinks
- anchor
- follow / nofollow
- first seen
- last seen

### Buoc 4: Merge vao mot sheet quyet dinh

Moi dong la 1 URL. It nhat can co cac cot:

- URL
- status code
- indexability
- in sitemap
- canonical target
- noindex
- clicks
- impressions
- top query
- referring domains
- backlinks
- content type
- intent group
- action
- notes

### Buoc 5: Gan action

Chi dung 5 nhan:

- `keep`
- `improve`
- `301`
- `noindex`
- `delete`

### Buoc 6: Uu tien

Uu tien xu ly theo thu tu:

1. internal errors va redirect bugs
2. non-indexable URLs in sitemap
3. utility / archive bloat
4. broken canonical rules
5. content cannibalization
6. metadata debt
7. trust page va author transparency gaps

## 8. Cac pattern can canh bao ngay

Gap la note vao nhom `Critical` hoac `High`:

- utility pages la `200 + Indexable`
- URLs khong nen index nam trong sitemap
- redirect den URL dich bi `404`
- nhieu internal links tro den 404
- canonicals tro sai hoac canonical ve trang vo nghia
- duplicate posts voi slug `-2`, `-3`
- `uncategorized` dang index
- tag archives phong to nhung khong co gia tri
- author archive config khong nhat quan
- sponsored / advertorial archive dang tranh index voi content chinh

## 9. Ve metrics tuong tac

`comment`, `star rating`, `time on page`, `pageview` van co ich, nhung chi la metric phu.

Khong nen ra quyet dinh SEO audit chi dua vao:

- pageview
- time on page
- comment count
- star rating

Ly do:

- do la user behavior metrics, khong phai direct search demand signal
- nhieu site news khong co comment nhung van rank tot
- mot bai co pageview thap van co the co intent dung va can giu lai

## 10. Deliverable sau audit

Moi lan audit nen co 3 dau ra:

### Executive summary

- tinh trang tong quan
- 3-5 blockers lon nhat
- muc do uu tien
- action plan 30 / 60 / 90 ngay

### Master issue list

Moi issue can co:

- priority
- category
- issue
- evidence
- impact
- effort
- owner
- status

### URL decision sheet

Day la file quan trong nhat khi don site, remap, hay gom evergreen.

## 11. Bo cong cu de nghi

### Bat buoc

- `Google Search Console`
- `Screaming Frog`
- `Semrush` hoac `Ahrefs`

### Nen co them

- `Google Analytics`
- browser devtools
- URL inspection trong GSC

## 12. Nguyen tac can nho

- khong redirect bua ve homepage
- khong xoa hang loat chi vi bai khong co traffic
- khong giu utility pages trong sitemap
- khong dua vao 1 metric don le de quyet dinh URL
- uu tien sua kien truc crawl / index truoc khi don title meta
- trust pages va author transparency la mot phan cua audit, khong phai viec lam sau

## 13. Phien ban workflow nen ap dung

Neu lam audit tong the, workflow nen la:

1. crawl site
2. lay GSC performance
3. lay backlink exports
4. review trust pages va major templates
5. merge URL-level sheet
6. gan action cho tung URL
7. lap master issue list
8. chot action plan theo uu tien

Day moi la khung audit co the dung lai cho nhieu site ma van giam duoc rui ro quyet dinh sai.
