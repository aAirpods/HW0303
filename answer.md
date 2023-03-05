# 第1次作業-作業-HW1
>
>學號：110111226
><br />
>姓名：李芸茜
><br />
>作業撰寫時間：36 (mins，包含程式撰寫時間)
><br />
>最後撰寫文件日期：2023/03/05
>

本份文件包含以下主題：(至少需下面兩項，若是有多者可以自行新增)
- [x] 說明內容
- [x] 個人認為完成作業須具備觀念

## 說明內容

1. 為何需要系統分析?

    答案：
         在具有不確定約束或邊界條件的情況下，對系統要素進行綜合分析、描述，得出較為準確或合理的結論。
2. 請參閱課本或是投影片後，請結合課本與課外自行查閱資料，說明軟體發展程序有哪兩種且其各代表為何種運作方式及其特點？

    答案：
         規範式程序：將軟體發展分為幾個階段進行，每一個階段要完成的工作必須事先仔細定義好。上個執行階段執行完之後才執行下個階段工作，每一階段完成後 必須得到使用者的確認。
         敏捷式程序：強調在能夠快速回應使用者的需求改變與環境變化，採用了反覆與漸增式的發展方式。強調專案的快速回應能力，須遵守一組「原則」

開始寫說明，該說明需說明想法，
並於之後再對上述想法的每一部分將程式進一步進行展現，
若需引用程式區則使用下面方法，
若為.cs檔內程式除了於敘述中需註明檔案名稱外，
還需使用語法` ```語言種類 程式碼 ``` `，其中語言種類若是要用python則使用py，java則使用java，C/C++則使用cpp，
下段程式碼為語言種類選擇csharp使用後結果：

```csharp
public void mt_getResult(){
    ...
}
```

若要於內文中標示部分網頁檔，則使用以下標籤` ```html 程式碼 ``` `，
下段程式碼則為使用後結果：

```html
<%@ Page Language="C#" AutoEventWireup="true" ...>

<!DOCTYPE html>

<html xmlns="http://www.w3.org/1999/xhtml">
<head runat="server">
<meta http-equiv="Content-Type" ...>
    <title></title>
</head>
<body>
    <form id="form1" runat="server">
        <div>
        </div>
    </form>
</body>
</html>
```
更多markdown方法可參閱[https://ithelp.ithome.com.tw/articles/10203758](https://ithelp.ithome.com.tw/articles/10203758)

## 個人認為完成作業須具備觀念

開始寫說明，需要說明本次作業個人覺得需學會那些觀念，亦可作為學習筆記使用 (需寫成文章，需最少50字，並且文內不得有你、我、他三種文字)
     在git bash的動作順序是打git confit --list確認目前git的設定狀況，接著設定使用者名稱 git config --global user.name"使用者名稱"，設定信箱 git config --global user.email 信箱@.com，再獲取ssh鑰匙ssh-genkey 並複製.pub檔的內容，最後打上git config --global core.editor "code--wait"。