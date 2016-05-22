# For graduate study


#Algorism

経路探索</br>
　現在位置・目的地の入力と地図データから、できるだけ直線的な移動経路を計算する。</br>
　　曲がるポイントをサブゴールと呼ぶ。</br>
　　サブゴールの設定にはできるだけ誤差修正ポイントを適用する。</br>
</br>

移動処理</br>
　ロータリエンコーダ・デジタルコンパスからの情報を受けながら、サブゴールまで直線的に移動する。サブゴールで方向転換し、再び直線的に移動する。</br>
</br>

画像処理</br>
　誤差修正ポイントについたときは、カメラを起動して周囲をスキャンし、位置を修正する。</br>
</br>
  
ユーザーインタフェース</br>
　GUI</br>
　　目的地の入力</br>
　　現在位置の表示</br>
　音声出力</br>
　　扉やエレベータなどの、人間の補助が必要なところではその旨を伝える。</br>
　連携</br>
　　外部デバイス(スマートフォンなど)との連携
