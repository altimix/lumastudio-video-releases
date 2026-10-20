# LumaStudio VIDEO 公式配布

Windows / macOS向けの動画編集アプリです。個人・学校・団体・企業で無償利用できます。商用目的でも利用できます。

**最新版は v1.11.0 です。** [ダウンロードと更新情報](https://github.com/altimix/lumastudio-video-releases/releases/tag/v1.11.0)から、お使いの環境に合うアプリを入手してください。

| お使いの環境 | ダウンロード | 起動方法 |
| --- | --- | --- |
| Windows 64bit | [Luma-Studio-1.11.0-Windows.exe](https://github.com/altimix/lumastudio-video-releases/releases/download/v1.11.0/Luma-Studio-1.11.0-Windows.exe) | [Windows向け案内](https://github.com/altimix/lumastudio-video-releases/releases/download/v1.11.0/README-Windows.txt) |
| Mac（Apple Silicon） | [Luma-Studio-1.11.0-macOS-arm64.zip](https://github.com/altimix/lumastudio-video-releases/releases/download/v1.11.0/Luma-Studio-1.11.0-macOS-arm64.zip) | [Mac向け案内](https://github.com/altimix/lumastudio-video-releases/releases/download/v1.11.0/README-Mac.txt) |

Windows版は64bitのポータブルEXE、Mac版はApple Silicon用のZIPです。[SHA256SUMS.txt](https://github.com/altimix/lumastudio-video-releases/releases/download/v1.11.0/SHA256SUMS.txt)で配布ファイルのチェックサムを確認できます。Windows版は未署名、Mac版はad-hoc署名付きで、Developer ID署名・Apple公証は行っていません。

v1.11.0では、AI字幕をタイムラインへ配置するときに、フォント・文字サイズ・縁取り・影・背景の有無や色、背景の透明度を設定できます。数値欄は左右ドラッグでも調整できます。サムネイルの「おまかせ」はタイトル・概要欄・字幕を読み取り、短い補足からも構図を作成します。生成ボタンも小さい画面で操作しやすくしました。AI機能には別途API設定と利用料が必要です。

- [VIDEO公式サイト・使い方](https://video.lumastudio.jp/)
- [LumaStudioシリーズ（VIDEO・PDF・CAD・Vector）](https://lumastudio.jp/)
- [画像付きマニュアル](https://lumastudio.jp/manual/)
- [アプリの利用条件](LICENSE)
- [第三者部品の通知](THIRD_PARTY_NOTICES.md)・[ライセンス全文](THIRD_PARTY_LICENSES.txt)
- [不具合・機能の提案](https://github.com/altimix/lumastudio-video-releases/issues)
- [お問い合わせ](https://altimix.co.jp/contact/)

このリポジトリはアプリの配布、更新情報、不具合報告、利用条件、第三者部品の通知を扱います。自作のアプリ本体はv1.10.12から独自の利用条件で提供し、開発ソースと履歴は非公開です。利用・複製等の許諾範囲は[LICENSE](LICENSE)を確認してください。

第三者部品の利用・改変・再配布等には、各部品のライセンスが適用されます。アプリ本体の利用条件は、各部品のライセンスが認める権利を制限しません。必要な対応ソースとビルド情報は、同じリリースの[Luma-Studio-1.11.0-media-sources.zip](https://github.com/altimix/lumastudio-video-releases/releases/download/v1.11.0/Luma-Studio-1.11.0-media-sources.zip)で提供します。第三者ライセンスの全文と通知も配布物に含まれます。

非公開化前に開発リポジトリで配布していた旧版の公式配布は終了しました。それらの旧版からの最初の移行は、上の配布ページから手動で行ってください。これらの旧版に組み込まれた更新先は、開発リポジトリの非公開化により利用できません。既にGPL等に基づいて受領した旧版には、その版の条件が引き続き適用されます。公式配布終了は、受領済みコピーの権利を取り消すものではありません。

実際の制作物、秘密鍵、APIキー、個人情報を公開Issueに添付しないでください。GitHubが自動生成する「Source code」のZIP/TARは、この配布案内リポジトリの内容です。アプリ本体の開発ソースは含みません。アプリのダウンロードには上の環境別リンクを使ってください。
