# Usage

```
- name : Install CppUnit
  uses : takahiro-itou/install-cppunit-action@v1.1.1
  with :
    # Install Directory.
    # インストール先ディレクトリ
    # Default : ${{ github.workspace }}/tools/cppunit
    install-prefix : "${{ github.workspace }}/tools/cppunit"

    # Version of CppUnit
    # インストールする CppUnit のバージョン
    # Default : 1.15.1
    version : '1.15.1'

    # SHA256 Hash of source tar.gz file
    # ソースファイルの SHA256 ハッシュ値
    # Default : the sha256 hash of version 1.15.1
    # In the current version, this value is not used.
    # 現在のバージョンでは、この値は使われない。
    sha256 : 89c5c6665337f56fd2db36bc3805a5619709d51fb136e51937072f63fcc717a7
```
