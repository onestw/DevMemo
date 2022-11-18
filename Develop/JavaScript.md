
・ <script> 要素はHTML ファイルの末尾付近に置く  
   →ブラウザーがファイルに現れる順番でコードを読み込むから。  
     JavaScript が先に読み込まれ、まだ読み込まれていないHTMLに影響を与えることになると、問題が生じる可能性がある。  
・変数  
   const/let/var  
   String('')/Number/Boolean/Array/Object  
   (Objectは基本的には何でも格納OK。 JavaScriptのすべてがオブジェクトであり、変数に格納することができる。)  
   
   let、var、constの違い
   |  | let | var | const |
   | :--- | :--- | :--- | :--- |
   | 再宣言 | 不可能 | 可能 | 不可能 |
   | 再代入 | 可能 | 可能 | 不可能 |
   | スコープ | ブロックスコープ | 関数スコープ | ブロックスコープ |
   | 繰り返し構文 | 可能 | 可能 | 不可能 |
   
   基本はconstで定義する。繰り返し構文のみletを定義する。  
   varは使用しない方が良い。→まざまな場面で利用できる反面、意図しない再宣言や再代入によってエラーにつながる可能性がある。  

・演算子  
    厳密等価：===  
    否定・非等価：!,!==  

・関数  
    let myHTML = document.querySelector('html');  
    myHTML.addEventListener('click', function () {  
      alert('XXX');  
    });  
    ⇒   document.querySelector('html').addEventListener('click', function () {  
            alert('XXX');
         });
         ⇒addEventListener()に渡した関数は、名前を持たないので無名関数。  
           無名関数の書き方として、アロー関数と呼ばれるものがある。アロー関数は() =>をfunction()の代わりに使用する。  
           document.querySelector('html').addEventListener('click', () => {  
              alert('XXX');
           });