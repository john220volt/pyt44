Задание 44
В ячейке ниже представлен код генерирующий DataFrame, которая состоит всего из 1 столбца. Ваша задача перевести его в one hot вид. Сможете ли вы это сделать без get_dummies?
импорт random lst = ['робот'] * 10 lst += ['человек'] * 10 random.shuffle(lst) data = pd.DataFrame({'whoami'lst}) data.head() |
