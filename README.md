# AnimeOne
AnimeOne不是官方APP。這是我自己用Flutter寫的三方APP。我的第一個React Native的APP是用來看動漫的，第一個Flutter的APP也是用來看動漫的。これは運命かもしれない。

If you prefer watching anime with English subtitle, you might consider [AnimeGo](https://github.com/HenryQuan/AnimeGo).

## 功能
- 最新動畫
- 動畫列表
- 快速搜索
- 新番時間表
- 新番介紹視頻
- 内置視頻播放器
- 自動軟件更新
- 自動夜間模式

## 關於
目前版本已經可以正常使用。
有一些數據會到本地本地（每周會更新一次數據）。
這是因爲動畫列表以及新番時間表并不會每天都更新，
所以APP也沒有理由每次開打都重新下載一遍數據。

## 截圖
<div>
  <img src="https://raw.githubusercontent.com/HenryQuan/AnimeOne/master/screenshot/1.jpg" width="180px" height="320px" />
  <img src="https://raw.githubusercontent.com/HenryQuan/AnimeOne/master/screenshot/2.jpg" width="180px" height="320px" />
  <img src="https://raw.githubusercontent.com/HenryQuan/AnimeOne/master/screenshot/3.jpg" width="180px" height="320px" />
  <img src="https://raw.githubusercontent.com/HenryQuan/AnimeOne/master/screenshot/4.jpg" width="180px" height="320px" />
  <img src="https://raw.githubusercontent.com/HenryQuan/AnimeOne/master/screenshot/5.jpg" width="180px" height="320px" />
</div>

## 下載安裝
安卓可以在[這裏下載](https://github.com/HenryQuan/AnimeOne/releases/latest)，IOS則需要自己使用Xcode進行編譯。

### Xcode如何編譯
- 在電腦上安裝Flutter以及Xcode
- 使用`flutter doctor`指令來檢查是否設置成功
- 進入`animeone`文件夾（注意是小寫）
- 使用`flutter build ios --release`獲得release包 （如果代碼沒有變化的話，只需要運行一次）
- 進入Xcode打開ios文件夾下的`Runner.xcworkspace`
- 在暫停按鈕旁邊選擇`RunnerRelease`
- 點擊運行按鈕
- 等一會兒
- App打開
- 每七天重複一次

## 支持
- 給Repo一個星星
- 上面的Sponsor按鈕
