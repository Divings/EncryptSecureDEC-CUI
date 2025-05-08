# EncryptSecureDEC

**EncryptSecureDEC** は、ファイルを安全に暗号化・復号するための高セキュリティCLIツールです。  
AES-GCMによる暗号化とハッシュログの追跡機能を組み合わせ、改ざん検知・証拠保全に対応します。

---

## 📦 インストール方法

### `.deb` パッケージを使用

1. パッケージをインストール：

```bash
sudo dpkg -i encryptsecuredec_1.2.0_amd64.deb
```

2. 実行ファイルの確認：

```bash
which EncryptSecureDEC
```

→ `/usr/local/bin/EncryptSecureDEC` にインストールされます。

---

## 🛠️ 使用方法

```bash
EncryptSecureDEC [オプション] <ファイル>
```

オプション例（バージョンによって異なります）：

| オプション | 説明                |
|------------|---------------------|
| `-e`       | ファイルを暗号化     |
| `-d`       | ファイルを復号       |
| `--help`   | ヘルプを表示        |
| `--version`| バージョン情報を表示 |

※詳細は開発者にお問い合わせください。

---

## 📄 ライセンス

本ソフトウェアは **プロプライエタリライセンス**（非OSS）です。  
ライセンスの詳細は `/usr/share/doc/encryptsecuredec/LICENSE` および `EULA.txt` を参照してください。

- 再配布・改変・商用利用は明示的な許可がない限り禁止されています。
- 利用にはエンドユーザーライセンス契約（EULA）への同意が必要です。

---

## 🏢 開発者

**Innovation Craft Inc.**  
Email: innovationcraft@outlook.jp  
Website: https://anvelk.jp

---

## 🗓️ 初版リリース日

2025年5月08日
