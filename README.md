# phpipam-japanese
[phpipam](https://phpipam.net/) の日本語翻訳ファイルです

編集にpoeditを使う場合頭に以下の情報が入っていないと言語設定がされていない状態になります。

ただし、そのままコンパイルすると、コメント部分が画面に出てしまうので、コンパイル時には以下をコメントアウトしてください。

```
msgid ""
msgstr ""
"Project-Id-Version: \n" 
"POT-Creation-Date: \n" 
"PO-Revision-Date: \n" 
"Last-Translator: \n" 
"Language-Team: \n" 
"MIME-Version: 1.0\n"
"Content-Type: text/plain; charset=UTF-8\n"
"Content-Transfer-Encoding: 8bit\n"
"Language: ja_JP\n"
"X-Generator: Poedit 2.1.1\n"
"Plural-Forms: nplurals=1; plural=0;\n"
```

- コンパイル用のコマンド

```
msgfmt phpipam.po -o phpipam.mo
```

- 生成されたファイルを以下のディレクトリに置きます

```
functions/locale/ja_JP.UTF-8/LC_MESSAGES/
```

