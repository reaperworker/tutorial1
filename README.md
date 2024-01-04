### MIDI ファイルについて
#### [x1.mid](https://github.com/reaperworker/tutorial1/blob/main/x1.mid)  
E4(064)をベロシティ1から127まで１回だけ鳴らします。
IvoryII GrandPianos はこちらで十分だと思います。
#### [x100.mid](https://github.com/reaperworker/tutorial1/blob/main/x100.mid)  
E4(064)をベロシティ1から127まで100回づつ鳴らします。
Ivory3 にはラウンドロビン的な機能があるのでしょうか？
無いことが明らかであれば x1.mid を使用してください、
不明な場合は x100.mid 使用してください。

### レンダリング手順
1. Reaper を起動します。

2. 前回使用していたプロジェクトがロードされるので、新たなプロジェクトを作ります。  
[File]->[New project]

3. MIDIファイルを読み込みます。  
[Insert]->[Media file]

4. 再生開始位置がデータの最後になるので先頭にします。  
![001](https://github.com/reaperworker/tutorial1/assets/155607404/b6a1c716-fb89-4612-a037-79b65bce3c34)

5. 測定対象の音源をロードし、対象のプリセットを読み込みます。  
![002](https://github.com/reaperworker/tutorial1/assets/155607404/5dbf5573-69c5-49db-af14-39eac54530de)
![003](https://github.com/reaperworker/tutorial1/assets/155607404/784a41ce-5e94-4ff2-8f3d-c73fabd999cd)

6. レンダリングを実行します。  
[File]->[Render]  
ファイルの保存先とファイル名フォーマットを選択して実行します。  
![005](https://github.com/reaperworker/tutorial1/assets/155607404/9a326d0f-cea5-450f-b34f-59f1b25feaf2)

7. レンダリングが完了するまで待ちます。  
![006](https://github.com/reaperworker/tutorial1/assets/155607404/23ca323b-f778-4b84-b2f7-538a503e8ea1)
![007](https://github.com/reaperworker/tutorial1/assets/155607404/aec89eec-99a5-454b-aacd-16bfb432860a)

8. 必要があればプロジェクトを保存します。  
[File]->[Save project]
