# Git-Operation
## New file Upload
### 基本オペレーション動作
NewFileUpload.mdを編集して、アップロードする作業下記の流れ
 1. 新規作成する。（このファイル）
 2. Gitのステージングに上げる（Add）
 3. Commitする 
 4. pushする

#### Step0. New File
  - This is New File

#### Step1. ステージングにあげる
`git add NewFileUpload.md`

#### Step2. Commit する -m はコメント
`git commit -m "Newfile Push"`

#### Step3. Git log でコミット内容を確認できる
`git log`

#### Step4. Push する（アップロード）
`git push origin`
