# バベル転生
サークルメンバー5名でオンライン鬼ごっこゲームを作成した。

## 使用言語・ツール等
![C#](https://img.shields.io/badge/c%23%20-%23239120.svg?&style=for-the-badge&logo=c-sharp&logoColor=white)
![Unity](https://img.shields.io/badge/unity%20-%23000000.svg?&style=for-the-badge&logo=unity&logoColor=white)

## UnityRoomに公開中
バベル転生: <https://unityroom.com/games/k3babel>

## 概要
非対称鬼ごっこゲーム

サメのプレイヤーは捕食を狙い、それ以外のプレイヤーはバベルの塔を建て、転生を狙う。

## 操作方法
WASD:移動

マウス:視点移動

サメ操作　左クリック:捕食

草食動物操作　スペースキー:バベル建設、アンチシャークフィールド起動

## 担当箇所
- プレイヤー、NPCの基盤作成(Agent.cs)
- NPCの作成(NPCController.cs, RayCast.cs)
- 動物の振り分け、表示等(AnimalList.cs, CharacterMaker.cs)
- Hashtableの作成(Ready.cs)
- 転生、捕食処理(Agent.cs, KillBall.cs, ProgressBar.cs)
- プレイヤー名表示(PhotonTextView.cs)
- スコアボード表示(PhotonScoreView.cs, ScoreManager.cs)

## 開発期間
7月下旬~11月
