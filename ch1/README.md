# MEMO
- pytestの挙動確認
- pytestを実行対象を指定せずに実行した場合、以下のパターンに当てはまるファイルのテストが実行される
    - test_*.py
    - *_test.py
- VSCode@Windowsでvenvがうまく実行できない件について：
    - 以下のコマンドで実行できた。

```bash
python -m venv venv
source  ./venv/Scripts/activate #./を付けないとちゃんと動かない
pip install pytest
```