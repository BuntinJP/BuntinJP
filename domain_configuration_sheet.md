
## ドメイン管理シート

### Town.INC 提出資料

端末
RHEL 自宅
GC GoogleCloud
DO DigitalOcean
AWS AWS RDS,S3,EC2
Azure (削除済み)

### buntin.tech

ポリシー

基本的にCloudflareのプロキシ無し

RHELへのアクセス用

メール関連設定は削除

レジストリをXServerからCloudflareへ移管済

レコード

- A -> 自宅RHEL

### buntin.xyz

ポリシー

基本的にCloudflareのプロキシ**有り**

RHELへのアクセス用

RHELへのCloudflare Tunnelには基本的にこちらを使う

- A -> RHEL

### buntinjp.net

現在使用していない

### synthia-liz.com

ポリシー

基本的に、GCへの接続用

メールがiCloudのメールサーバに登録済み

プロキシ有り、無しが混在

@(root)はプロキシ無しのGC指し

### conbios.systems

移管できるか謎

ポリシー

DigitalOceanへのプロキシ有りアクセス専用になっている。
Cloudflareの設定が消すのが面倒なため、放置気味、研究で使えるかも

aoki.work

使用していない


