1. В Stack Memory создается примитив i = 1;
1. Отрабатывют ClassLoader'ы в куче создается объект, а в стаке ссылка на него;
1. В куче создается объект Integer, а в стаке ссылка на него;
1. В стаке создается новый фрем для метода printAll, который ссылается на указанные в скобках объекты;
1. В фрейме printAll создается ссылка на Integer объект в куче;
1. В стаке создается новый фрейм println со ссылками на указанные в скобках объекты;
1. Закравается фрейм printAll, создается фрейм println со ссылкой на String объект в куче; 
