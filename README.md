Create a Laravel Project after install Git and GitHub

## 使用 PhpStorm 建立 Laravel 專案之後上傳到自己的 Git 數據庫 (Repository)

這個部分困擾很久，參考的 [影片](https://www.youtube.com/watch?v=4KTbrOdm9aU) 久遠，所以差異很大。

自己摸索的結果，認為是從 Laravel IDE helper 的 git Repository拉到本地端並建立好 git 資料庫，所以 Vision Control 的部分已經設定好，但是 remote Repository 仍然是原本的分支。

1. 建立好 Laravel 專案之後，打開 Git 視窗，移除 remote
2. 對 local 的 master 右鍵 CheckOut
3. 編輯要編輯的檔案，如：.gitignore 增加 /composer.phar
4. Git | GitHub | Share Project on GitHub，輸入描述(Description)
5. 勾選有更新的檔案，按 Commit
6. 對 local 的 master 右鍵 Push (預設是 origin/master)

詳細的過程放在 Blogger「 [使用 PhpStorm 建立 Laravel 專案之後上傳到自己的 Git 數據庫 (Repository)](https://yincywebdev.blogspot.com/2021/11/use-phpstorm-build-laravel-project-and.html) 」
