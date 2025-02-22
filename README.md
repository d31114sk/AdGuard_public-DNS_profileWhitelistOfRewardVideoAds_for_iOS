# AdGuard_public-DNS_profileWhitelistOfRewardVideoAds_for_iOS
iOSでAdGuard DNSの構成プロファイルを手動で取得する際に
プロファイルコンストラクタの対象外ドメインにカンマ区切りで入力するアプリ内リワード広告動画再生に必要なホワイトリストです

ポイントサイトやゲームアプリ等のリワード広告動画を再生して報酬を貰う為に必要な広告動画関係のドメインを並べています

※最低限リワード広告動画の再生さえ出来れば良いという考えを念頭に置いているので広告動画の内容を一部取得しなかったり表示が崩れる事もあります

ホワイトリストを適用したAdGuard DNSの構成プロファイルでも動画広告が再生できない場合は
再生に必要なドメイン名を調べて報告やホワイトリスト追加・更新して頂くと助かります(他力本願)

ファイルには改行が入ってますが全選択して例外ドメインの入力欄にコピペすれば改行を無視して入力できます

以下がiOSでのAdGuardの広告ブロックDNSの構成プロファイルのダウンロード手順です

出典:iOSにおける広告ブロック - なんJ AdGuard部 Wiki*

https://wikiwiki.jp/nanj-adguard/iOS%E3%81%AB%E3%81%8A%E3%81%91%E3%82%8B%E5%BA%83%E5%91%8A%E3%83%96%E3%83%AD%E3%83%83%E3%82%AF#ne6debc9

手順1)iPhone,iPadで https://adguard-dns.io/ja/public-dns.html を開く

手順2)「方法② AdGuard DNSを手動で設定する」をタップ

手順3)iOSをタップ

手順4)デフォルトサーバー若しくはファミリー保護サーバーにチェック

手順5)「プロファイルビルダーを開く」をタップし例外ドメインを入力

手順6)構成プロファイルをダウンロード

手順7)iPhoneの設定を開き「プロファイルがダウンロード済み」が表示されているので,タップしてプロファイルを”インストール”

手順8)設定→一般→VPNとデバイス管理→VPNを見て自動的にインストールしたプロファイルが選ばれている事を確認

手順9)手順8でインストールしたプロファイルが選ばれていない/別のプロファイルが選ばれている場合はインストールしたプロファイルを選び直す
