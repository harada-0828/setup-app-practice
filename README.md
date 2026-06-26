# setup-app-practice

## 概要
COACHTECH 教材 Tutorial 9-1「環境構築ハンズオン」で作成した成果物です。
Laravel Sail と Docker を使って、Tutorial 9〜10 のハンズオンで使う為に開発環境を構築しました。

## 使用技術
- PHP 8.x
- Laravel 10.x
- Laravel Sail（Docker Compose）
- MySQL, phpMyAdmin

## 学んだこと
- laraverl sailを使用する際の準備段階として目的に合わせた環境設定が必要なこと。全体の中では一部になるが現在は課題のハンズオンに向けての設定を行ったこと。細かい部分でより作業がしやすくなるような設定（エイリアス）が行われている事を理由を含めて学びました。
- 

## 動作確認
環境構築が完了後、正常に起動するかの確認。
１、VSCodeのターミナルを開き、以下のコマンドを実行してsailを起動。
　　./vendor/bin/sail up -d
２、また、起動状態を確認するために以下のコマンドを実行し、NAMEなど　　各項目がup状態になっているか確認した。
　　./vendor/bin/sail ps
３、その後、環境構築が正しく行えたか確認の為、ブラウザで Laravelア　　プリケーション・データベースにそれぞれ接続を行い、画面が表示され　　るかの確認を行った。


