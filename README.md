# SageMaker で Stable Diffusion(チェックポイントなど) を使う

* SageMaker Studio を起動後に、 Launcher タブで Open Image terminal を開き以下を実行する
* Github の設定

```
ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
git config --global user.email "your_email@example.com"
git config --global user.name "Your Name"
# Github の SSH Keys に以下内容を登録 https://github.com/settings/keys
cat ~/.ssh/id_rsa.pub
```

新しくリポジトリを作る場合
```
echo "# sagemaker-stable-diffusion" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:himanushi/sagemaker-stable-diffusion.git
git push -u origin main
```
