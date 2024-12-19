slackbotを作成してdifyのチャットアプリでの応答をslack上で実装
# .envファイルを作成して環境変数を設定
# パッケージのインストール
pip install slack_bolt python-dotenv requests
#実行
python /Users/kotaro/slackbot-dify01/difyapp01.py


# 仮想環境で実行する場合（返答はできない？）
- venvファイルを作成
python3 -m venv venv
source venv/bin/activate
