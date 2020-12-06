# distinctUntilChanged - не трегирит стрим если значение не изменилось если предыдущее значение не изменилось!

# switchMap - переключает на другой стрим на основе или с настройками старого, то что передаются в параметры

# mergeMap разбивает массив на каждый отдельный запрос (в данном примере)

# EMPTY - при пустом поле не ломает стрим

# takeUntil будет получать значения от стрима, пока не срабодает другой стрим

# pairwise возвращает не только текущее значение, но в месте с ним и предыдущее значение последовательности []

# withLatestFrom позволяет забрать последние значения из стримов

# startWith передает начальное значение

<!-- function onlyUnique(value, index, self) {
    return self.indexOf(value) === index;
 } -->

<!-- usage example:
 var a = ['a', 1, 'a', 2, '1'];
 var unique = a.filter( onlyUnique ); // returns ['a', 1, 2, '1'] -->

<!-- Number.isInteger();
Number.isNaN();
typeof value === 'number'
instanceof Number -->
