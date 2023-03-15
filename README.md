# Useful_links
Important and useful resources

## Заголовок первого уровня
## Заголовок второго уровня
### Заголовок третьего уровня
###### Heading level 6

**bold text** <br>
*italicized text*


Перенос строки:
так не переностися

А, если поставить 2 пробела в конце строки,  
тогда переносится без разрыва между строками

Чтобы сделать пустую строку между строками,

то нужно сделать двойной перенос строки

> Цитата (Blockquote)

Ordered List:
1. First item
2. Second item
3. Third item

Unordered List:
- First item
- Second item
- Third item

Код:

`	if(PrintLog["mon_Q"].size()>1)
	 {strLog+="\t"+PrintLog["function"].at(1)+"\t"+PrintLog["note"].at(1);
	  for(auto it=PrintLog.begin(); it!=PrintLog.end(); ++it)
	   {it->second.erase(it->second.begin()+1);
	   };
	 };`
   
   ---
   --
   ---
   ----
   -----
   ------
   -------
   
   [Название для ссылки](https://www.example.com)
   
   ![Альтернативный текст для картинки](image.jpg)  
   
   ![Тут должен быть octocat](https://myoctocat.com/assets/images/base-octocat.svg)
   
   ## Extended Syntax
   
| Syntax | Описание  |
| ----------- | ----------- |
| Header | Title |
| Пункт | Text |
| Header | Title |
| ----------- | ----------- |
| Пункт | Text |
| Пункт | Text |


# Выделенный блок кода:
```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

Footnote (Сноска, Примечание):
Here's a sentence with a footnote. [^1]
Это предложение со второй сноской. [^2]
Это предложение с четвертым примечанием. [^4]

Это ссылка на однострочное примечание,[^1] а это ссылка на многоострочное примечание.[^bignote]

[^1]: This is the first footnote.
[^2]: Это второе примечание
[^4]: Это четвертое примечание. 

[^bignote]: Here's one with multiple paragraphs and code.

    Indent (Отступ) paragraphs to include them in the footnote.

    `{ my code }`

    Add as many paragraphs as you like.


### My Great Heading {#custom-id}
Добавление пользовательских идентификаторов позволяет напрямую ссылаться на заголовки и изменять их с помощью CSS. Чтобы добавить пользовательский идентификатор заголовка, заключите его в фигурные скобки в той же строке, что и заголовок.   
Аналог в НТМL:
`<h3 id="custom-id">My Great Heading</h3>`


First Term  
: This is the definition of the first term.

Second Term
: This is one definition of the second term.
: This is another definition of the second term.
: У меня это не работает

~~Зачеркивание(Strikethrough) работает **только**~~, если его писать от самого *начала* строки!
  
Список задач:  
- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media

Эмодзи:  
That is so funny! :joy:   

👾 - [Эмодзи взят с этого сайта](https://emojipedia.org/)


Следующие 3 возможности у меня не работают:

I need to highlight these ==very important words==.

Subscript:	H~2~O  
Superscript:	X^2^=4

На HTML работает:  
H<sub>2</sub>O  
X<sup>2</sup>
