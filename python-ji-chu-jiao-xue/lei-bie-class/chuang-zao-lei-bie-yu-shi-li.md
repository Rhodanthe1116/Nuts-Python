# 實例 Instance

## 實例 Create Instance

只創造 Class 並不會創造出任何新的物件，因為Class只是一個模板而已，需要透過創造實例來創造新物件，就跟有了int，還要再給他一個數字一樣。 **實例 Instance** 是類別的具象化。**區別類別與實例非常重要！**

```python
class Character:
     hp = 100

# Create instance
new_character = Character()

print(type(new_character))
# <class '__main__.Character'>
```

在第 5 行利用`Characer()`創造一個新的實例物件，再將`new_character`指定為他。若利用`type()`會發現他的class為`Character`

## 💻練習

{% hint style="info" %}
* [ ] 參考上面的說明，撰寫一個名為`Song`的類別
* [ ] 為他加上`name`, `artist`, `album`三個屬性
* [ ] 創造一個實例，取名`new_song`
{% endhint %}

{% tabs %}
{% tab title="First Tab" %}

{% endtab %}

{% tab title="參考答案" %}
```python
class Song:
    name = "song name"
    artist = "artist name"
    album = "album name"
    
new_song = Song()
```
{% endtab %}
{% endtabs %}



