Жизненный цикл компонента

Жизненный цикл компонента включает в себя 4 фазы

1. Инициализация - Initialization
state/props - constractor - наш компонент создается (классовые компоненты)

2. Монтирование - Mounting
    компонент React монтируется (прикрепляется) и попадает в DOM(Document Object Model) 
    Объектная Модель Документа (DOM) – это программный интерфейс (API) для HTML и XML документов.

    Основой HTML-документа являются теги.

    В соответствии с объектной моделью документа («Document Object Model», коротко DOM), каждый HTML-тег является объектом. Вложенные теги являются «детьми» родительского элемента. Текст, который находится внутри тега, также является объектом. (https://learn.javascript.ru/dom-nodes)

    render() - is called fot the first time and shows what is on our page. I it renders or shows on the screen for the first time

    componentWillMount() (not in this Module)
    componentDidMount() (used in this Module)
    

3. Обновление - Updating
    Change of state and repeat render()

    shouldComponentUpdate() (not in this Module)
    componentWillUpdate() (not in this Module)
    componentDidUpdate((not in this Module))

4. Размонтирование - Unmounting
    Last step of componets life cycle and removal from DOM

    componentWillUnmount() (used in this Module)
