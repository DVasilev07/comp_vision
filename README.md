# comp_vision


look recom - рекоммендации аксессуаров по фотографии lookа.

Описание:
1. по фотографии с помощью mrcnn определяется маска класса person 
2. маска раскладывается в цветовой спектр (knn)
3. подбираются аксессуары по цветовой совместимости


photo_classif - бинарная классификация фотографий подходящих/неподходящих для делового портала

Описание:
1. на фотографии детектируются объекты с помощью frcnn
2. определяется соответствие характеристик фото деловому стилю 
