# vue-spot-modal

その場でささっと表示させたい時かとで使えるかも。  

[DEMO](https://mattune.github.io/vue-spot-modal/)

## 導入方法
1. /src/components/spotModal.vue を任意の場所に追加。

## 使用方法
詳しくはApp.vueを参照  
```html
<spotModal :position="位置用の文字列">
  <好きなhtmlを入れる>
</spotModal>
```

## その他
制御は親コンポーネントからゴニョゴニョしてください。  

位置用の文字列  
→ top / bottom / left / right / tooltip
 
isShow  
→表示状態を返す(デフォルトは false )

spotModalShow()  
→開く

spotModalHide()  
→閉じる
