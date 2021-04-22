# コードレビュー、学習の振り返り用ファイルです。

##### All links for dev.

font-awesome : https://fontawesome.com/ \
※php の中では、Single quote じゃないとエラーになる

bootstrap : https://bit.ly/2P97x34

##### index.php

```
    <div class="input-group mb-2">
         <div class="input-group-prepend">
            <div class="input-group-text bg-warning"><i class="fas fa-id-badge"></i></div>
        </div>
            <input type="text" autocomplete="off" placeholder="ID" class="form-control"
                        id="inlineFormInputGroup" placeholder="Username">
    </div>

```

これを component.php を使ってこう書いてる

```
    <?php inputElement("<i class='fas fa-book'></i>", "Book name", "book_name", ""); ?>


```
