#◆セレクター

 | セレクター名 | 選択するもの | 例 |
 | :--- | :--- | :--- |
 | 要素セレクター<br>(タグOR型セレクターとの呼ぶ) | 指定された型のすべてのHTML要素 | p<br>\<p\>を選択 |
 | ID セレクター | 指定されたIDを持つページ上の要素。<br>指定されたHTMLページでは、各id値は一意でなければならない。 | \#my-id<br>\<p id="my-id"\> または \<a id="my-id"\> を選択 |
 | クラスセレクター | 指定されたクラスを持つページ上の要素。<br>同じクラスの複数のインスタンスが1つのページに現れることがある。 | \.my-class<br>\<p class="my-class"\> および \<a class="my-class"\> を選択 |
 | 属性セレクター | 指定された属性を持つページ上の要素。 | img[src]<br>\<img src="myimage.png"\> は選択するが \<img\> は選択しない |
 | 擬似クラスセレクター | 指定された要素が指定された状態にあるとき。<br>（例えば、マウスポインターが上に乗っている（ホバー）状態。） | a:hover<br>\<a\> を、マウスポインターがリンク上にあるときのみ選択。|
 
 その他様々なセレクターが存在する。  
 参考資料<https://developer.mozilla.org/ja/docs/Learn/CSS/Building_blocks/Selectors>


#◆フォント
  参考資料<https://fonts.google.com/>  
  ↑サイトで選択したフォントの使用方法<https://developers.google.com/fonts/docs/getting_started>  
  ・フォントファミリーに含まれるスペースはすべてプラス(∔)記号に置き換える  
  ・複数のフォントファミリーを使用する場合はパイプ文字(|)で区切る  
  【例】https://fonts.googleapis.com/css?family=Inconsolata
  
  