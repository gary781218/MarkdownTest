# 說明

此為Markdown語法練習，將專案上傳到githubg上，為了讓其他人能快速概要性的明白功能，故通常會將重點寫在.md檔，最近看到保哥的教學，就直接練習起來了，GO!

</br>

## 一、如何標記標題?

要使用標題要用「#」來標記，#與標題之間必須保留一個space。  
如果需要子標題，可用#的數量來表示，如## 標題二、### 標題三...  
經筆者測試，最多能到第六層。

</br>

## 二、如何使用分隔線

分隔線主要是使用-與*來實現，可以用3個或多個來表示，結果如下。

    第一種方法  * * *
    第二種方法  ***
    第三種方法  *****
    第四種方法  - - -
    第五種方法  ---------------------------------------

</br>

## 三、如何列出清單

做法有幾下列幾種:

1. 手動在文字前以「+」 「-」 「*」來標記，標記與清單名稱之間必須保留一個space。
2. 清單文字選起來，按下ctrl + shift + p，並輸入markdown toggle，找到Markdown All in one: toggle list，重複使用會變成不同的list。

結果如下

+ 猩猩
+ 猴子
+ 狒狒

</br>

## 四、建立檢查清單

手動在文字前以「-」來標記，接上中括號並在括號內保留一個space。
按alt + c 可以勾選或或取消

- [x] 代辦工作1
- [x] 代辦工作2
- [ ] 代辦工作3

</br>

## 五、使用引言

在要做為引言的文字前，以「>」來標記，跟段落一樣，可以使用數量來產生子引言。結果如下

>十年生死兩茫茫，寫程式，到天亮。
>千行程式碼，Bug何處藏。</br>
>縱使上線又怎樣，朝令改，夕斷腸。</br>
>領導每天新想法，天天改，日日忙。</br>
>相顧無言，惟有淚千行。</br>
>每晚燈火闌珊處，夜難寐，又加班。</br>
>>子引言

</br>

## 六、文字區塊或程式碼區塊

### 文字區塊

僅需用用tab或space，超過4格以上會自動轉換為文字區塊。結果如下

    十年生死兩茫茫，寫程式，到天亮。
    千行程式碼，Bug何處藏。
    縱使上線又怎樣，朝令改，夕斷腸。
    領導每天新想法，天天改，日日忙。
    相顧無言，惟有淚千行。
    每晚燈火闌珊處，夜難寐，又加班。

</br>

### 程式碼區塊

需使用2組「```」來做標記程式碼，括號內為三個反引號。第一組反引號可加上Languege Code，但要看各平台的定義。顯示結果如下

```js
Console.log("Hello World!");
Console.log("Hello World!");
```

## 七、表格

表格的操作在原本的文件中並沒有看到，而原本表格的標記方法真的看了會頭痛，反而失去了原本作者的美意。幸好最近看到保哥的教學，厲害的開發者總是可以用更輕鬆的方式工作先將表格在EXCEL打好，複製完在這裡使用alt + shift + v，結果如下

</br>

| 學號 | 姓名 | 成績 | 備註  |
|----|----|----|-----|
| 1  | 猴子 | 50 |     |
| 2  | 猩猩 | 60 | 黑黑的 |
| 3  | 狒狒 | 70 |

</br>

## 八、圖片與超連結

手動打出[Link Text](Link URL)的方式來做一般文字的超連結，也先複製連結，將文字反白後ctrl + v，即可直接建立連結。ctrl + k則會產生空白的載入圖片則![Image Alt Text](Image URL)，還可以更改圖片的大小，範例如下

[超連結在此](https://www.google.com/?hl=zh_tw)

![猩猩](https://images.chinatimes.com/newsphoto/2021-04-10/1024/20210410002170.jpg)
