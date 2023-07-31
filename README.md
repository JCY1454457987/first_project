测试github----
1.首先git bash中通过
  git config --global user.name JCY1454457987
  git config --global user.email 1245206748@qq.com
  绑定github账号
2.生成ssh
  ssh-keygen -t rsa -C 1245206748@qq.com 
  产生对应这个账号的ssh
  cat ~/.ssh/id_rsa.pub
  读出这个ssh
