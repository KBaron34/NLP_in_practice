# NLP_in_practice
Соревнования от Альфа-банка по структуризации чеков ОФД

Ссылка на данные: https://ods.ai/competitions/nlp-receipts/data

Описание задачи:
Данные чеков ОФД содержат детальную информацию о тратах клиентов. Они помогают улучшать качество моделей кредитного скоринга и склонности к банковским продуктам, а также улучшать пользовательский опыт за счет структуризации трат клиентов в мобильном приложении. Однако работа с этим источником затрудняется его неструктурированностью: вся информация о купленном товаре лежит в одной строке произвольного формата.
В предположении что каждая чековая позиция описывает какой-либо товар, наименование этого товара, а также его бренд, являются главной информацией, которую можно извлечь из чека. По итогу задача структуризации этих данных ограничивается выделением и нормализацией брендов и товаров.
Участникам соревнования предоставляются два датасета с чековыми позициями, размеченный и неразмеченный:
В размеченном датасете для каждой чековой позиции указаны нормализованные бренды и товары входящие в нее в исходном виде. В неразмеченном датасете даны только сами чековые позиции.
