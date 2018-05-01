# phpstole
php简单网页内容处理类

    `$st= new stole();
     $content=$st->getContent("http://www.skymvc.com/");
    //匹配单个条件
    $title=$st->preg_one('<title>({title=.*})</title>');
    //剪切Html
    $st->cutHtml('<ul class="data-list">');
    //移除Html
    $st->removeHtml('<div class="img">');
    //匹配多个条件
    $arr=$st->preg_all('<a class=\"aurl\" href=\"({url=.*})\">');
    print_r($arr);
`
